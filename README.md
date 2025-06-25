# MLB-Whiff-Analysis
# Baseball Whiff Pitch Analysis (2025)

## Overview
This project analyzes whiff pitches (swinging strikes) in the 2025 MLB season using Statcast data, conducted as of June 25, 2025. It explores pitch categories, locations, release speeds, top pitchers, and player-specific performance (e.g., Kevin Gausman) through data visualization and statistical analysis. The project leverages Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `pybaseball` to process data and create insightful plots, presented in a single combined figure.

## Features
- **Data Collection**: Retrieves Statcast data for March 28, 2025, to June 23, 2025.
- **Data Cleaning**: Filters and prepares whiff pitch data.
- **Exploratory Data Analysis (EDA)**:
  - Whiff pitches by pitch category (bar plot).
  - Heatmap of whiff pitch locations.
  - Boxplot of release speeds by pitch category.
  - Top 10 pitchers by whiff rate (bar plot).
  - Player-specific analysis (e.g., Kevin Gausman’s whiff pitch locations).
- **Visualization**: Combines all plots into a single figure using subplots.
- **Output**: Generates and saves the analysis as a PNG file locally.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `pybaseball` for Statcast data access
- **Environment**: Any Python environment (e.g., local Jupyter Notebook, VS Code, or terminal)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Baseball-Whiff-Pitch-Analysis-2025.git
   cd Baseball-Whiff-Pitch-Analysis-2025
