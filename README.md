# Big Data Processing with Spark

## NUSC Summer School 2025

![NUSC Summer School Banner](https://via.placeholder.com/800x200)

Welcome to the Big Data Processing with Spark workshop for the NUSC Summer School 2025! This repository contains all the materials needed to learn how to process and analyze large datasets using Apache Spark and related technologies.

## Workshop Overview

This workshop provides a comprehensive introduction to big data processing using Apache Spark. Participants will learn how to use Spark for distributed data processing, analytics, and machine learning at scale.

### Learning Objectives

By the end of this workshop, participants will be able to:

- Understand distributed computing concepts and the Spark architecture
- Process large datasets using Spark's RDDs and DataFrames
- Perform data transformation and aggregation at scale
- Implement machine learning pipelines with Spark ML
- Process streaming data with Spark Streaming
- Optimize Spark jobs for better performance
- Deploy Spark applications in various environments

## Prerequisites

- Intermediate Python programming skills
- Basic knowledge of SQL
- Familiarity with data processing concepts
- A laptop with at least 8GB RAM and 20GB free disk space

## Workshop Schedule

### Day 1: Spark Fundamentals
- 09:00 - 10:30: Introduction to Big Data and Spark Architecture
- 10:45 - 12:15: Working with RDDs and Basic Transformations
- 13:30 - 15:00: Spark DataFrames and SQL
- 15:15 - 16:45: Data Processing and Aggregation

### Day 2: Advanced Spark and Machine Learning
- 09:00 - 10:30: Advanced DataFrame Operations and Optimization
- 10:45 - 12:15: Machine Learning with Spark ML
- 13:30 - 15:00: Building ML Pipelines
- 15:15 - 16:45: Model Evaluation and Hyperparameter Tuning

### Day 3: Spark Streaming and Deployment
- 09:00 - 10:30: Introduction to Spark Streaming
- 10:45 - 12:15: Stream Processing and Windowing Operations
- 13:30 - 15:00: Deploying Spark Applications
- 15:15 - 16:45: Final Project and Group Presentations

## Setup Instructions

### Option 1: Using Docker (Recommended)

```bash
# Clone this repository
git clone https://github.com/nusc-summer-school/big-data-spark.git
cd big-data-spark

# Start Spark environment using Docker
docker-compose up -d

# Access Jupyter notebooks
# Visit http://localhost:8888 in your browser
```

### Option 2: Using a Cloud Environment

You can use the following cloud environments with Spark pre-installed:

1. [Databricks Community Edition](https://community.cloud.databricks.com/)
2. [Google Colab with PySpark](https://colab.research.google.com/)
3. [AWS EMR](https://aws.amazon.com/emr/)

### Option 3: Local Installation

```bash
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
```

## Repository Structure

```
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
```

## Datasets

This workshop uses the following datasets:

1. **NYC Taxi Data**: Large dataset of taxi trips for batch processing
2. **E-commerce Transactions**: Customer transaction data for analytics
3. **Sensor Readings**: IoT sensor data for stream processing
4. **Social Media Data**: Text data for sentiment analysis and NLP

Sample versions of these datasets are included in the `/data` directory. Full datasets will be accessed through cloud storage during the workshop.

## Resources

### Recommended Reading

- Chambers, B., & Zaharia, M. (2018). Spark: The Definitive Guide. O'Reilly Media.
- Karau, H., & Warren, R. (2017). High Performance Spark. O'Reilly Media.
- Damji, J. et al. (2020). Learning Spark: Lightning-Fast Data Analytics. O'Reilly Media.

### Online Resources

- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [Databricks Academy](https://academy.databricks.com/)
- [Spark by Examples](https://sparkbyexamples.com/)

## Instructors

- **Dr. Alex Thompson** - Big Data Engineer, DataTech Solutions
  - [GitHub](https://github.com/) | [LinkedIn](https://linkedin.com/)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

We thank all contributors and the NUSC Summer School organizing committee for making this workshop possible.

---

For questions or additional information, don't hesitate to get in touch with us at info@nuscsummerschool.edu
