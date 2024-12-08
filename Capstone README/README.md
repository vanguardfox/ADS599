# Project Title: Peripheral Blood Mononuclear Cell (PBMC) Population Clustering

This project explores and clusters PBMCs based on flow cytometry data using machine learning techniques.

## Project Status: Active

## Installation

To use this project, first clone the repository to your device:
```
git init
git clone https://github.com/vanguardfox/ADS599
```

TBD: After cloning, navigate to the project folder and install the required packages by running:
```
conda activate # Optional if using Anaconda to manage environment
pip install -r requirements.txt
```

## Running the Project

1. Ensure all data files are in the expected directories.
2. Execute the script | notebook | application to process the data
3. TBD

# Background
Flow cytometry is a biochemical analytical process that involves identifying and classifying populations of PBMCs - such as lymphocytes, monocytes, etc. - using chemical substrates, imaging, and highly-capital intensive medical research equipment. Clustering aims to simplify to a fundamentally objective level the classification accuracy of a given population's cellular type to further immunological and clinical diagnostic purposes. By exploring methods like Gaussian Mixture Modeling, K-means Clustering, and Density-based Spatial Clustering of Applications (DBSCAN), the dataset containing metrics on front and side scatter areas of cell scans, fluorescence on markers, and other dimensions can potentially lead to automatic gating via clustering and bring forth insights on cell population characteristics.

# Project Objective
To enhance and accelerate drug discovery process with cell clustering automation via machine-learning methods and modeling techniques in a cost-effective manner.

# Contributors
* Gabriella Rivera
* John Vincent Deniega

# Technologies
* Python
* scikit-learn
* Matplotlib
* Pandas

# Dataset:
FlowRepository. (2020). FlowRepository ID FR-FCM-Z32U. Retrieved from http://flowrepository.org/experiments/3166/download_ziped_files

# Project Description
This project uses flow cytometry data on PBMCs consisting of 1.5 gigabytes of Flow Cytometry Standard files from FlowRepository. There are about ten million records across 32 columns (channels in FCS standard) containing numerical floating data to include measurements on scans from forward scatter, side scatter, and fluorescence scans. The project aims to address the following questions:
* Can clustering methods or other unsupervised techniques accurately separate PBMC populations into potentially distinct cellular groups?
* How do clustering results vary with that of a human analyst?
* Are the clustering results that are obtained both timely and practical for use similar to that of a human analyst?

Current challenges include whether clustering algorithms will result in biochemically significant clusters, applying algorithms that will best describe these biochemical categories, and being constrained to low or no-cost resources such as personal Mac Air M1 devices and Google Colaboratory computing and memory.

* License
This project is licensed under the Apache License 2.0. See the LICENSE file for details.
