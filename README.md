# **Gene Expression Analysis Dashboard** 

## **Introduction** 

This repository features an interactive data visualization dashboard designed for gene expression analysis. It simplifies the exploration of complex genomic datasets, enabling users to visualize patterns, compare gene expression across conditions, and integrate multiple data sources. This tool empowers researchers to derive actionable insights and make informed decisions, accelerating discoveries in genomics.

## **Pre-requisites**

- Python libraries ( pandas, numpy, scipy, seaborn, matplotlib, panel, bokeh, holoviews, holoviz)
- Normalized gene expression counts data and metadata

## **Contents**
In this repository you will find three folders:

- Code : Code for creating dashboard
- Data : Sample Gene expression normalized data
- Figures : A snippet of the dashboard

![Dashboard](https://github.com/pooja185/Panel_data_visualization_app/blob/main/Figures/Panel_app.png)

## **Functional Features**
- Dashboard allows user to input two types of datasets:
  1. Metadata - File containing all information about the sample
  2. Normalized counts dataset - File containing all genes and their counts for every sample

- On the left side: Users can select which metadata/gene through "Select metadata" and "Select gene" Dropdown widgets for BoxPlot and Violin data and can select 2 genes they want to visualize for Scatter Plot. 

- Panel and holoviews library allows user to have interactive plots and users would be able to see what each scatter point in the plot denotes.  

- The dashboard is divided in 4 parts :

  - The first quadrant shows the uploaded metadata file. 

  - Second Quadrant - shows Scatter Plot for 2 different genes present in the gene-expression dataset which can be further differentiated by the chosen metadata

  - Third and Fourth Quadrant - Box plot and Violin plot based on the selected widgets and groupby functionality.



