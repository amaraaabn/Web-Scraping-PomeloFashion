# Pomelo Fashion Data Scraping Portfolio

Welcome to my data scraping portfolio on GitHub! As a new data analyst in the field, I am excited to showcase my skills in web scraping by extracting product information from the Pomelo Fashion e-commerce website.

## Important Note

If you encounter difficulties opening or previewing the files directly from GitHub, please use the following link to access the files through Google Colab:
[Open in Google Colab](https://colab.research.google.com/drive/1wJ8QgicQPWvwcmritdM6FCyhOVyoKvvb#scrollTo=ao0fCqW35tA1)

## Project Overview
In this repository, I aim to retrieve essential product information from the Pomelo Fashion website using product ID data. The main information I want to obtain includes:

1. Product Name
2. Image Link
3. Fabric Composition

To achieve this, I have divided the process into three main stages:

## 1. Importing and Preparing Data
In this stage, I import the necessary data and prepare a dataframe to store the retrieved information later. This step involves setting up the environment and organizing the data for efficient processing.

## 2. Finding HTML Patterns
To extract the designated information, I analyze the HTML structure of the Pomelo Fashion website to identify patterns. This involves examining the HTML code to locate elements that contain the desired product information.

## 3. Web Scraping and Iteration
Using the identified HTML patterns, I perform web scraping to extract the product information. I loop through each product ID in the dataset and iterate through all possible countries and language options on the website. If a product is unavailable in one country, I check if it is available in another country. If all country lists are unavailable, it indicates that the product is truly unavailable on the website.

## Challenges Faced
During the process, I encountered challenges such as BeautifulSoup not being able to retrieve the complete HTML code. Initially, I was confused because the required data was not present in the HTML code that was readable. However, I found an alternative approach by utilizing string find elements in Python. This allowed me to successfully extract the required data and overcome the challenge.

##Conclusion
Through this project, I have demonstrated my problem-solving skills and determination to overcome challenges in data analysis and web scraping tasks. I am proud to have successfully extracted the product information needed from the Pomelo Fashion website and look forward to continuing to build my portfolio with more data analysis projects.

# Thank you for visiting my portfolio!
Come along and join me in this exciting journey of growth and discovery! Together, we'll make progress, one data point at a time🌈💻
