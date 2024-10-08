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
