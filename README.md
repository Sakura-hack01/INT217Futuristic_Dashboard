# INT217Futuristic_Dashboard
# Tech Adoption PivotTable Dashboard

## Overview
This Excel file (`PivotTech.xlsx`) features a PivotTable analyzing global technology adoption trends from 2030 to 2040. Built with standard Excel features, it offers dynamic filtering and insights into metrics like `Tech_Adoption_Index` across countries, ideal for data enthusiasts and analysts.

## Dataset
The PivotTable uses a synthetic dataset embedded in the "RawData" sheet, including:
- `Year` (2030–2040)
- `Country`
- `Tech_Adoption_Index` (0–100)
- `Climate_Risk_Level` (Low, Medium, High)
- Other metrics (e.g., `AI_Employment_Percent`)

## Features
- **Dynamic PivotTable**: Summarizes `Tech_Adoption_Index` by `Country` and `Year`.
- **Interactive Filters**: Slicers for `Country`, `Year`, `Climate_Risk_Level`, and `Tech_Category` (High/Medium/Low).
- **Calculated Metrics**:
  - `Tech_Impact_Score`: Tech adoption × digital wellness.
  - `AI_Economic_Impact`: AI jobs + crypto GDP.
- **No VBA/Add-ins**: Uses only standard Excel functionality.

## File Structure
- **PivotTech.xlsx**:
  - **PivotTech** sheet: Main PivotTable with filters.
  - **RawData** sheet: Source data table (`DataTable`).

## Requirements
- Microsoft Excel 2016 or later (Windows/Mac).
- Git LFS for downloading (file >25 MB).

## Setup Instructions
1. **Clone or Download**:
   - Install [Git](https://git-scm.com/downloads) and [Git LFS](https://git-lfs.github.com/).
   - Clone the repository:
     ```bash
     git clone https://github.com/yourusername/PivotTechDashboard.git
