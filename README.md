# Analysis of Food Store Accessibility in Erie County, NY

As an Erie County native, I have heard anecdotal reports of food deserts within the county, especially in the City of Buffalo. In this project, I have performed analysis on the available food stores, income, and population within the municipalities located in Erie County to explore trends based on location in the county and access to quality food stores.

Skills: 

Data Preprocessing, Database Engineering, Exploratory Data Analysis, Decision Trees, Dashboard Development

Data:
- Individuals, ZIP Code Data from the Department of the Treasury ([link](https://catalog.data.gov/dataset/zip-code-data ))
- Retail Food Stores from the NY State Department of Agriculture and Markets ([link](https://data.ny.gov/Economic-Development/Retail-Food-Stores/9a8c-vfzj/about_data))

Methodology:
- Preprocessed and cleaned both datasets
- Built a structured SQLite database to store and manage cleaned data
- Conducted exploratory analysis using visualizations and statistical techniques
- Applied a decision tree classifier to explore predictive trends by location
- Created an interactive dashboard to present findings

Tools & Technologies:
- Programming Language: Python, SQL
- Libraries: pandas, sqlite3, seaborn, matplotlib, sklearn, dash
- Software: Jupyter Notebook

Results & Evaluation:

The analysis revealed clear differences in income and food store quality between the City of Buffalo and its surrounding suburbs. Higher-income zipcodes in the suburbs tended to have greater access to high-quality food stores, while zipcodes within Buffalo saw lower incomes and a higher concentration of lower-quality food stores, such as gas marts and convenience stores. Rural areas at the edges of Erie County also showed lower income levels and limited access to food stores. Based on these findings, future work would benefit from framing the classification task as a multi-class problem rather than binary, to better capture the nuanced differences between urban, suburban, and rural zones.

Challenges & Learning:
- Strengthened preprocessing skills while working with multiple messy datasets
- Gained hands-on experience with dashboard creation directly within Jupyter using Dash
