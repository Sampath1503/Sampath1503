# PROFESSIONAL ANALYTICS PORTFOLIO

**Sampath Kumar Panthagani**
Data Analyst | Customer Analytics | Machine Learning

---

## EXECUTIVE SUMMARY

Results-driven Data Analyst with demonstrated expertise in building end-to-end analytics solutions, predictive modeling, and business intelligence platforms. Proven ability to translate complex behavioral data into actionable business insights that drive revenue protection and customer retention strategies. Skilled in Python-based data science, SQL analytics, and Power BI dashboard development. Seeking opportunities to leverage analytical capabilities in a challenging Data Analyst or Associate Analyst role at leading consulting firms.

**Location:** Hyderabad, India  
**Email:** sampath967610@gmail.com  
**GitHub:** https://github.com/Sampath1503  
**LinkedIn:** https://www.linkedin.com/in/sampath-kumar-panthagani-2147a6250

---

## TECHNICAL SKILLS

### Programming & Data Manipulation
- **Python** (Advanced) – Pandas, NumPy, Scikit-learn, XGBoost
- **SQL** (Intermediate) – Data querying, aggregation, window functions
- **Data Processing** – ETL pipelines, feature engineering, data cleaning

### Machine Learning & Analytics
- Predictive Modeling (Logistic Regression, XGBoost, Random Forest)
- Classification & Regression Analysis
- Feature Engineering & Selection
- Class Imbalance Handling (SMOTETomek)
- Customer Segmentation & RFM Analysis
- Probabilistic Modeling (BG/NBD, Gamma-Gamma)

### Business Intelligence & Visualization
- **Power BI** – Dashboard design, DAX calculations, data modeling
- **Streamlit** – Web application development, interactive analytics
- Advanced data visualization and storytelling
- Executive-level reporting

### Core Analytical Competencies
- Exploratory Data Analysis (EDA)
- Statistical Analysis & Hypothesis Testing
- Churn Prediction & Customer Lifetime Value (CLV) Modeling
- Revenue-at-Risk Analysis
- Customer Analytics & Retention Strategy

---

## FEATURED PROJECTS

### PROJECT 1: Customer Analytics Portfolio – E-Commerce

**Business Objective**
Develop an integrated customer analytics system to identify revenue exposure, protect high-value customers, and optimize retention spending through data-driven prioritization.

**Problem Statement**
E-commerce businesses face challenges in allocating limited retention budgets. Without understanding revenue concentration and churn risk interaction, companies overspend on low-impact customers while under-protecting high-value segments.

**Solution Delivered**

A comprehensive three-tier analytics framework combining:

1. **Churn Risk Prediction (Logistic Regression)**
   - Identified customers likely to disengage within 90-day window
   - Model Accuracy: 98% | Recall: 87% on churn class
   - Behavioral features: recency, purchase velocity, customer lifetime, return behavior

2. **Customer Lifetime Value Forecasting (BG/NBD + Gamma-Gamma)**
   - Predicted 6-month CLV for 4,300+ customers
   - Key Finding: 33% of customers contribute 88% of projected revenue
   - Segmentation: High/Medium/Low value tiers

3. **Revenue-at-Risk Intelligence**
   - Formula: Revenue at Risk = Churn Probability × CLV (6 months)
   - Quantified Exposure: ₹197K revenue at risk (~27.5% of total)
   - Enabled risk-based retention prioritization

**Tools & Technologies**
- Python (Pandas, NumPy, Scikit-learn, Lifetimes)
- SQL data aggregation and feature engineering
- Power BI executive dashboards
- Streamlit interactive application
- Git version control

**Key Metrics & Results**
| Metric | Value |
|--------|-------|
| Churn Model Accuracy | 98% |
| Churn Recall | 87% |
| High-Value Customer Segment | 33% of base |
| Revenue Contribution (Top 33%) | 88% |
| Total Revenue at Risk | ₹197K |
| Revenue Exposure % | 27.5% |

**Business Impact**
- Enables targeted retention campaigns reducing waste by focusing on revenue-exposed customers
- Provides quantifiable revenue protection strategy
- Supports executive decision-making with clear financial impact metrics
- Actionable customer lists for retention teams

**Dashboard Components**

*Churn Risk Dashboard*
- Risk distribution across customer base
- High-risk customer identification table
- Behavioral metrics by risk segment
- Trend analysis and cohort comparisons

*Revenue-at-Risk Dashboard*
- Financial exposure by customer segment
- Revenue concentration analysis
- High-value customer at-risk overlay
- Retention priority recommendations

*Customer Segmentation Dashboard*
- RFM analysis with CLV overlay
- Value vs. risk positioning matrix
- Customer lifecycle stage analysis
- Actionable segment recommendations

**Repository:** https://github.com/Sampath1503/customer-analytics-portfolio-e-commerce

**Live Demo:** https://customer-analytics-portfolio-e-commerce.streamlit.app/

---

### PROJECT 2: Telecom Churn Prediction ML Automation

**Business Objective**
Build a production-ready machine learning pipeline for daily churn prediction, enabling proactive retention campaigns through automated risk segmentation and operational integration.

**Problem Statement**
Telecom providers require real-time identification of at-risk customers to deploy targeted retention interventions. Manual churn assessment is inefficient and misses time-sensitive intervention windows.

**Solution Delivered**

End-to-end ML automation system featuring:

1. **Data Pipeline Architecture**
   - SQL Server data sourcing and transformation
   - CSV-based snapshot processing
   - Automated ETL workflow

2. **Advanced Feature Engineering**
   - Total usage aggregation (day, evening, night, international)
   - Billing metrics (total charges, charge-per-minute ratios)
   - Service quality indicators (service calls, tenure)
   - Behavioral risk signals

3. **ML Model Development**
   - Algorithm: XGBoost Classifier
   - Class Imbalance Handling: SMOTETomek resampling
   - Hyperparameter Optimization: RandomizedSearchCV
   - Cross-validation and performance evaluation

4. **Automated Batch Inference**
   - Daily scheduled churn scoring
   - Windows Task Scheduler automation
   - Structured logging and monitoring
   - CSV output for BI integration

5. **Risk Segmentation Framework**
   - Low Risk (< 0.30): Monitor
   - Medium Risk (0.30–0.70): Proactive outreach
   - High Risk (> 0.70): Immediate retention offer

**Tools & Technologies**
- Python (Pandas, NumPy, Scikit-learn, XGBoost, imblearn)
- SQL Server and CSV-based data sourcing
- Power BI executive dashboards
- Windows Task Scheduler automation
- Structured logging framework

**Key Metrics & Results**
| Metric | Value |
|--------|-------|
| Model Accuracy | 98% |
| Recall (Churn Class) | 87% |
| Precision (Churn Class) | 98% |
| Customer Base | ~10,000 customers |
| High-Risk Segment Size | 12% of base |

**Confusion Matrix Performance**
```
Predicted:  No Churn    Churn
Actual:
No Churn    856         3
Churn       19          122
```

**Business Impact**
- Identifies high-value at-risk customers for targeted campaigns
- Reduces manual reporting effort through automation
- Bridges ML predictions with operational BI dashboards
- Enables data-driven retention budget allocation
- Provides repeatable, scalable process for ongoing predictions

**Dashboard Components**

*Executive Overview*
- Total customer count and churn rate
- Active vs. churned customer split
- Risk distribution overview
- Key performance indicators

*Churn Driver Analysis*
- Feature importance visualization
- Behavioral patterns by risk segment
- Usage metric comparison
- Service quality correlations

*Business Insights & Retention Strategy*
- High-risk customer identification
- Segment-specific retention recommendations
- Campaign targeting guidelines
- Expected impact estimates

*Risk Monitoring & Model Output*
- Real-time churn predictions
- Risk score distribution
- Model performance metrics
- Prediction accuracy tracking

**Repository:** https://github.com/Sampath1503/telecom-churn-prediction-ml-automation

---

### PROJECT 3: E-Commerce Recommender System

**Business Objective**
Develop a hybrid recommendation engine that balances content-based precision with collaborative filtering diversity, optimizing for both accuracy and user engagement.

**Problem Statement**
E-commerce platforms face the cold-start problem and sparse user-item interaction matrices. Single-engine approaches fail to balance recommendation accuracy with catalog coverage and diversity.

**Solution Delivered**

Sophisticated hybrid recommendation architecture featuring:

1. **Content-Based Engine**
   - TF-IDF vectorization (1,535 terms)
   - Pairwise cosine similarity computation
   - Product feature similarity scoring
   - Strong performance on cold-start scenarios

2. **Collaborative Filtering Engine**
   - User-based and item-based approaches
   - Mean-centered cosine similarity (removes rating bias)
   - Handles sparse user-item matrix (300×500, 95% sparse)
   - Incorporates user behavior patterns

3. **Adaptive Hybrid Engine**
   - Dynamic alpha blending: score = α·CB + (1-α)·CF
   - Cold users (few ratings): α = 0.85 (content-heavy)
   - Warm users (many ratings): α = 0.30 (collaborative-heavy)
   - Smooth transition based on user activity level

4. **Comprehensive Evaluation Framework**
   - Leave-one-out cross-validation
   - Multiple accuracy metrics (Hit@K, NDCG@K)
   - Coverage and diversity analysis
   - Beyond-accuracy performance evaluation

**Tools & Technologies**
- Python (Scikit-learn, Pandas, NumPy)
- TF-IDF and cosine similarity algorithms
- Collaborative filtering implementation
- Streamlit interactive interface
- Pickle-based model persistence

**Key Metrics & Results**

| Engine | Hit@5 | Hit@10 | NDCG@10 | Coverage | Diversity |
|--------|-------|--------|---------|----------|-----------|
| Content-Based | 2.7% | 7.3% | 0.029 | 77.4% | 0.000 |
| CF User-Based | 0.0% | 0.0% | 0.000 | 49.8% | 0.797 |
| CF Item-Based | 0.0% | 0.0% | 0.000 | 84.0% | 0.792 |
| Hybrid Fixed | 13.3% | 17.3% | 0.113 | 82.0% | 0.173 |
| **Hybrid Adaptive** | **16.7%** | **24.0%** | **0.136** | **83.4%** | **0.312** |

**Business Impact**
- Hybrid_Adaptive wins on all accuracy metrics (3.3× improvement over best single engine)
- Maintains 98% personalization while improving recommendations
- Balances accuracy, coverage, and diversity for production deployment
- Scalable architecture supporting 500 products, 300 users, 7,456 interactions

**Dataset Architecture**
- Products: 500 items across 5 categories (Electronics, Clothing, Home & Kitchen, Books, Sports)
- Users: 300 active users with demographic data
- Interactions: 7,456 ratings (1-5 scale) with purchase indicators
- Sparsity: 95% sparse user-item matrix

**Repository:** https://github.com/Sampath1503/ecommerce-recommender

---

## EDUCATION

**M.Sc. Computational Data Science**  
Acharya Nagarjuna University  
Grade: 80%

**B.Sc. Statistics (MSCS)**  
Vijaya Jyothi Degree College  
Grade: 70%

---

## PROFESSIONAL CERTIFICATIONS

- Data Science Internship Completion Certificate – AiVariant
- Data Science Specialization Certificate – ExcelR

---

## PROFESSIONAL COMPETENCIES

### Analytics & Business Intelligence
- Business problem definition and solution design
- Stakeholder communication and executive reporting
- ROI calculation and business impact quantification
- Data-driven decision support

### Data Science & Modeling
- End-to-end ML pipeline development
- Exploratory data analysis and pattern recognition
- Predictive and prescriptive analytics
- Algorithm selection and hyperparameter tuning

### Software Engineering Practices
- Production-ready code development
- Automated pipeline implementation
- Version control and collaborative development
- Documentation and knowledge transfer

### Domain Expertise
- Customer analytics and behavior analysis
- Churn prediction and retention strategy
- Revenue optimization and financial analysis
- Telecom and e-commerce industry knowledge

---

## SUMMARY OF QUALIFICATIONS

✓ 3+ years of hands-on data science and analytics experience

✓ Proven track record delivering business-critical analytics solutions

✓ Advanced proficiency in Python, SQL, and Power BI

✓ Expertise in machine learning: classification, regression, clustering, and probabilistic modeling

✓ Experience with production ML pipelines and automation

✓ Strong communication skills with ability to translate technical solutions to business impact

✓ Portfolio of 3 deployed analytics solutions generating measurable business value

---

## CONTACT & PORTFOLIO LINKS

**Email:** sampath967610@gmail.com  
**Phone:** +91 9676105753  
**GitHub:** https://github.com/Sampath1503  
**LinkedIn:** https://www.linkedin.com/in/sampath-kumar-panthagani-2147a6250

**Featured Projects:**
1. Customer Analytics Portfolio – https://github.com/Sampath1503/customer-analytics-portfolio-e-commerce
2. Telecom Churn ML Automation – https://github.com/Sampath1503/telecom-churn-prediction-ml-automation
3. E-Commerce Recommender – https://github.com/Sampath1503/ecommerce-recommender

---

*This portfolio demonstrates a commitment to data-driven problem solving, technical excellence, and business impact. All projects are production-ready and available for technical review.*
