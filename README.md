# Web Scraping and Exploratory Data Analysis of AmbitionBox (DA, DS, DE Roles)

## Project Overview

This project focuses on web scraping and exploratory data analysis of job listings from AmbitionBox for Data Analyst (DA), Data Scientist (DS), and Data Engineer (DE) roles.

The objective is to extract real-world job market data and analyze hiring trends, salary distributions, company activity, and location-based opportunities to help job seekers and analysts understand the data job ecosystem.

AmbitionBox is a career advisory platform providing company reviews, salary insights, and hiring information across industries.

---

## Business Problem

Organizations and job seekers want to understand:

- Which data roles are most in demand
- Salary trends across roles and companies
- Hiring activity across locations
- Company-level hiring intensity
- Market trends in data-related careers

This project helps uncover these insights using real-world scraped data.

---

## Project Workflow

### 1. Web Scraping

- Extracted job-related data from AmbitionBox website
- Used HTTP requests and HTML parsing
- Identified relevant HTML tags using browser inspection
- Extracted structured job information

Libraries used:
- requests
- BeautifulSoup
- regex

Extracted features include:

- Company Name
- Rating
- Job Role
- Company Type
- Location
- Benefits Count
- Jobs Count
- Interview Count
- Salary
- Reviews Count

---

### 2. Data Cleaning and Preparation

- Combined multiple role-specific datasets into one dataset
- Removed duplicates and handled missing values
- Cleaned text using regular expressions
- Converted columns into correct data types

Final Dataset:

- 419 rows
- 10 columns

Numerical columns:
- Rating
- Benefits
- Jobs Count
- Interviews Count
- Salary
- Reviews Count

Categorical columns:
- Company Name
- Designation
- Type
- Location

---

### 3. Exploratory Data Analysis (EDA)

Performed analysis using:

- Pandas
- NumPy
- Matplotlib
- Seaborn

Analyzed:

- Salary distribution
- Job distribution
- Benefits distribution
- Hiring patterns
- Location trends
- Company hiring intensity
- Correlation between variables

---

## Key Insights

### Role Insights

- Data Scientist roles receive highest salaries
- Data Engineer and Data Analyst roles show strong hiring demand
- High salary roles are mostly from large tech companies

### Company Insights

Top hiring companies include:

- Amazon
- Google
- Flipkart
- Oracle
- Goldman Sachs
- Deutsche Bank

Large companies dominate hiring, salary, and benefits distribution.

---

### Location Insights

- Bangalore is the primary hiring hub (55.5% of openings)
- Hyderabad is second major hub
- Gurgaon and Pune show moderate activity
- Other cities show significantly lower hiring

---

### Salary Insights

- Salary distribution is right-skewed
- High salary outliers exist, mostly from large companies
- Data Scientist roles dominate high salary range

---

### Hiring Activity Insights

- High hiring activity companies conduct more interviews
- Benefits, salary, interviews, and reviews show strong correlation
- Company rating has weak correlation with salary and hiring

---

### Industry Insights

Dominant industries:

- IT Services & Consulting
- Internet Companies
- Software Product Companies
- Financial Services
- Analytics & KPO

---

## Tools and Technologies Used

Programming Language:
- Python

Libraries:
- requests
- BeautifulSoup
- regex
- pandas
- numpy
- matplotlib
- seaborn

Environment:
- Jupyter Notebook

---

## Project Structure

Scraping.ipynb → Web scraping script
Ambition_Box_EDA.ipynb → Exploratory data analysis
ambitionbox_dataset_final.csv → Final cleaned dataset
README.md → Project documentation


---

## Skills Demonstrated

- Web Scraping
- HTML Parsing
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Python Programming
- Real-world Dataset Handling
- Insight Generation

---

## Business Value

This project helps:

- Understand job market trends
- Identify high-paying roles
- Discover major hiring companies
- Analyze hiring locations
- Understand salary and hiring patterns

Useful for:

- Job seekers
- Data analysts
- Recruiters
- Career planners

---

## Presentation Preview


## Conclusion

- Large companies dominate hiring and salary distribution
- Data Scientist roles receive highest salaries
- Bangalore is the primary hiring hub
- Hiring activity and salary depend more on company scale than ratings
- IT and Software companies lead the data job market

---

## Author

Ram Kumar Cheekati  
Aspiring Data Analyst
