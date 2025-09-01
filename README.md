Global Student Migration & Higher Education Trends (2019–2023)

This dataset captures international student migration patterns over the last five years (2019–2023). It includes details such as countries of origin, destination countries, universities, courses, scholarships, visa trends, placement outcomes, and expected salaries.

The data is synthetic but realistic, generated for educational, research, and analytical purposes.

📌 Key Features

Covers 10 major destination countries with top universities and cities.

Tracks student migration patterns from multiple source countries.

Includes data on:

🎓 Popular fields of study & courses

🌏 Country-wise migration trends

💰 Scholarships & visa approvals

💼 Placement success rates & salary outcomes

🔎 Possible Use Cases

Identify most popular study destinations globally.

Analyze trending fields & courses in higher education.

Study scholarship distribution and visa success trends.

Explore graduate employability & salary expectations.

Build dashboards & visualizations for education analytics.

📂 Dataset

Source: Kaggle – Global Student Migration and Higher Education Trends

Format: CSV

Size: ~ MB (varies depending on export)

🚀 Getting Started
# Clone this repository
git clone https://github.com/yourusername/global-student-migration.git

# Navigate into the project
cd global-student-migration

# (Optional) Create virtual environment and install packages
pip install -r requirements.txt


Example usage in Python:

import pandas as pd

# Load dataset
df = pd.read_csv("global_student_migration.csv")

# Preview data
print(df.head())

# Analyze top 5 destination countries
print(df['Destination_Country'].value_counts().head())

📊 Sample Visualization

Here’s a quick example of how to visualize the top 10 destination countries:

import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("global_student_migration.csv")

# Count top destination countries
top_destinations = df['Destination_Country'].value_counts().head(10)

# Plot
plt.figure(figsize=(10,6))
top_destinations.plot(kind='bar')
plt.title("Top 10 Student Destination Countries (2019–2023)")
plt.xlabel("Destination Country")
plt.ylabel("Number of Students")
plt.xticks(rotation=45)
plt.show()


This will generate a bar chart showing the most popular study destinations.

