Overview
This repository contains a comprehensive analysis of the T20 World Cup matches, focusing on match results and player performances. The analysis is conducted using Python, leveraging libraries such as Pandas and NumPy for data manipulation and analysis.
Repository Structure
data/: Contains JSON files with match results and batting summaries.
notebooks/: Jupyter notebooks for data processing and analysis.
results/: Output CSV files generated from the analysis.
Installation
To run the analysis, ensure you have Python 3.x installed along with the following packages:
bash
pip install pandas numpy

Usage
Load Data: The match results and batting summaries are loaded from JSON files.
python
import pandas as pd
import json

with open('t20_wc_match_results.json') as f:
    data = json.load(f)
dfmatch = pd.DataFrame(data[0]['matchSummary'])

Data Processing: The match results are processed to create a summary DataFrame.
python
dfmatch.rename({'scorecard': 'match_id'}, axis=1, inplace=True)

Analysis: Perform various analyses such as finding the winner of each match and summarizing player performances.
python
df_batting = pd.DataFrame(all_records)
df_batting['out/not_out'] = df_batting.dismissal.apply(lambda x: "out" if len(x) > 0 else "not_out")

Export Results: The processed data can be exported to CSV for further use.
python
dfmatch.to_csv('dim_match_summary.csv', index=False)

Example Data
The following is an example of the match results processed in this analysis:
team1	team2	winner	margin	ground	matchDate
Namibia	Sri Lanka	Namibia	55 runs	Geelong	Oct 16, 2022
Netherlands	U.A.E.	Netherlands	3 wickets	Geelong	Oct 16, 2022
Scotland	West Indies	Scotland	42 runs	Hobart	Oct 17, 2022
Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
License
This project is licensed under the MIT License - see the LICENSE file for details.
For more details, visit the project on GitHub: T20 World Cup Analysis.
