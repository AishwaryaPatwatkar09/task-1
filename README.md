## Changes Made
1. **Missing Values**:
   - Dropped columns with high null counts (`director`, `cast`).
   - Filled missing `country` with "Unknown" and `rating` with the most frequent value.
2. **Duplicates**: Removed duplicate rows (if any).
3. **Standardization**:
   - Dates: Converted `date_added` to datetime format.
   - Text: Cleaned `title` (title case) and `rating` (e.g., `TV-14` → `TV14`).
4. **Column Names**: Formatted to lowercase with underscores (e.g., `show_id`).

## Files
- `cleaned_netflix_titles.csv`: Final cleaned dataset.
- `Netflix_Data_Cleaning.ipynb`: Google Colab notebook with the full code.

## How to Reproduce
1. Open the `.ipynb` file in Google Colab.
2. Run all cells to re-execute the cleaning steps.

## Tools Used
- Python (Pandas)
- Google Colab
