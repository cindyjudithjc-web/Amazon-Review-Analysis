# ☁️ Cloud-Based Big Data Analytics for Amazon Beauty Reviews

![Azure](https://img.shields.io/badge/Cloud-Microsoft%20Azure-blue)
![Python](https://img.shields.io/badge/Python-3.10-yellow)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Analytics-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

> A cloud-native big data analytics and machine learning solution built on Microsoft Azure for analysing Amazon Beauty Reviews using NLP, sentiment analysis, and predictive analytics.

## Project Overview

This project demonstrates the design and implementation of a scalable cloud-based big data analytics solution using the Amazon Beauty Reviews dataset within the Microsoft Azure cloud ecosystem. The project combines cloud computing, Natural Language Processing (NLP), machine learning, and business intelligence techniques to analyse customer reviews and generate actionable insights for enterprise decision-making.

The solution was implemented using Azure Machine Learning, Azure Data Lake Storage Gen2, Python, and Scikit-learn to perform data ingestion, preprocessing, sentiment analysis, machine learning model development, and cloud resource optimization.

---

# Objectives

The main objectives of this project were to:

- Design a scalable cloud-based big data architecture
- Store and process large semi-structured datasets in the cloud
- Perform data preprocessing and cleaning
- Apply Natural Language Processing (NLP) techniques
- Develop and compare machine learning models
- Generate business insights from customer review data
- Explore cloud security, monitoring, and cost optimization strategies

---

# Dataset Information

## Dataset Used

Amazon Beauty Reviews Dataset

### Files
- `All_Beauty.jsonl.gz`
- `meta_All_Beauty.jsonl.gz`

### Dataset Characteristics
- Over 700,000 customer reviews
- Semi-structured JSON Lines format
- Includes ratings, review text, timestamps, helpful votes, and purchase verification information

### Key Features Used
- rating
- title
- text
- asin
- parent_asin
- user_id
- timestamp
- helpful_vote
- verified_purchase

---

# Cloud Architecture

The project architecture was implemented within the Microsoft Azure ecosystem.

## Core Components

### Azure Data Lake Storage Gen2
Used for:
- storing raw datasets
- secure cloud storage
- scalable data management

### Azure Machine Learning Workspace
Used for:
- notebook execution
- preprocessing
- NLP analysis
- machine learning model training
- evaluation and visualization

### Python Environment
The analytical workflow was implemented using:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TextBlob
- NLTK

---

# Project Workflow

## 1. Data Ingestion

The datasets were uploaded into Azure cloud storage and accessed through Azure Machine Learning notebooks.

### Process
- Dataset upload to Azure Storage
- Secure cloud access
- Notebook-based processing
- Compressed `.jsonl.gz` storage format

---

## 2. Data Preprocessing

Several preprocessing steps were performed to improve data quality and analytical reliability.

### Preprocessing Tasks
- Duplicate removal
- Empty column identification
- Feature selection
- Text cleaning
- Text normalization
- Data validation

### Data Cleaning Actions
- Removed duplicate records
- Excluded empty `images` column
- Cleaned review text
- Standardized textual data

---

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand customer review behavior and dataset patterns.

### Analysis Performed
- Rating distribution
- Helpful vote analysis
- Verified purchase analysis
- Sentiment distribution
- Customer feedback trends

---

## 4. Natural Language Processing (NLP)

NLP techniques were applied to analyse customer sentiments within review texts.

### NLP Tasks
- Text preprocessing
- Tokenization
- TF-IDF vectorization
- Sentiment analysis

### Sentiment Categories
- Positive
- Neutral
- Negative

---

# Machine Learning Models

Three supervised machine learning models were implemented and compared.

| Model | Accuracy |
|---|---|
| Logistic Regression | 95.47% |
| Random Forest | 88.98% |
| Naïve Bayes | 80.36% |

## Best Performing Model

Logistic Regression achieved the highest predictive accuracy and demonstrated strong performance for sentiment classification tasks.

---

# Cloud Security Implementation

Security measures implemented and discussed include:

- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Encryption at Rest
- Encryption in Transit
- Secure cloud authentication
- Data minimization practices

---

# Cost Optimization Strategies

Several cost optimization approaches were considered:

- Compressed dataset storage
- On-demand compute usage
- Removal of unnecessary data columns
- Lightweight compute allocation
- Azure Cost Management monitoring
- Resource utilization optimization

---

# Monitoring and System Management

Cloud-native monitoring services explored include:

- Azure Monitor
- Azure Log Analytics
- Azure Cost Management
- Azure Storage Explorer
- Azure Machine Learning Studio

These tools support:
- performance monitoring
- troubleshooting
- resource management
- operational governance

---

# Business Insights Generated

The project demonstrated how customer review analytics can support:

- customer satisfaction analysis
- product performance evaluation
- sentiment tracking
- marketing strategy improvement
- enterprise decision-making

---

# Technologies Used

## Cloud Services
- Microsoft Azure
- Azure Machine Learning
- Azure Data Lake Storage Gen2
- Azure Monitor
- Azure Cost Management

## Programming & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TextBlob
- NLTK

---

# Project Structure

```bash
project/
│
├── datasets/
│   ├── All_Beauty.jsonl.gz
│   └── meta_All_Beauty.jsonl.gz
│
├── notebooks/
│   └── amazon_reviews_analysis.ipynb
│
├── outputs/
│   ├── charts/
│   ├── visualizations/
│   └── model_results/
│
├── architecture/
│   └── cloud_architecture_diagram.png
│
└── README.md
```

---

# How to Run the Project

## Step 1: Clone Repository

```bash
git clone <repository-link>
```

## Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn textblob nltk
```

## Step 3: Upload Dataset

Upload the dataset files into Azure Storage or place them within the notebook working directory.

## Step 4: Launch Notebook

Open:

```bash
amazon_reviews_analysis.ipynb
```

## Step 5: Run Analysis

Execute notebook cells sequentially to:
- preprocess data
- perform NLP
- train machine learning models
- generate visualizations

---

# Screenshots Included in Project

The report and repository include screenshots of:

- Azure ML Workspace
- Azure Storage Containers
- Dataset Upload Process
- Preprocessing Steps
- Model Evaluation Results
- Accuracy Comparison Charts
- Cloud Monitoring Configuration
- Compute Resource Setup

---

# Challenges Encountered

Some challenges experienced during implementation included:

- Azure storage authentication issues
- Package installation errors
- Compute configuration limitations
- Cloud permission restrictions within student subscription environments

These issues were resolved through troubleshooting, dependency management, and cloud configuration adjustments.

---

# Future Improvements

Future enhancements may include:

- Distributed Spark processing
- Real-time streaming analytics
- Deep learning implementation
- Automated ML pipelines
- Deployment of predictive APIs
- Enterprise-scale dashboard integration

---

# Conclusion

This project successfully demonstrated the practical implementation of a cloud-based big data analytics architecture using Microsoft Azure. By integrating cloud computing, NLP, and machine learning techniques, the project transformed large-scale customer review data into actionable business intelligence capable of supporting enterprise decision-making.

The implementation highlights the growing importance of scalable cloud analytics solutions in modern organizations and demonstrates how machine learning can be leveraged to derive valuable insights from unstructured customer-generated data.

---

# Author

JUDITH EMUOYIBOFARHE

Available for:
- Data Science Projects
- Machine Learning Projects
- Cloud Analytics Projects
- Business Intelligence Solutions

---

# References

- Davenport, T.H. and Harris, J.G. (2017) *Competing on Analytics: The New Science of Winning*. Boston: Harvard Business Review Press.

- Géron, A. (2022) *Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow*. 3rd edn. Sebastopol: O’Reilly Media.

- Mell, P. and Grance, T. (2011) *The NIST Definition of Cloud Computing*. Gaithersburg: National Institute of Standards and Technology.

- Microsoft (2024) *Azure Architecture Center*. Available at: https://learn.microsoft.com/en-us/azure/architecture/

- Pedregosa, F. et al. (2011) ‘Scikit-learn: Machine Learning in Python’, *Journal of Machine Learning Research*, 12, pp. 2825–2830.

