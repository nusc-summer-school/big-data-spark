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
