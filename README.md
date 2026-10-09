# Customer Churn Analysis | Big Data & Machine Learning

A Big Data project focused on customer churn analysis and predictive modelling, developed as the final project of my Big Data Master's programme.

## Project Overview

Customer churn represents a significant business challenge for telecommunications companies. Identifying customers who are more likely to leave can help businesses develop targeted retention strategies and make better data-driven decisions.

This project analyses customer behaviour using PySpark and develops a Decision Tree classification model to predict customer churn.

## Objectives

* Explore customer demographics, usage patterns and subscription characteristics.
* Analyse churn rates across subscription types and contract lengths.
* Calculate descriptive statistics and examine correlations between numerical variables.
* Build and evaluate a supervised machine learning model.
* Translate analytical findings into actionable business recommendations.

## Technologies

* **Python & PySpark:** Data processing and analysis.
* **Apache Spark MLlib:** Machine learning pipeline and model evaluation.
* **Apache Cassandra:** Data storage and CQL queries.
* **Google Colab:** Cloud-based development environment.
* **Pandas & Matplotlib:** Data presentation and visualisation.

## Methodology

1. **Data preparation:** Load and inspect the customer dataset using PySpark.
2. **Exploratory data analysis:** Examine customer distributions and churn rates.
3. **Statistical analysis:** Calculate means, standard deviations and correlations.
4. **Predictive modelling:** Train a Decision Tree classifier using categorical encoding and a feature vector.
5. **Model evaluation:** Use a train-test split, hyperparameter tuning and cross-validation.
6. **Business recommendations:** Identify potential retention strategies based on the findings.

## Key Results

The final report presents the following results on the test set:

| Metric   | Result |
| -------- | -----: |
| Accuracy | 96.21% |
| ROC-AUC  | 0.9666 |

The exploratory analysis also identifies substantial differences in churn rates by contract length, with monthly contracts showing a 100% churn rate in the analysed dataset.

These findings should be interpreted in the context of the dataset and validated further before any production deployment.

## Repository Structure

* `notebooks/`: Executable Google Colab / Jupyter notebook.
* `docs/`: Scientific report, technical report and project presentation.

## Documentation

* [Scientific Report](docs/informe_cientifico.pdf)
* [Technical Report](docs/informe_tecnico.pdf)
* [Project Presentation](docs/presentacion.pdf)

## Reproducibility

The analysis was developed in Google Colab using PySpark. To reproduce the analysis, open the notebook in Google Colab, install the required dependencies and provide access to the dataset.

The Cassandra component was tested using a sample of nine manually inserted records due to environment limitations. Its query results should therefore be understood as a functional demonstration rather than a full-dataset analysis.

## Author

**Javier Bris Miñambres**

Final project — Master's in Big Data

*This project demonstrates the application of data analytics and machine learning techniques to a business problem involving customer retention.*

Project Defense

Watch the recorded presentation of my Master's final project, covering the methodology, technical implementation, results and business implications.

▶ Watch the project defense on YouTube

Video hosted on YouTube and shared as an unlisted link: https://youtu.be/Cvdv09xxyl0
