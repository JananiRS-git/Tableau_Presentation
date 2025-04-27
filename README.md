Nashville Accident Report (Jan 2018 - April 2025) Overview


This repository contains the Nashville Accident Report dataset, which includes data on accidents that occurred in Nashville, Tennessee from January 2018 to April 2025. The dataset covers various details such as accident severity, weather conditions, and locations. Tableau visualizations have been created to provide insights into accident trends and patterns.

Files in this Repository
nashville_accidents.csv: The dataset containing the accident details.

Tableau Visualizations: Tableau workbook and visualizations summarizing key insights from the dataset.

README.md: This file with an overview and instructions.

Dataset Columns
Accident ID: Unique identifier for each accident.

Date: Date of the accident.

Time: Time of the accident (24-hour format).

Location: Street or coordinates of the accident.

Weather Condition: Weather at the time of the accident (e.g., clear, rainy).

Accident Type: Type of accident (e.g., rear-end, head-on).

Injuries: Number of injuries in the accident.

Fatalities: Number of fatalities in the accident.

Severity: Severity of the accident (e.g., minor, major, fatal).

Other Columns: Additional data such as road conditions, traffic control, etc.

Usage
You can use this dataset for:

Analyzing accident trends over time.

Mapping accident locations and identifying hotspots.

Investigating the relationship between weather, road conditions, and accident severity.

Example Code
Here is a simple code to load the dataset using Python:

python
Copy
Edit
import pandas as pd

# Load the dataset
df = pd.read_csv('nashville_accidents.csv')

# Display the first few rows of the dataset
print(df.head())
Tableau Visualizations
Tableau visualizations have been created to showcase:

Accident trends over time.

Accident severity by weather and road conditions.

Geographic distribution of accidents across Nashville.

You can open the Tableau workbook to interact with these visualizations.

How to Run
Clone this repository:
git clone https://github.com/yourusername/nashville-accidents.git

Install the required dependencies:

bash
Copy
Edit
pip install pandas matplotlib
Load and analyze the dataset in your preferred Python environment.

Open the Tableau workbook file to explore the visualizations.

License
This dataset is available for use under the Kaggle License.

Contact
For more information, please reach out to:

Your Name
Email: mail2rsjanani@gmail.com


linkedin: https://www.linkedin.com/in/janani-rs-?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
