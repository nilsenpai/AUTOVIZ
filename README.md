# AUTOVIZ
An automated Python pipeline that helps users upload a CSV file, explore the data, generate insightful visualizations, and receive AI-generated summaries using a Hugging Face Transformer model.

#📌 Features
📁 Upload any CSV file (e.g., Titanic, Iris, Heart Disease datasets)

#📊 Automatic data summarization:

Shape, columns, types

Missing values and duplicates

Statistical overview

#🧹 Data cleaning (drop duplicates, fill missing values)

#📈 Visualizations:

Histograms for numeric columns

Correlation heatmap

Bar charts for top categorical values

🤖 AI-generated insights using flan-t5-large from Hugging Face

✅ Works entirely in Google Colab (no local setup needed)

🚀 How It Works
Upload CSV: Use file picker to select and upload your CSV file.

Summarize Data: See column types, missing values, and stats.

Clean Data: Removes duplicates and fills missing values with "MISSING".

Visualize Data: Automatically shows histograms, bar charts, and heatmaps.

AI Insights: Generates natural-language summary of your dataset.

🖼️ Sample Visuals
Distribution of numerical columns

Top categories in text-based columns

Heatmap showing feature correlation

#🤖 Example AI Insight Output
Based on the dataset, most passengers who survived the Titanic disaster were women and children. Age distribution shows a heavy concentration around 20–30 years. There's a clear correlation between passenger class and survival. Missing values were found mostly in the 'Cabin' column.

#📂 Supported Datasets
You can use any dataset with a mix of numeric and categorical features. Recommended:

Titanic Dataset

Iris Dataset

Heart Disease Dataset

Student Performance

Supermarket Sales

Wine Quality

#📚 Requirements
Google Colab (Recommended)

Python 3

Libraries:

pandas

seaborn

matplotlib

transformers (Hugging Face)

#▶️ How to Run
Open in Google Colab

Copy-paste the entire script.

Run each cell step-by-step.

Upload your CSV when prompted.

Get insights instantly!
