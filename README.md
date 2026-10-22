# 💻 Laptop Price Prediction Using Machine Learning

📌 **Project Description**
This project presents an end-to-end machine learning solution developed during my Machine Learning Internship at Prinston Smart Engineers. It estimates laptop prices based on technical specifications by utilizing a full regression pipeline built in Python—covering data cleaning, exploratory data analysis, feature engineering, performance comparison of multiple models, and web deployment.

🎯 **Objectives**
- Build regression models to predict laptop prices from technical specifications
- Analyze how features such as RAM, brand, weight, IPS display, and touchscreen relate to pricing
- Clean raw data and engineer useful features like CPU brand, Touchscreen, and IPS flags
- Compare Linear Regression, Decision Tree, and Random Forest models using $R^2$ score and MAE
- Deploy the trained model through an interactive Gradio web interface

📊 **Tools & Technologies Used**
- Python, Pandas, & NumPy (Data processing, cleaning, and manipulation)
- Matplotlib & Seaborn (Exploratory Data Analysis and visual charts)
- Scikit-learn (Pipelines, one-hot encoding, model training, and evaluation)
- Pickle (Model serialization)
- Gradio (Interactive web interface development)
- Google Colab (Development environment)

🗂 **Dataset Details**
The dataset contains 1,303 laptop records with 11 attributes, including company name, type, screen size, resolution, CPU, RAM, storage memory, GPU, operating system, weight, and price.

📈 **Model Performance & Comparison**
| Model | $R^2$ Score | Mean Absolute Error (MAE) |
| :--- | :--- | :--- |
| **Linear Regression** | **0.823** | — |
| **Random Forest (100 Trees)** | **0.786** | **₹10,785** |
| **Decision Tree** | **0.710** | — |

🧹 **Data Cleaning & Feature Engineering Steps**
- Converted text-based RAM and Weight attributes into proper numeric values
- Engineered new features including `Cpu_brand`, `Touchscreen`, and `IPS` from raw text columns
- Applied one-hot encoding via Scikit-learn ColumnTransformers inside a robust Pipeline
- Split data into 80/20 training and test sets

🔍 **Key Insights**
- **RAM Impact**: RAM has the strongest positive relationship with price (correlation of $\sim 0.74$), with average pricing scaling up steadily from 2GB to 64GB.
- **Brand Positioning**: Premium brands like Razer, LG, MSI, Apple, Microsoft, and Google exhibit the highest average price tiers.
- **Display & Build**: IPS displays and touchscreens offer moderate price premiums, whereas screen size alone displays minimal linear correlation with price.

📌 **Conclusion**
The Laptop Price Prediction project demonstrates a production-style machine learning pipeline from raw data to a deployed web estimator[cite: 9]. It provides a reliable tool for buyers, e-commerce platforms, and manufacturers to evaluate pricing logic based on core specifications.

👩‍💻 **Created By**
Mounika M  
Final Year BCA Student  
St. Francis College, Bangalore

📎 **Project Type**
Industry Internship Project (Prinston Smart Engineers) / Machine Learning & Data Analytics
