Netflix Movies & TV Shows Analysis
Project Overview

This project performs an exploratory data analysis (EDA) on Netflix’s catalog of movies and TV shows to identify trends related to content type, release year, age certification, genres, and production countries.

The analysis is done using Python with pandas and matplotlib, and the insights are presented through various visualizations.

Objectives

Compare the number of Movies vs TV Shows on Netflix

Analyze the distribution of age certifications

Study content release trends over the years

Identify the top content-producing countries

Compare yearly trends of movies and TV shows

Analyze genre distribution after cleaning multi-genre data

Tools & Technologies Used

Python

pandas

matplotlib

Jupyter Notebook

Dataset

File name: titles.csv

Dataset contains information about Netflix titles

Important columns used:

type

release_year

age_certification

production_countries

runtime

genres

Data Cleaning Steps

Removed rows with missing values in key columns

Cleaned the genres column by removing brackets and quotes

Split multiple genres into separate rows using explode

Standardized values for better analysis

Analysis & Visualizations

Movies vs TV Shows comparison using bar chart

Age certification distribution using pie chart

Content release trend over years using scatter plot

Top 10 content-producing countries using bar chart

Comparison of movies and TV shows released over years using line plots

Genre distribution using pie chart after exploding genre values

Key Insights

Movies dominate Netflix’s content library, but TV shows are growing steadily

Majority of content is targeted toward mature audiences

Content production increased significantly after 2015

A small number of countries contribute most of the content

Drama and comedy are the most common genres

Project Structure

Analysis-Of-movies-And-shows-On-NETFLIX

Untitled3.ipynb

titles.csv

moviesvsshows.png

agecertification.png

showsyear.png

top10countries.png

comparison.png

genre.png

README.md

How to Run the Project

Clone the repository

Install required libraries using pip
pip install pandas matplotlib

Open the Jupyter Notebook

Run all cells sequentially

Skills Demonstrated

Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Handling categorical and multi-valued columns

Data visualization

Analytical thinking

Author

Priyansh Gautam
Aspiring Data Analyst
Skills: Python, pandas, SQL, Power BI, Data Visualization
