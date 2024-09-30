# CVE Analysis Dashboard

This project aims to provide insights into the landscape of Common Vulnerabilities and Exposures (CVEs) through interactive data visualizations. The dashboard leverages the CVE dataset from [source of the dataset] to uncover trends, risks, and areas for improvement in cybersecurity practices.

## Features

* **CVE Trend Over Time:** Visualizes the number of CVEs published each year, revealing trends and potential spikes in vulnerability disclosures.
* **CVSS Score Distribution:** Displays the distribution of CVSS scores, helping understand the severity of vulnerabilities.
* **Top CWE Names:** Showcases the most common CWE names, highlighting prevalent types of weaknesses.
* **Top Vendors:** Identifies the vendors with the highest number of associated CVEs, indicating potential vendor risk.
* **Top Products:** Presents the products most affected by vulnerabilities, assisting in prioritizing patching and security measures.

## Data Source

The project utilizes the CVE dataset from [source of the dataset]. This dataset contains information about CVEs, including their publication dates, severity scores (CVSS), associated weaknesses (CWEs), and the affected vendors and products.

## Technologies Used

* **Python:** Used for data analysis and visualization.
* **Pandas:** A powerful library for data manipulation and analysis.
* **Altair:** A declarative visualization library for creating interactive charts.

Visualizations
The project generates the following visualizations:

cve_trend_over_time.json
cvss_score_distribution.json
top_cwe_names.json
top_vendors.json
top_products.json
You can view these interactive visualizations using a tool like the Altair Viewer.

Future Enhancements
Interactive Dashboard: Integrate the visualizations into a single, interactive dashboard using a framework like Streamlit or Dash.
Real-time Data: Incorporate real-time CVE data feeds to keep the dashboard up-to-date.
Predictive Analytics: Explore machine learning models to predict future CVE trends or identify high-risk vulnerabilities.
User Customization: Allow users to filter and drill down into the data based on their specific interests.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project.

License
This project is licensed under the MIT License.   
