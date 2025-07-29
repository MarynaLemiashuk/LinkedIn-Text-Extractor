# LinkedIn-Text-Extractor

This Python script extracts structured contact and company data from a plain text file (all.txt) exported from LinkedIn Sales Navigator or similar platforms. It identifies and parses key fields from unstructured text blocks and saves the result to a clean Excel file.

✅ What It Does
From a raw .txt document containing multiple LinkedIn profiles, the script extracts:

First Name

Surname

Job Title

Company Name

Company Size (e.g., “10,000+”)

Country

(Empty) Email Address column for future enrichment

It then saves this data to linkedin_extracted.xlsx.

📁 Input
File: all.txt

Format: Unstructured text (e.g., copy-pasted or exported from a LinkedIn list)

Each entry is expected to contain profile-like information such as:

Go to Marketa Pfleger’s profile  
Head of Human Resources  Samsung Electronics  
Prague, Czechia  
Company headcount  
10,000+


📦 Requirements
Install required Python packages (only pandas is necessary):

pip install pandas

▶️ How to Run
Place your raw text file as all.txt in the same folder as the script.

Run the script:

TXT to Excel Sales Navigator.ipynb

The output Excel file linkedin_extracted.xlsx will appear in the same directory.

✏️ Notes
The script uses regular expressions to match patterns in the text.

Works best when the structure is consistent (as in exports from LinkedIn Sales Navigator).

You can expand the list of recognized countries or patterns in the script as needed.

👩‍💻 Author
Maryna Lemiashuk
GitHub: @MarynaLemiashuk
