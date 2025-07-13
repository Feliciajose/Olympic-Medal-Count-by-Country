#  Olympic Medal Count by Country

This project explores Olympic medal trends across different countries, sports, and years using real-world data from [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).

##  Project Highlights

- Country-wise medal performance over Olympic years
- Medal distribution trends by year and sport
- Heatmap of medal dominance
- Medals per capita (population-based analysis)
- Interactive visualizations (Matplotlib, Seaborn)

##  Dataset

- **athlete_events.csv** – Olympic athlete events from 1896 to 2016
- **noc_regions.csv** – National Olympic Committee (NOC) region mappings
- **country_population.csv** – (Optional) For medals per capita

##  Project Structure

```
├── data/
│   ├── athlete_events.csv
│   ├── noc_regions.csv
│   └── country_population.csv
├── Olympic_Medal_Count_by_Country.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

##  Exploratory Data Analysis

-  Medal trends by year
-  Country vs year heatmap
-  Top 10 countries by medal count
-  Most successful sports
-  Medals per million population

##  Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

##  Run the Notebook

```bash
jupyter notebook Olympic_Medal_Count_by_Country.ipynb
```

##  Sample Visualizations

- Bar charts of medal counts
- Line plots for trends
- Heatmaps for dominance

##  Acknowledgements

- Dataset: [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
