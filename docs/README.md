# README : PySpark

## Table of contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [Project structure](#project-structure)
- [Installation](#installation)
- [Contribution](#contribution)
- [Author](#author)

## Description

This project is a series of PySpark tutorials designed to learn the basics of Spark with Python. It includes several Jupyter notebooks categorized by difficulty level.

The tutorials cover various topics such as introduction to PySpark, manipulation of RDDs, calculation of PageRank, using Spark SQL, and machine learning with Spark.

## Prerequisites

- [Anaconda 2019+](https://www.anaconda.com/download/)
- Required Java 8/11. 
    - You can set the `JAVA_HOME` environment variable to point to the Java 8/11 folder you want to use for the project, from `Edit the system environment variables` window or `set JAVA_HOME=<path_to_java>` in command-line before running `jupyter notebook`. 
    - You may also install Java OpenJDK **inside** your Anaconda environment with `conda install openjdk`. The `JAVA_HOME` variable should be automatically updated for this environment only.

## Project structure

```bash
├── 1-beginner/
│   ├── 1-Initiation.ipynb
│   └── jupyter.png
├── 2-novice/
│   ├── 1-Initiation-RDD.ipynb
│   ├── 2-Pagerank-RDD.ipynb
│   ├── FL_insurance_sample.csv
│   └── pagerank.png
├── 3-advanced/
│   ├── 1-Initiation-SparkSQL.ipynb
│   ├── 2-Advanced-SQL-and-ML.ipynb
│   ├── FL_insurance_sample.csv
│   └── titanic.csv
├── cheatsheets/
│   ├── conda-cheatsheet.pdf
│   ├── Jupyter-notebook.pdf
│   ├── Pyspark-RDD.pdf
│   ├── Pyspark-SQL.pdf
│   └── Python.pdf
├── docs/
│   ├── css/
│   │   └── custom.css
│   ├── images/
│   │   └── ...
│   ├── index.html
│   ├── intro.pdf
│   ├── pyspark.pdf
│   └── README.md
├── .gitignore
└── requirements.txt
```

## Installation

To install the project on your local machine, you can use the following command :

```bash
git clone https://github.com/hugocollin/pyspark
```

Then move to the project directory and create a new conda environment with the following command :

```bash
conda create -n pyspark python=3.11
conda activate pyspark
pip install -r requirements.txt
# pip install bokeh jupyter numpy pandas psutil pyspark seaborn
```

*We provide you with a `requirements.txt` which is used to download dependencies in a conda environment we will name `pyspark`.*

You can now run the Jupyter notebook.

## Contribution

All contributions are welcome. Here's how you can help :

1. Fork the project.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## Author

This project was developed by COLLIN Hugo a student from the Master 2 SISE program at the University of Lyon 2.