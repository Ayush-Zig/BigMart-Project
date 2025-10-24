BigMart-Project

Big Mart Sales Prediction Project is a machine learning project aimed at predicting the sales of products across different outlets of Big Mart. Using historical sales data and features like item type, outlet location, and visibility, this project builds predictive models to estimate product sales and help in inventory planning and business decisions.

Key Features:

• Data cleaning and preprocessing

• Handling missing values and zero entries

• Feature engineering for better model performance

• Exploratory data analysis (EDA) for insights

• Machine learning models to predict sales (e.g., Linear Regression, Random Forest)

• Evaluation of model accuracy using appropriate metrics

Tools & Technologies Used:

• Python (pandas, numpy, scikit-learn, matplotlib, seaborn)

• Jupyter Notebook for experimentation

• Git & GitHub for version control

Model Performance (R² Scores for XGBoost Regressor):

• Train R²: 0.86

• Test R²: 0.52

Objective:
To accurately predict product sales at Big Mart outlets to assist in inventory management, optimize stock levels, and improve overall business efficiency.




Importing The Dependencies -------------------->


<img width="1497" height="861" alt="Screenshot 2025-10-24 142726" src="https://github.com/user-attachments/assets/1507f8d9-876c-4c36-a00b-beeeebc0d5a4" />


<img width="1362" height="590" alt="Screenshot 2025-10-24 143718" src="https://github.com/user-attachments/assets/d5c9a24f-8406-435f-ae90-c1acf23b2b3c" />


<img width="1447" height="717" alt="Screenshot 2025-10-24 143011" src="https://github.com/user-attachments/assets/4480c875-d6dd-4823-ab95-0b31c2684c18" />


<img width="1457" height="718" alt="Screenshot 2025-10-24 143751" src="https://github.com/user-attachments/assets/fea54a10-d2d6-4f9d-acac-48fdf5fb0aed" />


DATA ANALYSIS --------------------------->

Item Weight Distribution

<img width="731" height="725" alt="Screenshot 2025-10-24 143443" src="https://github.com/user-attachments/assets/2278c4a8-4ace-4fb6-b1d3-6d7eb62483b6" />

Item Visibility Distribution

<img width="817" height="741" alt="Screenshot 2025-10-24 143518" src="https://github.com/user-attachments/assets/9277ce8f-2c20-442b-9dec-0eb70a82debe" />

Item MRP Distribution 


<img width="737" height="718" alt="Screenshot 2025-10-24 143601" src="https://github.com/user-attachments/assets/5bd5f282-4473-429c-8073-0135587a4718" />

Item Outlet Sales Distribution 

<img width="706" height="712" alt="Screenshot 2025-10-24 143641" src="https://github.com/user-attachments/assets/102c458a-7268-49a9-8c0b-61ad459dd377" />

Outlet Establishment Distribution 

<img width="810" height="723" alt="Screenshot 2025-10-24 143355" src="https://github.com/user-attachments/assets/58bbc2c2-7438-4c1e-85da-6cb9e41996a6" />

Item Type Distribution

<img width="1440" height="441" alt="Screenshot 2025-10-24 143115" src="https://github.com/user-attachments/assets/c9b44102-f502-41c5-9405-a062e1b608b1" />


Converting To String for Outlet Size

<img width="1243" height="482" alt="Screenshot 2025-10-24 143829" src="https://github.com/user-attachments/assets/ec9055c2-96cd-4d3f-b853-d341602043c5" />


Outlet Size Distribution

<img width="875" height="720" alt="Screenshot 2025-10-24 143907" src="https://github.com/user-attachments/assets/d0b5caf8-17e8-4d58-a4c0-28dfa31767b6" />

Data Preprocessing 

<img width="1478" height="692" alt="Screenshot 2025-10-24 143935" src="https://github.com/user-attachments/assets/57e98ae6-1365-4a84-b82f-ca8e608c0607" />


<img width="1437" height="581" alt="Screenshot 2025-10-24 144002" src="https://github.com/user-attachments/assets/ee9fed6f-6cbf-4720-a6ee-68aeb563afec" />


Splitting Features 

<img width="1465" height="637" alt="Screenshot 2025-10-24 144033" src="https://github.com/user-attachments/assets/f5efeef8-1060-4581-8ab7-63f4d22c55a0" />

Splitting Data Into Training and Test Data


<img width="1462" height="640" alt="Screenshot 2025-10-24 144109" src="https://github.com/user-attachments/assets/57191091-edb1-440a-8d88-fa46e747c297" />


Evaluation 

<img width="1437" height="623" alt="Screenshot 2025-10-24 144135" src="https://github.com/user-attachments/assets/1f6352f1-bfa4-4de9-889a-d3574909b728" />


