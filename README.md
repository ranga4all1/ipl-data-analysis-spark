# ipl-data-analysis-spark
Indian Premier League (IPL) data analysis using Apache Spark

Being a cricket Fan let's try to analyse this IPL dataset with a fun factor.
Hope you like it!!!

## Dataset
https://data.world/raghu543/ipl-data-till-2017

**DESCRIPTION:**
Ball By Ball Data of all the IPL seasons (637 matches including 2017)

**SUMMARY:**
This data set has the ball by ball data of all the Indian Premier League (IPL) matches till 2017 season.

**Source:** http://cricsheet.org/ (data is available on this website in the YAML format. This is converted to CSV format by using R Script ,SQL,SSIS.

**Note**:
- Same dataset is available in one AWS Public bucket:
```
s3://ipl-data-analysis-project/
```

## Tech stack
1. Python
2. AWS S3 - Cloud storage bucket
3. Databricks community edition (free) - Apache Spark single mode cluster
4. Jupyter Notebook

## Steps to run the code
1. Clone the repository
2. Create compute and notbook in Databricks to run Spark code/notebook
    - Register for Databricks community edition (free)
    - Create compute
        - Click "Compute" --> Create compute
        - Name: ipl_compute_cluster
        - Keep all other parameters default and click "Create compute"
        - This should create a single node cluster
        ```
        0 Workers:0 GB Memory, 0 Cores, 0 DBU
        Driver: 15.3 GB Memory, 2 Cores, 1 DBU
        ```
3. Run the code
    - In Databricks UI, Create or import the notebook "ipl_data_analysis_spark.ipynb"
    - Click "Run All"

