# Land Use and Land Cover Dehradun (2015-2022) Project
![image](https://github.com/Hritikgoswami/Land-Use-Land-Cover-Dehradun/assets/84679973/c6ae11a4-d1ed-4a6f-b711-4aaddad66563)



**Welcome to the Land Use and Land Cover Dehradun project repository!** This project focuses on **analyzing and visualizing geospatial data** related to land use and land cover changes in Dehradun between the years 2015 and 2022. The goal of this project is to provide insights into the transformation of land areas and their cover types over this period.

## Table of Contents

- [Project Overview](#-project-overview)
- [Installation](#-installation)
- [Code Structure](#-code-structure)
  - [1. Importing and Data Preparation](#1-importing-and-data-preparation)
  - [2. Visualizing Satellite Imagery Bands](#2-visualizing-satellite-imagery-bands)
  - [3. Dimensionality Reduction using PCA](#3-dimensionality-reduction-using-pca)
  - [4. K-Means Clustering](#4-k-means-clustering)
  - [5. Visualizing Clusters](#5-visualizing-clusters)
- [Usage](#-usage)
- [Results and Insights](#-results-and-insights)
- [Acknowledgments](#-acknowledgments)

## 🌍 Project Overview

This repository contains Python code snippets and scripts for **processing, analyzing, and visualizing geospatial data** using various libraries and tools. The code covers several aspects of the project, including:

- Importing and handling geospatial data
- Reading and visualizing Sentinel satellite imagery bands
- Performing standardization and dimensionality reduction using PCA
- Applying k-means clustering to identify land cover clusters
- Visualizing land cover clusters using image plots and interactive plots

## 🚀 Installation

To run the code in this project, follow these installation steps:

**Clone this repository** to your local machine using the following command:

   ```
   git clone https://github.com/Hritikgoswami/Land-Use-Land-Cover-Dehradun.git
   ```

## 📂 Code Structure

The project is organized into the following sections:

### 1. Importing and Data Preparation

- The code imports necessary Python libraries for geospatial data manipulation and visualization.
- It uses the `glob` module to retrieve files/pathnames that match a specified pattern.
- Sentinel satellite imagery bands are read and stored using the `rasterio` library.

### 2. Visualizing Satellite Imagery Bands

- Sentinel satellite imagery bands are visualized using various techniques.
- The `earthpy.plot` module is used for creating customized plots of bands.
- RGB composite images are generated and displayed using the `plot_rgb` function.
- Histograms for each band are plotted using the `hist` function.

### 3. Dimensionality Reduction using PCA

- Principal Component Analysis (PCA) is applied to the standardized data.
- The `StandardScaler` class is used for feature scaling.
- The `PCA` class from `sklearn.decomposition` is used to perform dimensionality reduction.

### 4. K-Means Clustering

- K-means clustering is applied to the lower-dimensional PCA data.
- The resulting cluster labels are predicted using the trained k-means model.

### 5. Visualizing Clusters

- The cluster labels are visualized using the `earthpy.plot` module.
- Cluster labels are plotted as bands to show their spatial distribution.
- An interactive plot using `plotly.express` displays the cluster labels.

## 🛠️ Usage

Each code snippet can be executed independently by running the respective Python scripts or Jupyter notebooks provided in the repository. Make sure you have the required libraries installed before running the code.

## 📊 Results and Insights
![image](https://github.com/Hritikgoswami/Land-Use-Land-Cover-Dehradun/assets/84679973/64a990a7-8d73-401b-9e04-3a3cc06bee17)

![image](https://github.com/Hritikgoswami/Land-Use-Land-Cover-Dehradun/assets/84679973/9391f726-a592-4176-8db3-8ffdbab74de4)


This project's code snippets and visualizations provide insights into the land use and land cover changes in Dehradun over the years 2015 to 2022. You can explore the visualizations and interpret the results to understand the patterns and transformations in the land cover clusters.

## 🙏 Acknowledgments

This project was developed as part of an exploration into geospatial data analysis and visualization. The code and visualizations can serve as a starting point for further research and analysis in the field of land use and land cover studies.

---

Feel free to explore the code, modify it to suit your specific needs, and contribute to the repository by creating pull requests. If you have any questions or suggestions, please open an issue. **Happy coding!**
