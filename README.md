# T20 World Cup Analysis Project

This repository provides a comprehensive analysis of T20 World Cup cricket data using advanced analytics techniques. By leveraging Python for data processing and Power BI for visualizations, this project delivers actionable insights into player performances, match outcomes, and team strategies.

---

## Features

- **Data-Driven Insights**: Detailed analysis of batting, bowling, and match outcomes.
- **Interactive Dashboards**: Pre-built Power BI reports for exploration and decision-making.
- **Scalable Framework**: Reusable datasets and scripts for further customization.
- **Advanced Analytics**: DAX measures and calculated columns for deeper insights.

---

## Repository Structure

```plaintext
T20_worldcup_analysis_main/
│
├── Code Files
│   ├── t20dataprocessing.ipynb            # Jupyter notebook for data processing and analysis
│   ├── DAX Measures and Calculated columns.csv
│   ├── DAX Measures and Calculated columns.xlsx
│
├── Data
│   ├── JSON
│   │   ├── t20_wc_batting_summary.json    # Batting performance data
│   │   ├── t20_wc_bowling_summary.json    # Bowling performance data
│   │   ├── t20_wc_match_results.json      # Match results and metadata
│   │   ├── t20_wc_player_info.json        # Player information
│   │
│   ├── CSV
│       ├── dim_match_summary.csv          # Match summary dimension table
│       ├── dim_players.csv                # Players dimension table
│       ├── fact_bating_summary.csv        # Batting statistics fact table
│       ├── fact_bowling_summary.csv       # Bowling statistics fact table
│
├── Power BI Reports
│   ├── Cricket Best 11.pbix               # Visualization of the best-performing team
│   ├── Stage-2.pbix                       # Advanced Power BI analysis report
│   ├── Stage-3.pbix                       # Final stage of Power BI reporting
│   ├── t20_cric_1_power_query.pbix        # Data modeling and initial Power BI report
│
├── IDE Configurations
│   ├── .idea/                             # IntelliJ IDEA project settings

```

---

## Prerequisites

### Software Requirements
- **Python**: Ensure Python 3.8 or higher is installed with the following libraries:
  - `pandas`, `numpy`, `jupyter`, `matplotlib`
- **Power BI Desktop**: Required to open `.pbix` files.
- **Jupyter Notebook**: For running the Python analysis notebook.

### Dataset Availability
All required datasets are included in this repository (`JSON` and `CSV` formats). Ensure they are correctly loaded for analysis.

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/harshgupta1810/T20_worldcup_analysis
   cd T20_worldcup_analysis
   ```

2. **Set Up Python Environment**:
   - Install required Python libraries:
     ```bash
     pip install pandas numpy jupyter matplotlib
     ```
   - Open `t20dataprocessing.ipynb` to preprocess and analyze the data.

3. **Power BI Analysis**:
   - Open the `.pbix` files in Power BI Desktop to explore pre-built dashboards and insights.

4. **Modify DAX Measures**:
   - Enhance or customize reports using the provided DAX measures in `DAX Measures and Calculated columns.csv` or `.xlsx`.

---

## Key Insights

- Identify top-performing players and teams.
- Evaluate batting and bowling strategies.
- Uncover patterns in match results and tournament trends.

---

## Contribution Guidelines

We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

---

**Contact**: For questions or suggestions, feel free to open an issue or reach out to the repository maintainer.

**Disclaimer**: This project is for educational and analytical purposes only.

---

Explore, analyze, and enjoy T20 cricket like never before!

--- 

Let me know if you want any additional sections or modifications!
