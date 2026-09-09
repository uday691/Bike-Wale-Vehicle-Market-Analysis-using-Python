dme · MD
🏍️ Bike Wale – Vehicle Market Analysis using Python

A data analysis project exploring the used/new two-wheeler (bike & scooter) market using data scraped/sourced from BikeWale. The project covers data cleaning, exploratory data analysis (EDA), and visualization to uncover trends in pricing, brand popularity, mileage, and regional demand.

📌 Project Overview

This project analyzes vehicle listing data to answer questions such as:

Which brands and models dominate the market?
How do prices vary by brand, city, fuel type, or engine capacity?
What is the relationship between mileage, age, and resale price?
Which cities/regions show the highest listing activity?
📂 Repository Structure
Bike-Wale-Vehicle-Market-Analysis-using-Python/
│
├── data/                   # Raw and/or cleaned dataset(s)
├── notebooks/              # Jupyter notebooks with EDA and analysis
├── images/                 # Charts/plots exported from the analysis
├── src/                    # (optional) Python scripts for scraping/cleaning
├── requirements.txt        # Python dependencies
└── README.md

Update this section to match your actual folder/file names.

🧰 Tech Stack
Python 3
Pandas – data manipulation and cleaning
NumPy – numerical operations
Matplotlib / Seaborn – data visualization
Jupyter Notebook – analysis workflow
🔍 Approach
Data Collection – Vehicle listing data sourced from BikeWale.
Data Cleaning – Handled missing values, removed duplicates, standardized columns (price, mileage, year, brand, model, city, fuel type).
Exploratory Data Analysis (EDA)
Distribution of prices across brands and cities
Correlation between age, mileage, and price
Popularity ranking of brands/models
Outlier detection using boxplots/IQR
Visualization – Bar charts, histograms, scatter plots, and heatmaps to communicate insights.
📊 Key Insights
(Add 3–5 bullet points summarizing your top findings, e.g. "Bikes under 5 years old retain over 70% of their resale value.")
(e.g. "Royal Enfield and Honda listings dominate the mid-range price segment.")
(e.g. "Metro cities show significantly higher listing volume than tier-2 cities.")
🚀 Getting Started
Prerequisites
bash
pip install -r requirements.txt
Running the Analysis
bash
git clone https://github.com/uday691/Bike-Wale-Vehicle-Market-Analysis-using-Python.git
cd Bike-Wale-Vehicle-Market-Analysis-using-Python
jupyter notebook

Open the main notebook and run all cells.

📈 Sample Visualizations

(Add screenshots of your charts here, e.g.)

![Price Distribution](images/price_distribution.png)
![Brand Popularity](images/brand_popularity.png)
🙌 Acknowledgements
Data sourced from BikeWale
Built as a personal/portfolio data analysis project
📄 License

This project is licensed under the MIT License — feel free to use and modify with attribution.
