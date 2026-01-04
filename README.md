# amazon-reviews-eda
Amazon Reviews EDA - README Template
This project analyzes Amazon customer reviews using Jupyter notebooks in VSCode. It covers exploratory data analysis (EDA) with pandas, visualizations via matplotlib/seaborn, and key insights from review datasets.
​

Project Structure
text
amazon-reviews-eda/
├── README.md                 # This file
├── amazon_reviews.ipynb      # Main EDA notebook
├── data/                     # Raw/processed CSV files
├── outputs/                  # Charts, cleaned data
└── requirements.txt          # Dependencies
Quick Start (VSCode + Jupyter)
Clone repo: git clone https://github.com/JeyaAgastink/amazon-reviews-eda.git

Open in VSCode: code amazon-reviews-eda

Install extensions: Jupyter, Python, Jupyter Renderers

Select Python kernel (top-right in notebook)

Run all: Ctrl+F or Run All button

Requirements (run in VSCode terminal):

bash
pip install pandas numpy matplotlib seaborn jupyter ipykernel
Notebook Workflow
Data Loading: Reads CSV review files (products, ratings, text)

EDA Steps: Missing values, distributions, word clouds, sentiment trends

Visuals: Rating histograms, top products, review length analysis

Outputs: Save charts to outputs/ folder

Expected runtime: ~2-5 minutes on standard laptop.

Key Findings (Update After Running)
 Top 10 products by review volume

 Average rating distribution

 Sentiment correlation with verified purchase

 Most common review keywords

Troubleshooting
"Unable to render code block": Reload VSCode window (Ctrl+Shift+P → "Developer: Reload Window")

Kernel issues: pip install --upgrade ipykernel, restart kernel

Push errors: Check proxy (git config --global --unset http.proxy)

Next Steps
Add ML model for sentiment classification

Deploy Streamlit dashboard

Real-time review scraper

Built with VSCode Jupyter for your amazon-reviews-eda project. Edit findings section after running notebook!
