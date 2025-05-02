# Big Data Processing with Spark NUSC Summer School 2025


Welcome to the Big Data Processing with Spark workshop for the NUSC Summer School 2025! This repository contains all the materials needed to learn how to process and analyse large datasets using Apache Spark and related technologies.

## Workshop Overview
This workshop provides a comprehensive introduction to big data processing using Apache Spark. Participants will learn how to use Spark at scale for distributed data processing, analytics, and machine learning.

## Learning Objectives
By the end of this workshop, participants will be able to:

* Understand distributed computing concepts and the Spark architecture
* Process large datasets using Spark's RDDS and DataFrames
* Perform data transformation and aggregation at scale
* Implement machine learning pipelines with Spark ML
* Process streaming data with Spark Streaming
* Optimise Spark jobs for better performance
* Deploy Spark applications in various environments
  
## Prerequisites
* Intermediate Python programming skills
* Basic knowledge of SQL
* Familiarity with data processing concepts
* A laptop with at least 8GB RAM and 20GB of free disk space
  
## Workshop Schedule

### Day 1: Spark Fundamentals
* 09:00 - 10:30: Introduction to Big Data and Spark Architecture
* 10:45 - 12:15: Working with RDDS and Basic Transformations
* 13:30 - 15:00: Spark DataFrames and SQL
* 15:15 - 16:45: Data Processing and Aggregation
  
### Day 2: Advanced Spark and Machine Learning
* 09:00 - 10:30: Advanced DataFrame Operations and Optimisation
* 10:45 - 12:15: Machine Learning with Spark ML
* 13:30 - 15:00: Building ML Pipelines
* 15:15 - 16:45: Model Evaluation and Hyperparameter Tuning
  
### Day 3: Spark Streaming and Deployment
* 09:00 - 10:30: Introduction to Spark Streaming
* 10:45 - 12:15: Stream Processing and Windowing Operations
* 13:30 - 15:00: Deploying Spark Applications
* 15:15 - 16:45: Final Project and Group Presentations
  
### Setup Instructions

### Option 1: Using Docker (Recommended)
bash
### Clone this repository
git clone https://github.com/nusc-summer-school/big-data-spark.git
cd big-data-spark

### Start Spark environment using Docker
docker-compose up -d

### Access Jupyter notebooks
#### Visit http://localhost:8888 in your browser

## Option 2: Using a Cloud Environment
You can use the following cloud environments with Spark pre-installed:

1. Databricks Community Edition
Google Colab with PySpark
AWS EMR

<li><a href="#[workshops](https://community.cloud.databricks.com/)">Data Colan</a></li>




Option 3: Local Installation
bash
# Clone this repository
git clone https://github.com/nusc-summer-school/big-data-spark.git
cd big-data-spark

# Create and activate conda environment
conda create -n spark-workshop python=3.9
conda activate spark-workshop

# Install PySpark and other dependencies
pip install -r requirements.txt

# Start Jupyter notebook
jupyter lab
Repository Structure
big-data-spark/
├── data/                   # Sample datasets (small versions)
├── notebooks/              # Jupyter notebooks for each topic
│   ├── day1/
│   ├── day2/
│   └── day3/
├── exercises/              # Hands-on exercises
├── solutions/              # Exercise solutions
├── scripts/                # Utility scripts and helpers
├── docker/                 # Docker configuration files
├── presentations/          # Slide decks in PDF format
├── project/                # Final project template
├── requirements.txt        # Python dependencies
├── docker-compose.yml      # Docker Compose configuration
└── README.md               # Workshop information
Datasets
This workshop uses the following datasets:

NYC Taxi Data: Large dataset of taxi trips for batch processing
E-commerce Transactions: Customer transaction data for analytics
Sensor Readings: IoT sensor data for stream processing
Social Media Data: Text data for sentiment analysis and NLP
Sample versions of these datasets are included in the /data directory. Full datasets will be accessed through cloud storage during the workshop.

Resources
Recommended Reading
Chambers, B., & Zaharia, M. (2018). Spark: The Definitive Guide. O'Reilly Media.
Karau, H., & Warren, R. (2017). High Performance Spark. O'Reilly Media.
Damji, J. et al. (2020). Learning Spark: Lightning-Fast Data Analytics. O'Reilly Media.
Online Resources
Apache Spark Documentation
Databricks Academy
Spark by Examples
Instructors
Dr. Alex Thompson - Big Data Engineer, DataTech Solutions
GitHub | LinkedIn
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
We thank all contributors and the NUSC Summer School organising committee for making this workshop possible.

For questions or additional information, don't hesitate to get in touch with us at info@nuscsummerschool.edu

