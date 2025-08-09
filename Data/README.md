☕ Coffee Data – Anonymized Dataset for Exploratory Analysis
This repository contains an anonymized dataset on domestic coffee consumption by country, type, and year. The original data has been transformed to protect confidentiality while preserving its analytical value for exploratory analysis, statistical modeling, and data visualization.

📁 Available File
- :
Ready-to-use dataset compatible with Python, R, Power BI, and other analytical tools.

📊 Dataset Description
- Country: Generic country identifier (e.g., Country 1, Country 2...)
- Coffee type: Type of coffee (e.g., Arabica, Robusta)
- Year: Year of consumption (format YYYY or YYYY/YY) 
- Total_domestic_consumption: Annual domestic consumption (scaled using a constant multiplier) 
- Continent: Continent assigned via geolocation using pycountry_convert 

🔐 Data Transformations
- Real country names were replaced with generic labels.
- Consumption values were scaled using a constant multiplier to preserve proportions without revealing actual figures.
- The Continent column was added using the pycountry_convert library, as it was not included in the original dataset.

🐍 How to Load the Dataset in Pytho

import pandas as pd
url = "https://raw.githubusercontent.com/Jhonarsa/Coffee-data/refs/heads/main/Data/Coffee%20data.csv"
df = pd.read_csv(url)
print(df.head())

✍️ Suggested Citation
Salina Alfaro, J.D. (2025). Coffee Data – Anonymized Dataset for Exploratory Analysis. GitHub repository: https://github.com/Jhonarsa/Coffee-data


