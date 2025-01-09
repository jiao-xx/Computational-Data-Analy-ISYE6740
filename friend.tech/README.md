# Project Title: Friend.tech Social Network Analysis

## Overview
This project leverages the Friend.tech platform and its Python package to perform a comprehensive social analysis. The analysis involves data collection, community detection, key holder analysis, and financial tracking, providing actionable insights into user behavior, community structures, and financial flows within the Friend.tech ecosystem.

## Key Features
- **Data Collection**: Utilized the Friend.tech API and its Python package to gather comprehensive data on user activities, trades, and share ownership.
- **Network Analysis**: Explored social network structures by analyzing key holders, distributors, and their relationships using graph theory.
- **Community Detection**: Implemented clustering techniques to identify communities and influential users within the platform.
- **Financial Analysis**: Tracked financial flows, including share buy/sell prices, fees, and supply metrics, to understand market dynamics.
- **Interactive Reporting**: Designed detailed visualizations to represent user interactions, community structures, and financial trends.

## Tools and Technologies
- **Friend.tech Python Package**: To interact with the platform APIs and collect data efficiently.
- **Python Libraries**: Pandas, NetworkX, Matplotlib, Seaborn.
- **Jupyter Notebook**: For data exploration and analysis workflows.
- **Graph Theory**: For network analysis and community detection.
- **Visualization**: For creating interactive charts and network graphs.

## Workflow
1. **Data Collection**:
   - Used Friend.tech's Python package to fetch data on global activities, user trades, share prices, and holders.

2. **Network Analysis**:
   - Built a graph representation of the data to analyze relationships between key holders and distributors.

3. **Community Detection**:
   - Applied clustering algorithms to identify key communities and influencers.

4. **Financial Tracking**:
   - Extracted buy/sell prices, fees, and supply metrics to analyze market trends and dynamics.

5. **Visualization**:
   - Generated network graphs, financial trend charts, and interactive dashboards for actionable insights.
   - [Presentation](https://github.com/jiao-xx/Computational-Data-Analy-ISYE6740/blob/main/friend.tech/Report%20Poster.pdf)

## Results
The project provides:
- Insights into key influencers and community structures within the platform.
- Analysis of financial dynamics such as pricing trends and share supply changes.
- Comprehensive network graphs illustrating user relationships and trade flows.

### Example Outputs:
- **Network Graphs**: Visualizing key holders and their influence.
- **Financial Trends**: Tracking buy/sell prices and fees over time.
- **Community Clusters**: Highlighting social groups and influencers.

## Repository Structure
- **1. Ft_DataCollection&Network.ipynb**: Notebook for data collection and initial network analysis.
- **2. Ft_holders&distributors.ipynb**: Notebook for analyzing key holders and distributors.
- **3. Ft_community.ipynb**: Notebook for community detection and analysis.
- **4. Ft_financials.ipynb**: Notebook for financial tracking and market analysis.
- **README.md**: Documentation for the Friend.tech Python package.

## Future Enhancements
- Integrate real-time data updates for continuous analysis.
- Expand financial tracking with predictive modeling for price trends.
- Enhance community detection with advanced clustering algorithms.
