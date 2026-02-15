# Amazon Product Review Analysis using Apache Spark

## Project Overview

This project performs large-scale analysis of the **Amazon Product Reviews dataset** using **Apache Spark (PySpark)**.  
The objective is to demonstrate the use of distributed data processing, Spark SQL, and performance optimization techniques on real-world data.

> Note: The project was developed and executed using **VS Code with Jupyter Notebook support**.

---

## Dataset

**Dataset Name:** AmazonProductReviews.csv  
**Source:** Provided as part of the course material

### Key Columns Used

- `categories` – Product categories
- `name` – Product name
- `reviews.date` – Review date
- `reviews.rating` – Rating (1–5)
- `reviews.text` – Review content
- `reviews.title` – Review title
- `reviews.username` – Reviewer name

---

## Technology Stack

- Python 3.x  
- Apache Spark (PySpark)  
- Py4J  
- Jupyter Notebook (VS Code)  
- Git & GitHub  

---

## Environment Setup

### Java Installation

Apache Spark requires Java (JDK 8 or later).

Verify Java installation:
```bash
java -version


## Project Structure

amazon-reviews-spark-analytics/
│
├── notebook/
│   └── main.ipynb
│
├── dataset/
│   └── AmazonProductReviews.csv   (ignored by Git)
│
├── src/
│
├── .gitignore
├── README.md
└── requirements.txt


Analysis Tasks Performed

The following tasks were implemented using Spark:

Load and inspect the dataset

Data cleansing and schema correction

Extract primary product categories

Top-rated products (with minimum review threshold)

Most active reviewers

Monthly rating trends per category

Products with polarized reviews

Longest reviews by category

Year-over-year review growth

Review length vs rating analysis

Identification of products with declining ratings

Root cause analysis and insights


Optimization Techniques

Caching reused DataFrames

Reducing redundant Spark actions

Efficient aggregations


Result

Execution time improved significantly after optimization, demonstrating effective Spark performance tuning.
