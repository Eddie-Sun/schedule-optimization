# Nurse Scheduling Optimization

This project is an implementation of a Nurse Scheduling problem using Linear Programming. It aims to optimize nurse scheduling in a healthcare facility, respecting different constraints such as shift availability, minimum and maximum shifts, and consecutiveness of shifts and days worked.

## Getting Started

### Dependencies
- Python
- Pulp
- Numpy
- Matplotlib
- Seaborn

You can install the necessary dependencies with pip:

## Description
The project generates a cost matrix for full-time and part-time nurses and uses linear programming to minimize the total cost while respecting all constraints. The solution is displayed as a schedule for each nurse and visualized in a heatmap.

## Code Overview

1. **Import Necessary Libraries**: Libraries required for mathematical modeling, data manipulation, and data visualization are imported.
2. **Problem Definition and Data Generation**: Constants for the problem such as number of nurses, number of days, etc. are defined. A cost matrix is also generated using these constants.
3. **Model Creation and Constraints Addition**: An instance of the problem is created using the Pulp library. Necessary constraints are added to this model.
4. **Model Solution and Results Display**: The problem is solved using linear programming and the results are displayed.
5. **Data Visualization**: The nurse scheduling is displayed using a heatmap for a better understanding of the distribution of the schedule.

## Usage
To execute the script, run:

```shell
python MSCI555.py

