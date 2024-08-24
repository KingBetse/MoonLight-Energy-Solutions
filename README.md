# MoonLight Energy Solutions

## Project Overview
This project aims to analyze a dataset containing solar energy-related data, such as Global Horizontal Irradiance (GHI), Direct Normal Irradiance (DNI), Diffuse Horizontal Irradiance (DHI), and module temperatures (TModA and TModB). The goal is to provide insights into the relationships between these variables through statistical analysis and visualization.

## Dataset
The dataset used in this project includes data from three different locations: Benin, Sierra Leone, and Togo. The dataset can be found in the `./src/` directory of the project, with the following file names:
- `benin-malanville.csv`
- `sierraleone-bumbuna.csv`
- `togo-dapaong_qc.csv`

## Jupyter Notebook Analysis
To explore and analyze the dataset, the project leverages the Jupyter Notebook environment. Jupyter Notebook allows for interactive data exploration, visualization, and reporting, making it an ideal tool for this type of project.

### Usage
1. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Launch the Jupyter Notebook server:
   ```
   jupyter notebook
   ```
3. Open the `data_analysis.ipynb` notebook and run the cells to explore the dataset.

### Data Exploration and Visualization
The Jupyter Notebook provides a comprehensive approach to analyzing the solar energy dataset. It includes the following key steps:

1. **Data Loading and Preprocessing**: The dataset is loaded into a Pandas DataFrame, and any necessary data cleaning and preprocessing steps are performed.

2. **Exploratory Data Analysis**: The notebook includes various visualizations, such as scatter plots and histograms, to gain a better understanding of the dataset's characteristics and the relationships between the variables.

3. **Correlation Analysis**: A correlation matrix is computed to identify the strength and direction of the relationships between the different features in the dataset. This information is then visualized using a correlation heatmap.

4. **Statistical Modeling**: Depending on the specific goals of the analysis, the notebook may include the development of statistical models, such as regression analyses, to further explore the dataset and uncover insights.

By leveraging the interactive and powerful features of Jupyter Notebook, the MoonLight Energy Solutions project provides a comprehensive and engaging way to analyze the solar energy dataset, enabling researchers and stakeholders to gain valuable insights and make informed decisions.

## Conclusion
The MoonLight Energy Solutions project demonstrates the effectiveness of using Jupyter Notebook for data analysis in the context of solar energy research. The interactive nature of the notebook, combined with its ability to integrate code, visualizations, and narrative, makes it an invaluable tool for exploring and understanding the dataset, ultimately supporting the development of more efficient and effective solar energy solutions.
 
