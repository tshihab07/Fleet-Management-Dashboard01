# Fleet Management Dashboard

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tools](#tools)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Fleet Management Dashboard is a data-driven tool created in Power BI with Python scripts and Excel data inputs. It provides an interactive way to monitor fleet performance metrics, driver insights, fuel efficiency, and cost analysis, helping fleet managers optimize operations and reduce costs.

## Features

**High-Level KPIs:** Overview of total drivers, total kilometers traveled, total liters consumed, and cost breakdowns (fixed, maintenance, and fuel).
**Driver-Specific Insights:** Detailed metrics for each driver, including total drives, average fuel efficiency, fuel consumption per kilometer, cost per kilometer, and average speed.
**Cost Analysis:** Breakdown of maintenance, fuel, and fixed costs for easy assessment.
**Time-Series Data Visualization:** Line graph for tracking total kilometers traveled over time.
**Filter Functionality:** Filter data by driver and other criteria to analyze specific segments.

## Tools

**Power BI:** For creating interactive visualizations and dashboard layouts.
**Python:** Used for data processing and transformations before loading data into Power BI.
**Excel:** Primary data source for the dashboard, containing fleet and driver information.

The data for this dashboard comes from the 2019 HSC rescrutiny results published by the Education Board of Bangladesh. This dataset includes information on students' previous and current grades across various subjects and groups.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/tshihab/Fleet-Management-Dashboard01.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Fleet-Management-Dashboard01
    ```
    
3. Python Script: Use Python scripts to preprocess the data in Excel (e.g., calculations, transformations) and save the processed data back to Excel, if applicable.
4. Load the Data: Load the data into your visualization tool and ensure the data fields align with the visualizations.
5. Run the Dashboard: If using Power BI, open the .pbix file to view and interact with the dashboard.

## Usage

  - Open the Power BI dashboard to view overall fleet metrics at a glance.
  - Use the driver filter to drill down into individual driver metrics and assess performance.
  - Analyze cost metrics to identify potential savings and optimize fleet costs.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
