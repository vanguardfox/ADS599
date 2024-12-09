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

# References
1. Beckman Coulter. (2022). Automatic gating - Beckman Coulter. Flow Cytometry. https://www.beckman.com/flow-cytometry/software/cytobank-premium/learning-center/automatic-gating 
Brestoff, J. R., & Frater, J. L. (2022). Contemporary challenges in clinical flow cytometry: Small samples, big data, little time. Journal of Applied Laboratory Medicine, 7(22), 931-944. https://doi.org/10.1093/jalm/jfab176
2. Cossarizza, A., Chang, H. D., Radbruch, A., Acs, A., Adam, D., Adam-Klages, S., Agace, W. W., Aghaeepour, N., Akdis, M., Allez, M., Almeida, L. N., Alvisi, G., Anderson, G., Andrä, I., Annunziato, F., Anselmo, A., Bacher, P., Baldari, C. T., Bari, S., Barnaba, V., … Zychlinsky, A. (2019). Guidelines for the use of flow cytometry and cell sorting in immunological studies (second edition). European journal of immunology, 49(10), 1457–1973. https://doi.org/10.1002/eji.201970107 
3. FlowRepository. (2020). FlowRepository ID FR-FCM-Z32U. Retrieved from http://flowrepository.org/experiments/3166/download_ziped_files
4. Hennig, H., Rees, P., Blasi, T., Kamentsky, L., Hung, J., Dao, D., Carpenter, A. E., & Filby, A. (2016). An open-source solution for advanced imaging flow cytometry data analysis using machine learning. Methods, 112(2017), 201–210. http://dx.doi.org/10.1016/j.ymeth.2016.08.018
5. Hu, Z., Bhattacharya, S., & Butte, A. J. (2022). Application of machine learning for cytometry data. Frontiers in immunology, 12, 787574. https://doi.org/10.3389/fimmu.2021.787574 
6. Lee, J. A., Spidlen, J., Boyce, K., Cai, J., Crosbie, N., Dalphin, M., Furlong, J., Gasparetto, M., Goldberg, M., Goralczyk, E. M., Hyun, B., Jansen, K., Kollmann, T., Kong, M., Leif, R., McWeeney, S., Moloshok, T. D., Moore, W., Nolan, G., Nolan, J., … Brinkman, R. R. (2008). MIFlowCyt: the minimum information about a Flow Cytometry Experiment. Cytometry. Part A: the journal of the International Society for Analytical Cytology, 73(10), 926–930. https://doi.org/10.1002/cyto.a.20623 
7. Maecker, H. T., McCoy, J. P., & Nussenblatt, R. (2012). Standardizing immunophenotyping for the Human Immunology Project. Nature Reviews Immunology, 12(3), 191–200. https://doi.org/10.1038/nri3158 
8. Mair, F., & Leichti, T. (2020). Comprehensive Phenotyping of Human Dendritic Cells and Monocytes. Journal of Quantitative Cell Science, 99(3), 231–242. https://doi.org/10.1002/cyto.a.24269
9. Monaco, G., Chen, H., Poidinger, M., Chen, J., Magalhaes, J., & Larbi, A. (2016). FlowAI: Automatic and interactive anomaly discerning tools for flow cytometry data. Bioinformatics, 32(16), 2473–2480. https://doi.org/10.1093/bioinformatics/btw191
10. Ng, D. P., Simonson, P. D., Tarnok, A., Lucas, F., Kern, W., Rolf, N., Bogdanoski, G., Green, C., Brinkman, R. R., & Czechowska, K. (2024). Recommendations for using artificial intelligence in clinical flow cytometry. Cytometry part b: Clinical cytometry, 106(4), 228–238. https://doi.org/10.1002/cyto.b.22166 
11. Policar, P. (2023). How t-SNE works. Read the Docs. https://opentsne.readthedocs.io/en/latest/tsne_algorithm.html
Spidlen J, Breuer K, Rosenberg C, Kotecha N and Brinkman RR. (2012). FlowRepository - A Resource of Annotated Flow Cytometry Datasets Associated with Peer-reviewed Publications. Cytometry A. 81(9), 727-31. https://doi.org/10.1002/cyto.a.22106 


