# PDF-Extractor
A Python script for automating the extraction and renaming of individual pages from a PDF based on specific text content, designed for efficient document handling and organization.


##Description:
This Python program is designed to automate the process of extracting individual pages from a large PDF file and renaming them based on specific text content extracted from each page. It's particularly useful for documents where each page contains unique identifiers like employee names and IDs. The script uses the PyPDF2 library for PDF manipulation and regular expressions for text extraction. It's ideal for processing documents in structured formats, such as workplace rosters or reports, where each page needs to be saved as a separate file with a descriptive name. The program also handles cases where the expected text is not found, saving these pages with a default naming scheme and logging their indices for review.

Repository Contents:

pdf_extractor_renamer.py: Main Python script.
requirements.txt: List of Python dependencies.
