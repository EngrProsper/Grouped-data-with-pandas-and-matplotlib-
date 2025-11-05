# Grouped Data Analysis with Pandas and Matplotlib

## Description

This project analyzes sales data by grouping it by region using `pandas`, visualizes results with a dual-axis `matplotlib` chart (Revenue vs. Units Sold), and exports to an Excel file with `openpyxl`. It helps analyze sales data for better data-driven decision-making.

## Features

- Load and read CSV sales data
- Group data by **Region** with aggregated **Revenue** and **Units Sold**
- Create dual-axis bar chart with customer age group annotations
- Export grouped data and embedded chart to Excel
- Professional chart formatting with legends and labels


## Tech Stack

- **Python 3.8+**
- **pandas** - Data manipulation and grouping
- **numpy** - Numerical operations
- **matplotlib** - Data visualization
- **openpyxl** - Excel file generation

## Installation

Install the required dependencies:

```
!pip install pandas numpy matplotlib openpyxl

```

## Usage

-Clone the repository:
git clone https://github.com/EngrProsper/Grouped-data-with-pandas-and-matplotlib.git
cd Grouped-data-with-pandas-and-matplotlib

-Open the notebook:
jupyter notebook "Data_grouping_with_pandas_and_visualization_with_matplotlib.ipynb"
Or open in Google Colab
Upload freelance_project.csv when prompted (or update the file path)

-Run all cells to generate:
Grouped data
Chart (revenue_units_chart.JPG)
Excel file (project_grouped_data.xlsx)

## Folder Structure
.
├── Data_grouping_with_pandas_and_visualization_with_matplotlib.ipynb
├── LICENSE
├── README.md
├── project_grouped_data.xlsx
└── revenue_units_chart.JPG

## Results

The script groups sales data by Region and calculates total Revenue and Units Sold


### Sample excel file Output

![excel grouped table Screenshot](https://github.com/user-attachments/assets/bb40d21f-74ce-4f08-b241-fa0463877b92)

### Excel file created at: 
project_grouped_data.xlsx

## Visualization

### Demo

![ Revenue & Units sold bar chart Screenshot](https://github.com/user-attachments/assets/9fad8160-9264-47ce-93b4-b14c22604387)


*Dual-axis bar chart showing Revenue (red) and Units Sold (blue) by region with age group annotations*



### The generated chart displays:

-Red bars: Revenue (USD) on the left y-axis

-Blue bars: Units Sold on the right y-axis

-Customer age group annotations above each region's bars

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created by Prosper Ochuko as a weekly learning project for freelancing.

GitHub Profile · Open an Issue
