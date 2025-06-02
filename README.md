# Data-Cleaning-and-Preprocessing

Challenges Faced on this project
- Converting non-standard date strings like "September 24, 2021" into Excel-readable date formats.
- Finding and handling missing data in multiple text columns efficiently.
- Maintaining formatting while saving the final cleaned file.

Learnings
- Improved skills in data cleaning using Excel tools like filters, conditional formatting, and date functions.
- Understood the importance of consistent formatting and how minor issues can impact analysis.
- Gained confidence working with real-world raw datasets.

Tools Used
- Microsoft Excel

Date Formatting:
   - Converted `date_added` column to consistent format `dd-mm-yy` using the **Custom Format** under Format Cells.
  
Step perform:
Select the column with dates (e.g., date_added)
Go to the Home tab → Click on Number Format drop-down
Choose Custom
Enter the format: dd-mm-yy

Handled Missing Values:
   - Filled empty cells in `director`, `cast`, and `country` with `"Unknown"` using Excel filters and Find & Replace.


