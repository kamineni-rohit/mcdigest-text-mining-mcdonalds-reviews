# McDigest: Text Mining McDonald's Customer Reviews

This project applies text mining techniques to over 33,000 McDonald's customer reviews sourced from Google Reviews. Using SAS Enterprise Miner, the analysis reveals insights into customer sentiment, operational pain points, and regional feedback patterns.

## 🧠 Objective
To analyze unstructured text data from McDonald’s customer reviews and extract actionable insights that improve service quality, customer satisfaction, and operational efficiency.

## 🔍 Business Problems Addressed
1. **Comprehensive Feedback Analysis**: Categorize and quantify themes across positive and negative reviews.
2. **Regional Sentiment Understanding**: Compare sentiment distribution and top complaints across U.S. regions.
3. **Operational Recommendations**: Translate feedback into improvements in cleanliness, food quality, staffing, and infrastructure.

## 🧪 Methodology

### Dataset
- 33,000+ reviews from U.S. McDonald’s locations (public dataset from Kaggle)
- Columns include: review text, rating, location (lat/lon), category, timestamps, etc.

### Tools
- SAS Enterprise Miner for data preparation, clustering, text parsing, and supervised modeling
- JMP & Excel for initial cleaning and segmentation

### Modeling Approach
- Created stop lists, adjusted weighting methods (Entropy, IDF), and applied clustering
- Modeled both **positive** and **negative** reviews independently
- Conducted region-wise topic analysis for Eastern, Western, Northern, and Southern U.S.
- Built a predictive sentiment classification model with custom topics

## 📊 Key Insights

### Negative Feedback Clusters
- **Cleanliness & Security**: Particularly dominant in Eastern and Western regions
- **Cold/Stale Food** and **Drive-through Delays**: Recurring concerns in Southern and Western regions
- **Machine Malfunctions** and **Restroom Conditions**: Strong negative sentiment triggers

### Positive Feedback Clusters
- **Quick Drive-through Service**, **Play Area**, and specific menu items like **Quarter Pounder** and **Apple Pie** earned praise
- Positive sentiment was generally more dispersed across categories

### Predictive Modeling
- Built a sentiment classifier using a supervised model
- Regression model had the best performance with ~17% misclassification rate
- Custom topics used: Food, Ambience, Service, Others

## 📌 Business Recommendations
- Improve restroom hygiene and deploy regional cleaning standards
- Optimize drive-through staffing and machine maintenance schedules
- Launch regional marketing campaigns focused on highly rated menu items
- Tailor employee training to region-specific service issues

## 🛠️ Tech Stack
- SAS Enterprise Miner
- JMP & Excel
- Text Mining, Clustering, Predictive Modeling

## 👥 Team
- Rohit Kamineni  
- Satakshi Deshmukh  
- Hema Pradhiksha Dhanapal  
- Sri Kavya Reddy Narra  
- Sravya Machavarapu

