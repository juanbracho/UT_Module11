# Module 11: Data Collection

## Overview
In this module, we focus on collecting data from websites via web scraping techniques. You'll gain an understanding of how websites are structured using HTML and CSS and learn to use Python libraries such as Beautiful Soup and Splinter to extract information from web pages. You'll also delve into advanced scraping techniques to navigate and scrape data from dynamic and multi-page websites.

---

## Lessons

### 11.1 Scraping HTML
- **Overview**: Learn the basics of HTML structure and CSS styling to understand the framework of web pages. Apply this knowledge to perform web scraping using Beautiful Soup.
- **What You'll Learn**:
  - Identify HTML components in a website.
  - Create a basic HTML document.
  - Scrape data from a website using Beautiful Soup.
  - Style HTML elements using CSS.

---

### 11.2 Web Scraping with CSS Selectors
- **Overview**: Build on your foundational skills to perform more advanced web scraping using CSS selectors. Learn to identify and extract targeted elements by leveraging Chrome DevTools.
- **What You'll Learn**:
  - Use CSS selectors to scrape targeted elements.
  - Use Chrome DevTools to identify elements and their CSS selectors.

---

### 11.3 Automated Browsing
- **Overview**: Dive into automated browsing with Splinter, combining it with Beautiful Soup for advanced scraping. Understand the ethics and legal considerations of web scraping as you automate data collection from live websites.
- **What You'll Learn**:
  - Use Splinter to perform automated browser actions.
  - Automate web scraping using Splinter and Beautiful Soup.
  - Organize scraped information into Python data structures.

---

## Assignments

### Part 1: Scrape Titles and Preview Text from Mars News
- **Task**: Scrape news titles and preview text from the [Mars news site](https://mars.nasa.gov).
- **Steps**:
  1. Use Splinter for automated browsing to visit the website.
  2. Create a Beautiful Soup object and identify target elements for scraping.
  3. Extract titles and preview text into a Python dictionary.
  4. Store the data in a list and optionally export it as a JSON file.

---

### Part 2: Scrape and Analyze Mars Weather Data
- **Task**: Scrape Mars weather data and perform analysis using Pandas and Matplotlib.
- **Steps**:
  1. Use Beautiful Soup to scrape data from the Mars Temperature Data site.
  2. Assemble the data into a Pandas DataFrame.
  3. Analyze the data to:
     - Identify the number of Martian months.
     - Find the coldest and warmest months on Mars and plot the results.
     - Determine the months with the lowest and highest atmospheric pressure.
     - Calculate the approximate length of a Martian year.
  4. Export the DataFrame to a CSV file.

---

## Key Skills Gained
- Scraping data from static and dynamic web pages.
- Using Beautiful Soup and CSS selectors to extract specific elements.
- Automating browser actions with Splinter.
- Structuring and analyzing scraped data in Python.
- Creating visualizations from extracted data.

