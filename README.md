# SQL DATA CLEANING PROJECT

# project overview

This project focuses on cleaning and preparing a layoff dataset using sql.The goal is to transform raw data into a structured and usable format for analysis.

# Tools used

>SQL
>MYSQL
>VS CODE
>GIT & GITHUB

# Data cleaning steps

>Removing duplicate from the layoffs record

>Standardizing the data
       >Trimming the extra spaces.
       >converted the date format.

>Handling the null and blank values

>Removing any column

# Example of the query

   UPDATE layoffs_staging2
   SET `date` =STR_TO_DATE(`date`,'%m/%d/%Y');

   ALTER TABLE layoffs_staging2
   MODIFY COLUMN `date` DATE;

# files in this project

 >_data_cleaning_sql >>sql script used for cleaning the data

>README.md >> Project documentation.

# Project Purpose

>This project demonstrates sql data cleaning skills:
             >Data transformation.
             >Data standardization
             >Preparing data analysis


## Author 

Elias Muthomi.
