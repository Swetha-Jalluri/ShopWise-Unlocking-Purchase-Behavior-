# ShopWise: Unlocking Purchase Behavior  

## Problem Setting  
E-commerce platforms are integral to the modern shopping experience, offering convenience and accessibility to a diverse user base. However, understanding customer purchasing behavior remains a significant challenge for online retailers. Customers’ purchase intentions are influenced by various factors, such as browsing patterns, time spent on pages, and session attributes.  

Decoding these intents can significantly enhance marketing strategies, inventory management, and personalized recommendations, ultimately boosting sales. Despite the availability of vast amounts of user behavior data, the challenge lies in uncovering actionable insights and developing accurate predictive models to understand purchasing decisions.  

## Problem Definition  
This project seeks to answer the following key questions:  
- What patterns and insights can be uncovered from user behavior data that are indicative of purchase intent?  
- How can predictive models be developed to accurately classify and predict customers’ likelihood of making a purchase?  
- Which classification algorithms perform best in predicting purchase intent, and how can preprocessing techniques improve model accuracy?  

## Data Source  
The **"Online Shoppers Purchasing Intention Dataset"** from the UCI Machine Learning Repository will be used as the primary data source.  
[Dataset Link](https://archive.ics.uci.edu/dataset/468/online+shoppers)  

## Data Description  
The dataset comprises **18 attributes**, including **10 numeric** and **8 categorical** variables, along with a target variable, **‘Revenue’**, which indicates whether a session resulted in a purchase (`True`) or not (`False`).  

### Key details about the dataset:  
- **Number of instances**: 12,330  
- **Number of attributes**: 18 predictors and 1 target variable  

## Objectives and Key Results (OKRs)  
- **Analyze user behavior** to uncover patterns influencing purchase intentions.  
  - Identify **3+ significant factors** impacting purchasing behavior (e.g., session duration, page views, proximity to special days).  
- **Develop and validate** predictive models to estimate purchase propensity.  
- **Compare and evaluate** the performance of **5 classification algorithms**, selecting the top-performing model.  
- **Enhance data preprocessing techniques** to improve model performance.  
  - Use **SMOTE** to balance the dataset, improving recall for minority classes by **15%**.  
  - Apply **PCA** to retain **85%+ variance** while reducing dimensionality.  

## Key Performance Indicators (KPIs)  
1. **Model Accuracy**: Achieve **90% or higher** accuracy in predicting purchase intent.  
2. **Data Balance**: Improve minority class recall by **at least 15%** using SMOTE.  
3. **Dimensionality Reduction**: Retain **85% or more** of data variance after applying PCA.  
4. **Feature Insights**: Identify and rank the **top 5 features** influencing purchasing behavior.  
5. **Algorithm Comparison**: Benchmark **5 classification algorithms**, with detailed evaluation based on **F1-score, precision, and recall**.  
6. **Documentation**: Deliver a **comprehensive report** with findings, insights, and future opportunities for improvement.  

## Installation and Usage  
### Prerequisites  
Ensure you have Python installed along with the following dependencies:  
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn


