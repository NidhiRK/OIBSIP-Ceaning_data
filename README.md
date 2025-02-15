# Data Cleaning Project: AB_NYC_2019 Dataset

This project focuses on cleaning the `AB_NYC_2019` dataset to ensure data integrity, handle missing values, remove duplicates, standardize data, and detect outliers.

## Dataset Information
- **Dataset Name:** AB_NYC_2019
- **Columns:**
  - `id`, `name`, `host_id`, `host_name`, `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude`, `room_type`, `price`, `minimum_nights`, `number_of_reviews`, `last_review`, `reviews_per_month`, `calculated_host_listings_count`, `availability_365`

## Project Objectives
- **Data Integrity:** Ensuring accuracy and consistency.
- **Missing Data Handling:** Imputation and informed handling.
- **Duplicate Removal:** Identifying and eliminating duplicates.
- **Standardization:** Consistent formatting across the dataset.
- **Outlier Detection:** Identifying and addressing outliers.

## Code Overview
- **Load Dataset:** Read the CSV file into a Pandas DataFrame.
- **Handle Missing Data:** Impute missing `reviews_per_month` with median values.
- **Remove Duplicates:** Drop duplicate records.
- **Standardize Data:** Convert column names to lowercase and round prices.
- **Detect Outliers:** Remove outliers based on IQR method.
- **Save Cleaned Data:** Export the cleaned dataset as `AB_NYC_2019_cleaned.csv`.

## How to Run
1. Clone this repository.
2. Ensure you have Python 3.x installed along with Pandas and NumPy.
3. Run the provided Python code to clean the dataset.

## Output
- Cleaned dataset saved as `AB_NYC_2019_cleaned.csv`.

## Tools Used
- Python
- Pandas
- NumPy

---

Feel free to explore, modify, and contribute to this project!

### Author
Your Name Nidhi Kushwaha                                                                                                                           
📢 Connect with Me
🔗 LinkedIn:(https://www.linkedin.com/in/nidhi-kushwaha-1b64b62a1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)                                      
📧 Email: nidhirk1706@gmail.com
