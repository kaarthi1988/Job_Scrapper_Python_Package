# Job_Scrapper_Python_Package
Job Scraper is a Python application that automates the extraction of job postings from website. Users can input a search keyword and specify the number of pages to scrape (up to 16). The tool collects essential details like job titles, companies, and descriptions, saving the results in a CSV file for easy access and analysis.

# Job Scraper

## Description
The Job Scraper is a Python package designed to scrape job postings from Indeed based on user-defined keywords and parameters. This application utilizes web scraping techniques to gather relevant job information, such as job title, company, location, salary, and job description. The scraped data is saved in a CSV file for further analysis.

## Features
- User-friendly interface for inputting search parameters.
- Scrapes job postings from Indeed based on specified keywords.
- Saves scraped job data to a CSV file.

## Requirements
- Python 3.x
- pandas
- beautifulsoup4
- hrequests
- numpy
- tkinter

## Installation

### 1. Download the Package

Download the package from the repository. The package should be in `.tar.gz` or `.zip` format.

### 2. Unzip the File

- **For `.zip` files**: Right-click the zip file and select "Extract All" or use a tool like 7-Zip or WinRAR.
- **For `.tar.gz` files**: Use a tool like 7-Zip or WinRAR to extract it, or use command line tools on Linux or macOS:

### 3. Navigate to the Extracted Directory

### 4. Install the Package

pip install job_scraper-0.1-py3-none-any.whl
 or 
pip install job_scraper-0.1.tar.gz

### 5.Verifying the Installation

pip show job_scraper

### 6.Usage

from Job_scrapper import start_scraping

start_scraping()

It will ask two inputs 
- 1.Search Key words - Max 25 char

  
  ![image](https://github.com/user-attachments/assets/24082313-faec-46ec-a766-6042c18d5eb2)

- 2.Number of pages to scrap - Max 10 Pages

  ![image](https://github.com/user-attachments/assets/d58e93af-d19b-46b7-82d9-a518cee75ae6)




then you will get


  ![image](https://github.com/user-attachments/assets/d00a2d3a-3194-4f06-a0e0-f4e21dd52104)


### Notes
This package is not intended for commercial purposes and is meant strictly for personal use only.
The author does not assume any liability for any consequences that may result from the use of this package  


Please feel free to make any adjustments to the author section or other details as needed. This format includes all the required details, ensuring everything is neatly organized within the `README.md` file.

