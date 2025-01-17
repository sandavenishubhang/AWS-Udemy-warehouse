# AWS Udemy Warehouse Project

A comprehensive data analysis project focusing on Udemy course insights using an end-to-end data pipeline. This project leverages **AWS Athena**, **Python**, and **Tableau** to process, analyze, and visualize data, delivering actionable insights for course engagement, pricing, and instructor performance.

---

## 🚀 Project Overview

### **Objective**
To extract meaningful insights from Udemy course data, including instructor revenue, engagement metrics, pricing analysis, and course quality trends, through a robust ETL pipeline and interactive dashboards.

### **Technologies**
- **AWS S3 & Athena**: For data storage and querying.
- **Python**: To build and automate the ETL pipeline.
- **Tableau**: For creating interactive and insightful dashboards.
- **Jupyter Notebook**: For exploratory data analysis and pipeline development.

### 🏗️ Data Warehouse Architecture

### Overview
The data warehouse architecture for this project consists of the following key components:
1. **Raw Data Ingestion**: Data is uploaded to AWS S3.
2. **ETL Pipeline**: The ETL process cleanses, transforms, and loads data into a structured format.
3. **Athena Query Engine**: AWS Athena is used to query the data for analysis.
4. **Visualization**: Tableau dashboards are used to present the insights.

### Architecture Diagram
![Data Warehouse Architecture](ScreenShots/Screenshot%202025-01-16%20at%208.24.40%E2%80%AFPM.png)

### **Key Features**
1. **ETL Pipeline**:
   - Extracts raw data from source files.
   - Cleans and transforms the data for structured analysis.
   - Loads data into AWS S3 and queries using AWS Athena.
2. **Interactive Visualizations**:
   - Engagement trends.
   - Revenue and pricing distributions.
   - Instructor performance and quality ratings.
3. **Actionable Insights**:
   - Identified high-performing instructors and revenue concentration.
   - Highlighted engagement patterns based on course quality.
   - Analyzed pricing models for optimal strategies.

---

## 📊 Key Insights and Dashboards

### **1. Engagement Analysis**
- **Insight**: Highly rated courses have higher engagement and retention rates.
- **Visualization**:
![Engagement Analysis](visualisations/Screenshot%202025-01-16%20at%208.24.10%E2%80%AFPM.png)

### **2. Pricing and Revenue Distribution**
- **Insight**: Premium courses contribute significantly to revenue, while free courses drive engagement.
- **Visualization**:
![Pricing and Revenue Distribution](visualisations/Screenshot%202025-01-16%20at%208.23.50%E2%80%AFPM.png)

### **3. Instructor Revenue Concentration**
- **Insight**: The top 5 instructors generate over 40% of total revenue.
- **Visualization**:
![Instructor Revenue Concentration](visualisations/Screenshot%202025-01-16%20at%208.24.03%E2%80%AFPM.png)

### **4. Course Quality Ratings**
- **Insight**: Courses rated above 4.5 show better student engagement and revenue performance.
- **Visualization**:
![Course Quality Ratings](visualisations/Screenshot%202025-01-16%20at%208.24.20%E2%80%AFPM.png)

### **5. Overall Dashboard**
- **Insight**: A consolidated view of engagement, pricing, instructor revenue, and course ratings.
- **Visualization**:
![Overall Dashboard](ScreenShots/Dashboard%201.png)
[View Tableau Dashboard](https://public.tableau.com/app/profile/shubhang.yadav.sandaveni/viz/UdemyDatawarehouse/Dashboard1)
---

## 📂 Project Structure

```plaintext
AWS-UDEMY-WAREHOUSE/
├── Reports/
│   ├── Udemy Course Analysis Presentation.pptx   # Project presentation
│   ├── UDEMY_Analysis_FULL REPORT-2.pdf           # Detailed analysis report
├── Screenshots/
│   ├── Dashboard 1.png                            # Overall Tableau dashboard
│   ├── Screenshot 2025-01-16 at 8.24.40 PM.png    # ETL Pipeline screenshot
├── Scripts/
│   ├── udemy_etl_job_final.ipynb                  # ETL pipeline script
├── visualisations/
│   ├── Screenshot 2025-01-16 at 8.23.50 PM.png    # Course Quality Ratings
│   ├── Screenshot 2025-01-16 at 8.24.03 PM.png    # Engagement Analysis
│   ├── Screenshot 2025-01-16 at 8.24.10 PM.png    # Instructor Revenue Concentration
│   ├── Screenshot 2025-01-16 at 8.24.20 PM.png    # Pricing and Revenue Distribution
└── README.md                                      # Project documentation
```
---

## 🛠️ Tools and Platforms

### **1. AWS Athena**
- Enabled efficient querying of structured data stored in S3.
- Used SQL queries to analyze instructor and course performance metrics.

### **2. Python**
- Built an ETL pipeline to extract, transform, and load (ETL) data into AWS S3.
- Automated data cleaning and transformation processes.

### **3. Tableau**
- Designed interactive dashboards to explore insights such as engagement metrics, pricing trends, and instructor performance.
- Delivered actionable visuals to aid in data-driven decision-making.

### **4. Jupyter Notebook**
- Facilitated exploratory data analysis (EDA) and debugging of the ETL process.
- Developed and tested scripts before integrating them into the ETL pipeline.

---

## 📜 Reports and Deliverables

### **1. Project Presentation**
- **File**: [Udemy Course Analysis Presentation.pptx](Reports/Udemy%20Course%20Analysis%20Presentation.pptx)
- **Description**: A concise PowerPoint summarizing the project's key insights, methodologies, and findings.

### **2. Comprehensive Report**
- **File**: [UDEMY_Analysis_FULL REPORT-2.pdf](Reports/UDEMY_Analysis_FULL%20REPORT-2.pdf)
- **Description**: A detailed report outlining the project's objectives, processes, results, and recommendations.

---

## 📋 How to Use

### **1. Clone the Repository**
Use the following command to clone the repository to your local machine:
```bash
git clone https://github.com/sandavenishubhang/AWS-Udemy-warehouse.git
```
### **2. Navigate to the Project Directory**
```bash
cd AWS-Udemy-warehouse
```
### **3. Run the ETL Pipeline Script**
Open the ETL pipeline script in Jupyter Notebook and execute the pipeline:
```bash
jupyter notebook Scripts/udemy_etl_job_final.ipynb
```

### **4. Explore the Dashboards**
- Open the Tableau visualizations stored in the `visualisations` folder.
- Review the snapshots in the `Screenshots` folder for key insights and trends.

### **5. Review Reports**
- Refer to the detailed report `UDEMY_Analysis_FULL REPORT-2.pdf` in the `Reports` folder for in-depth analysis and conclusions.
- Use the presentation file `Udemy Course Analysis Presentation.pptx` to present the project highlights.

---

## 🌟 Acknowledgments

- **Udemy**: For providing the dataset that formed the foundation of this analysis.
- **AWS Athena & S3**: For enabling efficient data querying and storage solutions.
- **Tableau**: For creating engaging and interactive dashboards.
- **Python Community**: For tools and libraries that supported the ETL pipeline and data processing.

---

## 💡 Future Work

### **1. Predictive Analytics**
- Integrate machine learning models to predict course success based on instructor performance, pricing, and quality metrics.

### **2. Recommendation Systems**
- Build a recommendation system to suggest courses based on user preferences and engagement history.

### **3. Dashboard Automation**
- Automate dashboard updates to provide real-time insights and trend tracking.

### **4. Data Enrichment**
- Integrate additional data sources such as user reviews and course completion rates for more granular insights.

---

## 📬 Contact

For any questions or feedback, feel free to reach out:

- **Email**: sshubhangyadav@gmail.com
- **GitHub**: [sandavenishubhang](https://github.com/sandavenishubhang)
- **LinkedIn**: [Shubhang Yadav](https://www.linkedin.com/in/shubhang-yadav-sandaveni)

---

