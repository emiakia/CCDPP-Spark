# Speed Up Recommender Systems Based on CCD Matrix Factorization

## Overview

This project demonstrates a method for accelerating recommender systems using CCD matrix factorization by combining shared memory and distributed memory parallel computing. The approach leverages Spark and Pandas to efficiently handle and process large datasets. The key innovation of this project is the treatment of datasets as tables, which enhances both performance and readability, particularly for those familiar with SQL-like thinking.

## Technologies Used

- **Python**: Programming language used for implementing the algorithms and managing the data processing pipeline.
- **Apache Spark**: Distributed computing framework for handling large-scale data processing.
- **Pandas**: Library for data manipulation and analysis in Python.
- **Google Colab**: Provides an environment to run the notebook and manage datasets.
- **GPU**: Utilized to accelerate computations and enhance performance.

## Features

- **Matrix Factorization**: Implements CCD matrix factorization to improve the performance of recommender systems.
- **Data Handling**: Efficiently manages large datasets using Spark DataFrames and SQL queries.
- **Optimization**: Employs a method to treat datasets as tables, which simplifies the code and makes it more efficient.

## Setup

1. **Environment Setup**:
   - Ensure you have access to Google Colab or a similar environment with Python, Spark, and GPU support.
   - Install necessary libraries and set up the environment with Spark and Java.
