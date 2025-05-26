Task 1: Data Cleaning and Preprocessing (Excel)

📌 Objective
The goal of this task was to clean and preprocess a raw dataset using Microsoft Excel by handling missing values, removing duplicates, standardizing data formats, and ensuring consistent structure for analysis.

📁 Dataset Used
- **Dataset Name**: Customer Personality Analysis (sample data inspired by the original Kaggle dataset)
- **Format**: Excel `.xlsx`
- **Sample Fields**: ID, Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome, Dt_Customer, Recency, Gender

✅ Cleaning Steps Performed
1. **Removed duplicate rows** (e.g., ID 1006 was a duplicate of ID 1001).
2. **Handled missing values** in the `Income` column by replacing blanks with the average income.
3. **Standardized text fields**:
   - Gender: converted to `Male` / `Female`
   - Education: standardized capitalization (e.g., `PhD`, `Graduation`, `Master`)
   - Marital status: ensured uniform spelling and case
4. **Formatted date values** in the `Dt_Customer` column to `DD-MM-YYYY`.
5. **Renamed column headers** to lowercase with underscores (e.g., `Marital_Status` → `marital_status`).

📄 Files Included
- `cleaned_customer_data.xlsx`: Cleaned and processed dataset
- `summary.txt`: Brief overview of all changes made
- `raw_sample_data.xlsx`: The original version before cleaning
- `screenshots/`: Excel screenshots showing cleaning steps
- `README.md`: This file

🛠 Tools Used
- Microsoft Excel (for data cleaning)
- GitHub (for version control and submission)

✍️ Author
 - Shobana Balusamy
