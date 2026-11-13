# TrendPulse – Part 1: Python Foundations & Data Structures

## Project Overview
TrendPulse analyzes trending YouTube video statistics from the United States (US), Great Britain (GB), and India (IN). This part focuses on Python fundamentals, data structures, data cleaning, and video classification.

## Dataset
The project uses the provided YouTube Trending Video Statistics dataset.

Countries included:
- United States (US)
- Great Britain (GB)
- India (IN)

Total records loaded: **46,230**

## Folder Structure
```text
part1_python_foundations/
├── data/
│   ├── USvideos.csv
│   ├── GBvideos.csv
│   ├── INvideos.csv
│   └── categories.csv
├── trendpulse_part1.ipynb
├── README.md
└── requirements.txt
```

## Technologies Used
- Python
- Pandas
- Python built-in data structures
- Google Colab

## Key Tasks Completed
1. Loaded CSV datasets using Pandas.
2. Converted DataFrame records into Python dictionaries.
3. Cleaned numeric, Boolean, and date/time values.
4. Used lists, tuples, sets, and dictionaries.
5. Compared unique video IDs across countries.
6. Identified the top 15 channels.
7. Created country-wise category summaries.
8. Demonstrated Python scope and functions.
9. Used for loops, while loops, break, continue, and range().
10. Classified videos using views, like ratios, and engagement settings.
11. Refactored repeated counting logic into a reusable function.

## Data Cleaning
- Missing or invalid numeric values were replaced with 0.
- Boolean values were converted to True or False.
- Trending dates and publish times were converted into Python date/time objects.
- No records were removed.

## Video Classification
Videos were classified into:
- Viral Hit
- Steady Performer
- Divisive
- Low Engagement
- Unrated

The classification uses views, like ratios, and comments/ratings settings.

## How to Run
1. Install the required dependency:
   `pip install -r requirements.txt`
2. Open `trendpulse_part1.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure the four CSV files are inside the `data` folder.
4. Run all notebook cells from top to bottom.

## Dataset Source
Dataset provided as part of the TrendPulse mini project assignment.
