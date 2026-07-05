Delta Lake MERGE Implementation
=== Objective ===
This project demonstrates incremental data processing using Delta Lake MERGE operation in Databricks with PySpark.

The assignment covers:
- Loading CSV data into Delta Lake
- Data cleaning (null check and duplicate removal)
- Creating incremental datasets
- Performing MERGE operation (SCD Type 1)
- Validating the final merged data

---

=== Technologies Used ===

- Databricks Community Edition
- PySpark
- Delta Lake
- Python
- Git & GitHub


---> Steps Performed

1. Data Loading
- Loaded Superstore CSV file
- Converted column names
- Saved dataset as Delta Table
- Loaded Delta table

2. Data Cleaning
- Checked null values
- Removed duplicate records
- Created cleaned Delta dataset

3. SCD Type 1 Preparation
- Selected existing customer records
- Updated existing records
- Created new customer records
- Combined records into an incremental dataset

4. Delta MERGE
- Loaded Delta Table
- Applied MERGE operation
- Updated matching records
- Inserted new records

5. Validation
- Verified merged dataset
- Checked total record count
- Verified duplicate records



=== Results  ===

- Successfully loaded CSV into Delta Lake
- No null values found
- Duplicate records removed
- Incremental dataset created
- MERGE operation executed successfully
- Final dataset validated successfully



=== Learning Outcomes ===

Through this project, I learned:

- Delta Lake fundamentals
- Delta Table creation
- Data Cleaning using PySpark
- Incremental Data Processing
- MERGE operation in Delta Lake
- SCD Type 1 implementation
- Data Validation
- GitHub project organization

