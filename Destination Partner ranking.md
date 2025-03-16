# README for Destination Partner Ranking- Remittance Data Analysis Project

## Overview

The **Destination Partner Ranking** project analyzes data sourced from a database. The relevant queries and tables used for this analysis are detailed in the accompanying documentation titled **Destination Partner Ranking**. This project aims to rank destination partners based on specific criteria and generate a comprehensive output.

## Data Sources

The project requires downloading three files from the database. Please note that no CSV files are attached to this repository. You will need to download the files manually as per the instructions in the documentation.

## Data Preparation

After downloading the three files, follow these steps to prepare the data:

1. **Check Common Entries**: Manually inspect the `destination_country` and `destination_partner` columns in all three files. 
2. **Remove Uncommon Entries**: Delete any rows that do not have common values across all three files. After this step, each file should contain exactly **465 rows**, excluding the column headers.

## Running the Code

Once the data is prepared, run the provided code with the three cleaned files. The code will generate the following output files:

1. **Sorted Files**: Three output files, each corresponding to the original files but sorted and ranked based on the specified criteria.
2. **Final Combined Result**: A fourth output file that combines the results from the three sorted files. This file will include:
   - Total rank
   - Average rank

## Conclusion

This project provides a structured approach to ranking destination partners based on data from a database. By following the outlined steps for data preparation and execution, you will obtain sorted and ranked files, along with a comprehensive final output that summarizes the results. 

For any further questions or clarifications, please refer to the **Destination Partner Ranking** documentation or reach out to the project maintainers.


