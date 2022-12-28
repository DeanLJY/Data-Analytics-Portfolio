# Data Science Job Market Analysis

This project aims to provide a comprehensive and up-to-date understanding of the current job market for data science roles. It achieves this by extracting and analyzing job listing data from three major job listing platforms: Monster, SimplyHired, and Indeed.

## Project Overview

This project is developed and maintained by Dean Leung and was last updated in December 2022. The primary goal of the project is to identify the key skills and technologies that are currently in high demand for data science roles.

The project utilizes Python along with several libraries, including:

- `pandas` for data manipulation,
- `matplotlib` for data visualization,
- `requests` and `beautifulsoup` for web scraping,
- `plotly` for creating interactive visualizations.

## Project Description

The data science job market is a dynamic ecosystem where new technologies emerge, old ones become obsolete, and the skills employers seek can change rapidly. To stay competitive in this evolving landscape, it's critical to keep up with these trends and understand what skills are in demand.

This project uses web scraping to gather job listing data for the role of "Data Scientist" from three major job platforms: Monster, SimplyHired, and Indeed. We have compiled a list of search terms representing different skills or technologies relevant to data science, such as Python, SQL, R, Spark, Hadoop, and more. We then scrape data for each of these terms.

Once the data is collected, it is cleaned and transformed into a pandas DataFrame to facilitate analysis and visualization. The frequency of each skill or technology in the job listings gives us an idea of what employers are currently looking for.

Finally, the findings are visualized using bar charts to understand the relative demand for different skills and technologies.

## Project Structure

The project is structured as follows:

1. **Import necessary libraries**: We begin by importing all the necessary libraries.
2. **Data Collection**: We define our list of search terms and start scraping data from the job listing platforms.
3. **Data Cleaning & Transformation**: We clean and transform the scraped data, preparing it for analysis.
4. **Data Analysis**: We analyze the data, aiming to answer our research questions.
5. **Data Visualization**: We create visualizations to better understand our findings and communicate them effectively.
6. **Conclusion**: We conclude with a summary of our findings.

## Getting Started

To get started with the project, clone the repository and install the necessary Python libraries. The Jupyter notebook is well-documented and provides a step-by-step guide to the process.

## Conclusion

By the end of this project, you will have a good understanding of the current job market for data science roles and know which skills and technologies are in demand. This knowledge will help you stay competitive and relevant in the rapidly evolving data science job market.
