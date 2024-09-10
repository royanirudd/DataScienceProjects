# Data Science Projects

This repository contains various data science projects I've worked on. Each project is briefly described in its own collapsible section below.

<details>
<summary><strong>Queensland Health Facilities Data Scraper</strong></summary>

### Overview
This project involves scraping data about healthcare facilities from the Queensland Health website. It collects information such as clinic names, addresses, and phone numbers.

### Technologies Used
- Language: Python
- Environment: Jupyter Notebook

### Libraries
- BeautifulSoup: For parsing HTML content
- pandas: For data manipulation and storage
- requests: For making HTTP requests
- time & random: For implementing delays between requests
- re: For pattern matching using regular expressions
- fake_useragent: For generating random user agent strings

### Process
1. Initial Google search for Queensland Health website
2. Web scraping of clinic names and links
3. Detailed scraping of individual clinic pages
4. Google search for missing information

### Challenges
- Web Scraping Complexity: Parsing varied HTML structures and handling edge cases
- Missing Data: Implementing additional data sourcing methods for incomplete information
- Google Search Limitations:
  - Implementing rate limiting to avoid being blocked
  - Ensuring accuracy of information from search results
  - Complex parsing of unstructured web content for structured data extraction

### Notes
This project is for educational purposes. Always ensure compliance with websites' terms of service and ethical web scraping practices when collecting data.

</details>
