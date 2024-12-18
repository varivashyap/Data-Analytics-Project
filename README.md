# Data-Analytics-2024-Project (Stock Market Analysis Using Hierarchical Clustering)
Submitted By: Anishka Vaitla, Ramesh Kumar, Tarun Kumar Sahu, Varivashya Poladi, Yogangi Tiwari


Aim: To compare stock market network dynamics and resilience between the 2008 Financial Crisis and 2020 COVID-19 Crisis using network analysis.

Code Summary by Cell


Cell 1: Library Imports

Imports essential libraries for data analysis, visualisation, and network analysis
Sets up basic environment configurations

Cell 2: Data Download

Downloads stock data from Yahoo Finance
Creates directory structure
Handles ticker symbol cleaning and data formatting
Implements error handling and rate limiting

Cell 3: Data Organization

Arrange downloaded data by date.
Organises files into NASDAQ and NYSE directories
Processes and validates data
Creates standardized CSV format

Cell 4: Data Processing

Reads and combines data from multiple CSV files
Processes S&P 500 company list
Randomly samples 500 companies
Combines data from both periods

Cell 5: Price Processing

Processes stock price data
Calculates log returns
Handles missing values
Creates price matrix for network analysis

Cell 6: Network Analysis

Implements core network analysis functions
Creates correlation-based networks
Performs hierarchical clustering
Calculates network metrics

Cell 7: Time Window Analysis

Analyzes networks using sliding windows
Implements period analysis functions
Plots metric evolution over time
Compares different time periods

Cell 8: Cluster Quality Analysis

Calculates cluster quality metrics
Implements conductance calculations
Measures cluster stability
Analyses cluster coverage

Cell 9: Crisis Period Analysis

Analyses network characteristics during crises
Compares Financial Crisis vs COVID-19 period
Calculates crisis impact metrics
Visualizes crisis patterns

Cell 10: Advanced Network Analysis

Implements advanced network metrics
Analyses community structure
Calculates stability measures
Visualizes network evolution

Cell 11-20: Additional Analysis Cells

Cell 11-12: Network visualization and evolution patterns
Cell 13-14: Community structure analysis
Cell 15-16: Crisis pattern analysis
Cell 17-18: Network resilience analysis
Cell 19-20: Warning signals and comparative analysis

Cell 21: Final Analysis

Creates comprehensive visualizations
Generates summary reports
Compares crisis periods
Saves final results and documentation

Main Features:

Comprehensive stock market network analysis
Crisis period comparison (2008 vs 2020)
Multiple visualization techniques
Robust error handling
Detailed metric calculations
