**Project Description**

This project compares salary progression under two different pension schemes: UPS (Unified Pension Scheme) and NPS (National Pension System). 
The calculations utilize the 7th Pay Commission's pay matrix and promotion criteria to estimate salary growth over an employee's career.

**Installation Instructions**

To run this project, ensure you have the following dependencies installed:

pip install pandas numpy


**Usage Guide**

Ensure the required datasets **CPC7.csv** and **Simplified_Minimum_SL_Promotion.csv** are in the same directory as the script.

Run the script in a Jupyter Notebook or as a standalone Python program.

The output provides salary projections and pension estimations under both schemes.


**Assumptions Made**

1. Promotion Timing: Promotions are applied as soon as they are accrued, up to Pay Level 14.

2. Fitment Factor: A conservative factor of 1.7 is used for each prospective Pay Commission revision.

3. Military Service Exclusion: Military pay levels (13A) are excluded if the employee is not a defense personnel.

4. Data Accuracy: The calculations are based on official 7th Pay Commission data.


**Dependencies**

Python Libraries: pandas, numpy

CSV Files: CPC7.csv, Simplified_Minimum_SL_Promotion.csv

For any issues or improvements, feel free to contribute!

