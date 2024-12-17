
# Crime Data Analysis Dashboard (2018)

This project utilizes R and Shiny to create an interactive dashboard for analyzing 2018 crime data in the United States. The dashboard is built using `flexdashboard` and provides a variety of visualizations and insights into crime trends and patterns.

## Features

- **Heatmap Visualization**: Displays correlations between various crime-related variables.
- **Interactive Charts**: Includes dynamic plots created with libraries such as `plotly`, `highcharter`, and `ggvis`.
- **Data Tables**: Interactive data tables for exploration, powered by `DT`.
- **Statistical Analysis**: Built-in functionality for regression analysis and hypothesis testing.
- **Custom Themes**: Visualization styles using `viridis` and `RColorBrewer`.

## Installation

#1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <Group_14> 
   ```

2. Ensure the required R packages are installed. You can use the following command

```install.packages(c(
  "flexdashboard", "tidyverse", "ggplot2", "dplyr", "DT", "knitr",
  "rpivotTable", "plotly", "openintro", "highcharter", "ggvis",
  "shiny", "viridis", "RColorBrewer", "corrplot", "ggpubr", 
  "lmtest", "tidyr", "maps", "heatmaply"
))
```

##Usage

1. Open the R Markdown file in RStudio: project_with_shiny.Rmd.
2. Run the file to generate the Shiny dashboard
`rmarkdown::run("project_with_shiny.Rmd")`

##Files and Data
processed_crimedata.csv: Input data file containing crime statistics for the United States in 2018. Ensure this file is located in the same directory as the R Markdown file.
R Markdown File: Contains the code and structure for generating the dashboard.

##Libraries Used
This project leverages the following R libraries:
Visualization: ggplot2, plotly, highcharter, ggvis, viridis, heatmaply
Data Wrangling: tidyverse, dplyr, tidyr
Interactive Features: shiny, DT, rpivotTable
Statistical Analysis: ggpubr, lmtest, corrplot
Mapping: maps
Dashboard Framework: flexdashboard

##Contribution
Feel free to contribute to this project by submitting pull requests or opening issues for bugs and feature requests.
