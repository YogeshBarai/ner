# NER Script for Extracting Companies, Tickers, ISINs, and Ratings from PDFs

This Python script extracts company names, tickers, ISINs, and associated ratings or preferences from a PDF report using Named Entity Recognition (NER) and regular expressions. The script leverages the `spaCy` library for NER and `PyPDF2` for PDF text extraction.

## Features

- **Extract Company Names**: Identify companies mentioned in the PDF using NER.
- **Extract Tickers**: Detect stock ticker symbols.
- **Extract ISINs**: Find International Securities Identification Numbers.
- **Extract Ratings/Preferences**: Capture associated ratings (e.g., Buy, Sell, Hold) if mentioned near company names.