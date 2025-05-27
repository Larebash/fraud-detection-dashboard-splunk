# Fraud-detection-dashboard-splunk
This project features an interactive Splunk dashboard designed to detect and analyze fraudulent transactions using synthetic banking data.

## 📊 Features
- Total and trend of fraudulent payments over time
- Category-wise fraud detection
- Demographic filters: Gender and Age Group
- Visualizations: Bar charts, line charts, single-value panels
- ## 🛠️ Tools Used
- Splunk Enterprise
- SPL (Search Processing Language)
- CSV dataset (simulated)
- GitHub
- ## 📷 Dashboard
[📄 View Dashboard PDF](fraud_dashboard.pdf)

## 🚀 How to Use
1.  Covert your xlsx file into Csv
2. Import the dataset into Splunk (`dataset_sample.csv`)
3. Search to Confirm Data is Ingested (index=main sourcetype=csv)
4. Copy and run the SPL queries in `queries.spl`
5.  Create Basic Visualizations by 
6.   Create the Dashboard
7. Import the dashboard from `dashboard.xml`
## 📁 Project Structure
├── README.md
├── dashboard.xml
├── queries.spl
├── dataset_sample.csv
└── dashboard.pdf

## 👤 Author
[Larewaju on LinkedIn](https://www.linkedin.com/in/larewaju)

