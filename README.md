# Data-Science-Salary-Analysis-project

Hello, this is my Data Science Salary Analysis project. This project aims to analyze and predict salaries in the data science field using a dataset ("salaries.csv") containing information on job titles, work years, experience levels, remote ratio, salary, salary in USD, company location, and company size. Using data analysis and machine learning techniques, this project provides insights into salary trends and predictions for future salaries. 

## Objectives
My objectives for this project were: 
- To find the average salaries throughout the last couple of years
- How does working remotely affect job salary?
- Does company size affect salary?
- Does company location affect pay?
- Salaries by job titles and which job title earns the most
- Will Data Science salaries go up in the next year?

## Dataset

The dataset used in this project includes the following columns:
- **work_year**: The year the salary data was recorded.
- **experience_level**: The level of experience of the employee (e.g., Junior, Mid-level, Senior, Executive).
- **job_title**: The job title of the employee (e.g., Data Scientist, Data Engineer).
- **salary**: The salary of the employee.
- **salary_in_usd**: The salary converted to USD.
- **employee_residence**: The country of residence of the employee.
- **remote_ratio**: The ratio of remote work (0 for no remote work, 50 for hybrid, 100 for fully remote).
- **company_location**: The country where the company is located.
- **company_size**: The size of the company (Small, Medium, Large).

  ## Getting Started

To get started with this project, you will need to clone the repository and set up the necessary dependencies. Detailed instructions are provided in the "Installation" section below.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Data-Science-Salary-Analysis-Project.git
    cd Data-Science-Salary-Analysis-Project
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Results and Findings

### Average Salaries Over The Last Two Years and Prediction for Next Year
- Salaries for Data Scientists in the last two years have increased significantley
- The average salary in the year 2025 is expected to be $164,335.16 which is a 19,996.91 increase from 2024 to 2025

### Impact of Company location on Pay 
- As expected, salaries in Western countries were the biggest, the United States of America being the overall highest-paying country

###
