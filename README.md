# Data Analyst Job Market Analysis
📊 [Streamlit Dashbaord](https://hello-app-ookc5qlq1o.streamlit.app/)


## Project Overview

This project aims to analyze the nature of the Data Analyst job market in London, UK. Leveraging daily scraped data from Google Jobs search engine via a function created on Google Cloud and SerpAPI, the project seeks to provide insights into the job market by examining various parameters such as salaries, required skills, and years of experience mentioned in job postings.

## Motivation

The motivation behind this project is to gain a deeper understanding of the current trends and demands in the Data Analyst job market in London. By analyzing real-time data, the project aims to assist job seekers, recruiters, and other stakeholders with valuable insights that can guide decision-making in the job market.

## Methodology

The project employs a robust data cleaning process to ensure the accuracy of the analysis. This includes the removal of duplicate job postings identified based on various parameters such as job ID, job title, company name, and job description. The project also explores different similarity metrics and methods to determine the cutoff for similarity, including an approach based on the statistical theory of sum of normal distributions, a concept learned during the Decision and Risk module at university.

The data extraction process involves the use of regex to extract salaries and salary ranges from various fields in the job postings, followed by a process to correct common typos and standardize the format of salaries.

## Data Sources

The primary data source for this project is the Google Jobs search engine, from which job postings are scraped daily using a function created on Google Cloud and SerpAPI. The data encompasses various details from job postings, including salaries, skills required, and years of experience mentioned in the descriptions.

## Features (Work in Progress)

✅ Automated Data Cleaning: A feature to automate the data cleaning and extraction process, facilitating daily updates.
- Extract years of experience from job postings
- Live Dashboard: A planned feature that will provide a live dashboard to visualize the analysis results and insights dynamically.
