# Advanced Cricket Match Analysis

This project provides a comprehensive analysis of cricket match data using Python. It fetches commentary data from Cricbuzz, parses it to extract ball-by-ball details, and generates various visualizations to analyze the performance of both teams.

## Features

-   **Data Fetching**: Automatically fetches match commentary for both innings from Cricbuzz.
-   **Data Parsing**: Extracts detailed information including runs, extras, wickets, and real player names.
-   **Visualizations**: Generates a suite of charts to visualize match dynamics:
    -   Manhattan Charts (Innings 1 & 2)
    -   Worm Chart (Cumulative Runs Comparison)
    -   Run Rate Progression
    -   Run Rate Distribution
    -   Fall of Wickets
    -   Extras Breakdown
    -   Batsman Contribution
    -   Bowler Performance
    -   Boundary Analysis

## Visualizations

### Manhattan Charts
Visualizes runs scored per over for each innings.

![Manhattan Chart Innings 1](images/manhattan_innings_1.png)

![Manhattan Chart Innings 2](images/manhattan_innings_2.png)

### Worm Chart
Compares the cumulative runs of both teams throughout the match.

![Worm Chart](images/worm_chart.png)

### Run Rate Progression
Tracks the run rate fluctuation over the course of the match.

![Run Rate Progression](images/run_rate_progression.png)

## Setup

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
2.  **Run Analysis**:
    Open `match_analysis_graphs.ipynb` in Jupyter Notebook or JupyterLab and run all cells.

## Requirements

-   Python 3.x
-   pandas
-   matplotlib
-   seaborn
-   requests
