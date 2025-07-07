# Analysis of Food Store Accessibility in Erie County, New York 

As an Erie County native, I have heard anecdotal relics of food deserts within the county, especially in the City of Buffalo. In this project, I have performed analysis on the available food stores, income, and population within the municipalities located in Erie County to explore trends based on location in the county and access to quality food stores.

Skills: 

Data preprocessing, Database Engineering with SQLite, Exploratory Data Analysis, Decision Trees, Dashboard Creation with Dash

Data:
- Individuals, ZIP Code Data from the Department of the Treasury ([link](https://catalog.data.gov/dataset/zip-code-data ))
- Retail Food Stores from the NY State Department of Agriculture and Markets ([link](https://data.ny.gov/Economic-Development/Retail-Food-Stores/9a8c-vfzj/about_data))

Methodology:
- Preprocessed and cleaned both datasets
- Built a database to store the clean data
- Analyzed trends using visualizations and statistical modeling
- Used a decision tree model to predict location
- Built a dashboard to present findings in an interactive way

Tools & Technologies:
- Programming Language: Python, SQLite
- Libraries: pandas, sqlite3, seaborn, matplotlib, sklearn, dash
- Software: Jupyter Notebook

Results & Evaluation:

My results focus on the differences between the City of Buffalo and the surrounding Suburbs in terms of income and the quality of food stores located in that area. When looking at the higher income brackets located in the Suburbs, the quality of food stores greatly increases. The zipcodes located within the City of Buffalo generally saw lower income and many more low-quality food stores, such as convenience stores or gas marts. Future analysis completed in the area would be best if opened into a multi-class problem, rather than a binary one. The rural areas on the outskirts of Erie County also face significantly lower incomes and fewer food stores than the more populated and bigger suburbs. 

Challenges & Learning:
- Improved preprocessing skills working with multiple datasets that both needed significant cleaning
- Gained experience building a dashboard directly inside Jupyter Notebook
