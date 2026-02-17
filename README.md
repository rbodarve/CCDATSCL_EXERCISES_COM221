# Data Science Course Exercises - COM221

A collection of hands-on exercises for learning data science fundamentals through practical analysis of real-world datasets.

## Table of Contents

- [About](#about)
- [Exercises](#exercises)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## About

This repository contains a series of Jupyter Notebook exercises designed for the COM221 Data Science course (CCDATSCL). Each exercise focuses on different aspects of data science including data cleaning, exploratory data analysis, visualization, and statistical analysis using real-world datasets.

The exercises progressively build skills in:
- Data manipulation and cleaning with Pandas
- Statistical analysis and hypothesis testing
- Data visualization with Matplotlib and Seaborn
- Exploratory Data Analysis (EDA) techniques
- Working with various data formats (CSV, etc.)

## Exercises

### Exercise 1: Airbnb NYC 2019 Analysis
Explore and analyze Airbnb listings in New York City. This exercise covers data cleaning, neighborhood price analysis, and understanding the rental market dynamics.

**Dataset**: AB_NYC_2019.csv  
**Notebook**: DS_Exercise1.ipynb

### Exercise 3: Pokemon Dataset Analysis
Analyze characteristics and statistics of Pokemon across different generations and types.

**Dataset**: Pokemon.csv  
**Notebook**: Exercise3.ipynb

### Exercise 4: COVID-19 Data Analysis
Study COVID-19 pandemic data with comprehensive cleaning and exploratory analysis.

**Dataset**: covid_19_clean_complete.csv  
**Notebook**: Exercise4.ipynb

### Exercise 5: Advanced Analysis
Additional data science exercise building on previous concepts.

**Notebook**: Exercise_5.ipynb

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Conda (recommended) or pip for package management

### Installation

1. Clone the repository
```bash
git clone https://github.com/rbodarve/CCDATSCL_EXERCISES_COM221.git
cd CCDATSCL_EXERCISES_COM221
```

2. Create and activate the conda environment (recommended)
```bash
cd Exercise_1
conda env create -f environment.yml
conda activate datasci
```

Alternatively, install dependencies using pip:
```bash
pip install -r Exercise_1/requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

## Usage

Navigate to the desired exercise folder and open the corresponding Jupyter Notebook file (.ipynb). Each notebook contains:
- Dataset description and source information
- Step-by-step instructions
- Code cells for analysis
- Markdown cells with explanations
- Visualization outputs

Run the cells sequentially to reproduce the analysis or modify them to explore the data further.

## Technologies

This project uses the following Python libraries:
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter** - Interactive computing environment

## Project Structure

```
CCDATSCL_EXERCISES_COM221/
├── Exercise_1/
│   ├── AB_NYC_2019.csv
│   ├── DS_Exercise1.ipynb
│   ├── average_price_per_neighborhood.csv
│   ├── cleaned_airbnb.csv
│   ├── environment.yml
│   └── requirements.txt
├── Exercise_3/
│   ├── Exercise3.ipynb
│   └── Pokemon.csv
├── Exercise_4/
│   ├── Exercise4.ipynb
│   └── covid_19_clean_complete.csv
├── Exercise_5/
│   └── Exercise_5.ipynb
└── README.md
```

## Contributing

This is an educational repository for course exercises. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is created for educational purposes as part of the COM221 Data Science course.

## Acknowledgments

- README template inspired by [awesome-readme](https://github.com/matiassingers/awesome-readme) by [Matias Singers](https://github.com/matiassingers)
- Datasets used are publicly available for educational purposes
- Course materials from COM221 Data Science curriculum
