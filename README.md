# Explorative Data Analysis: Indian Start-up Funding (2018-2021)

## Project Overview

Welcome to the Exploratory Data Analysis project focused on **Indian Start-up Funding from 2018 to 2021**. This project is part of the **Data Analytics Professional & AI Program**. As data continues to grow exponentially, this analysis will help uncover insights into funding trends, investor behavior, and the start-up ecosystem in India.

Your team is considering venturing into the Indian start-up ecosystem, and as the data expert, your task is to analyze the funding data and recommend the best course of action based on your findings.

## Table of Contents

- [Project Overview](#project-overview)
- [Scenario](#scenario)
- [Data Sources](#data-sources)
- [Installation and Setup](#installation-and-setup)
- [Skills Developed](#skills-developed)
- [Project Structure](#project-structure)
- [Analysis and Visualizations](#analysis-and-visualizations)
- [Key Findings](#key-findings)
- [Contributing](#contributing)
- [License](#license)

## Scenario

Your goal is to investigate funding received by Indian start-ups between 2018 and 2021. The data includes start-up details, funding amounts, and investor information. You will utilize this data to provide recommendations for entering the Indian start-up ecosystem.

### Key Questions

1. What are the funding trends over the years?
2. Which sectors received the most funding?
3. Who are the key investors in the Indian start-up space?
4. What are the differences in funding by region?
5. What strategic recommendations can be made based on the analysis?

## Data Sources

This project uses three data sources, covering the years 2018 to 2021:

### 1. 2020 & 2021 Data (SQL Database)

The data for 2020 and 2021 is stored in a **SQL Server** database. 

### 2. 2019 Data (OneDrive)

The data for 2019 is stored in a CSV file:


### 3. 2018 Data (GitHub)

The 2018 dataset is available in a github repository:


## Installation and Setup

### Prerequisites

- Python (>= 3.x)
- Libraries: pandas, numpy, matplotlib, seaborn, pyodbc, SQLAlchemy
- Jupyter Notebook or any IDE for `.ipynb` files

### Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/repository-name.git
    cd repository-name
    ```

2. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Connect to the database (2020 & 2021 data):**
   - Use `pyodbc` or `SQLAlchemy` to connect to the SQL Server database.

4. **Access the 2019 and 2018 datasets:**
   - `startup_funding2019.csv` from OneDrive
   - `startup_funding2018.csv` from this repository

## Skills Developed

By completing this project, I have built the following skills:

- Asking **SMART** and effective questions
- Structuring and cleaning data
- Summarizing and analyzing data using Python
- Connecting business objectives to data analysis
- Visualizing data with Python
- Telling a compelling data-driven story
- Presenting findings and answering data-related questions

## Project Structure


- **data/**: Contains the datasets for analysis.
- **notebooks/**: Contains Jupyter notebooks with the EDA process.
- **images/**: Visualization outputs (e.g., trends, distributions).
- **requirements.txt**: Python dependencies for the project.

## Analysis and Visualizations

Key analyses performed in the EDA include:

- **Funding Trends**: Year-on-year trends of start-up funding
- **Sector Analysis**: Funding distribution across different sectors
- **Investor Insights**: Identifying key investors
- **Regional Breakdown**: Geographical distribution of start-ups and funding

Visualizations include:

- Line plots for **funding trends**
- Bar charts for **sector funding distribution**
- Heatmaps for **correlation analysis**

## Key Findings

1. **Funding Growth:** The Indian start-up ecosystem saw significant growth in funding from 2018 to 2021.
2. **Sector Leaders:** Technology and e-commerce sectors attracted the most investment.
3. **Top Investors:** [Investor Name] and [Investor Name] were key players in funding Indian start-ups.
4. **Geographical Focus:** Major funding hubs were concentrated in cities like Bangalore, Mumbai, and Delhi.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests. 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
