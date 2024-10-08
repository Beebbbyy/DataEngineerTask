# DataEngineerTask

## Overview

This project processes XML files and converts them into relational tables using PySpark. The goal is to extract specific data from an XML structure, convert it into PySpark DataFrames, and save the results as Snappy-compressed Parquet files.

## Project Structure

- **transformation.ipynb**: This notebook contains the core logic for reading XML files, transforming them into DataFrames, and saving them as parquet files.
- **sample_data.xml**: A sample XML file that is used as input for the transformation logic.
- **Target File**: This directory will contain the generated parquet files after running the transformation logic.

## Prerequisites

Ensure the following are installed:

- Python 3.x
- PySpark
- unittest or pytest for testing

You can install the required Python libraries with:

```bash
pip install pyspark lxml pytest
```

##Running the Project
Ensure the XML file is in the correct directory:

1. Place your sample XML file in the appropriate folder, e.g., jupyter_workspace/DataEngineer_Test/Source File/sample_data.xml.
Run the Transformation Notebook:

2. Open the transformation.ipynb notebook and run the cells to process the XML file and generate Parquet files.

3. After processing, the resulting Parquet files will be saved in the output folder, and compressed using Snappy.
