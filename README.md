# LinkedIn Job Scraper
This repository contains a Jupyter notebook for scraping job postings from LinkedIn for the position of "Frontend Developer" in the United States. The script collects various details about each job posting and saves the data into a CSV file.

## Features
- Scrapes job postings from LinkedIn based on specified job title and location.
- Extracts job details such as job title, company name, posting time, and number of applicants.
- Handles rate limiting by LinkedIn to avoid being blocked.
- Saves the scraped data into a CSV file for further analysis.

## Installation
1. Clone the repository:

      ```
      git clone https://github.com/yourusername/linkedin-job-scraper.git
      cd linkedin-job-scraper
      
      ```
      
2. Install the required dependencies:

    You need to have Python installed on your system. You can install the required packages using pip:

   ```
   pip install requests beautifulsoup4 pandas
   ```
3. Jupyter Notebook:

   Ensure you have Jupyter Notebook installed. If not, you can install it using:
   
   ```
   pip install notebook
   ```
   

# Usage
1. Run Jupyter Notebook:
      ```
      jupyter notebook
      ```

2. Open the notebook:

   Open the `openings-scraper.ipynb` notebook from the Jupyter interface.



3. Execute the notebook cells:

   Run each cell in the notebook sequentially to scrape the job postings and save the data to a CSV file.


# Output
The notebook will save the scraped job data into a CSV file named `United_States_Frontend_Developer.csv` in the same directory.

# Notes
-  The script is designed to handle rate limiting by LinkedIn by checking the response status and waiting if necessary.
-  Ensure that you comply with LinkedIn's terms of service when using this script for web scraping.


# Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request, have a crack at it!.

# License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

