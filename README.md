Small Business Financial Segmentation

Project Overview
This project analyzes the financial characteristics of small business owners using K-Means clustering.
By identifying key financial features with high variance, we segment business owners into distinct groups, providing insights that can aid in financial planning, loan approvals, and business support strategies.

📊 Methodology
Data Preparation – Imported libraries and loaded the dataset.

Feature Selection – Identified the five financial features with the highest variance.

Standardization – Scaled the selected features for consistent analysis.

K-Means Clustering – Tested cluster numbers (2 to 12) and selected the optimal 3 clusters based on inertia and silhouette scores.

Cluster Analysis – Examined mean feature values per cluster and visualized them with bar charts.

Dimensionality Reduction – Applied Principal Component Analysis (PCA) for 2D visualization of the clusters.

🔍 Key Findings
Small business owners can be categorized into three financial groups based on spending, saving, and loan behavior.

PCA visualization helped interpret the clusters effectively in a lower-dimensional space.

This segmentation can assist banks, investors, and policymakers in tailoring financial products and support strategies.

📂 Data Source
The dataset used in this analysis was obtained from Board of Governors of the Federal Reserve System(https://www.federalreserve.gov/econres/scf_2019.htm). You can access the dataset it here: https://www.federalreserve.gov/econres/files/scfp2019excel.zip. If the dataset is publicly available, please check the licensing terms before use.

🚀 Future Improvements
Exploring alternative clustering methods like DBSCAN or hierarchical clustering for more refined segmentation.

Adding external financial indicators to enhance clustering insights.

🛠 How to Run the Notebook
Clone the repository:

git clone https://github.com/HarrisTekenah/Small-Business-Financial-Segmentation.git
cd Small-Business-Financial-Segmentation

pip install -r requirements.txt

jupyter notebook 


📂 Project Files
small_business_financial_segmentation.ipynb – The main analysis notebook.

README.md – Project documentation.

Data_Dictionary or Features_Description_SCFP_2019.txt - Description of dataset features from the SCF 2019 survey.

📜 License
This project is open-source under the MIT License.
