# US Sector Classification

This repository contains classified US stock tickers based on their sectors. The classification process uses data from the official US stock market website, as of **November 25, 2024**, to map stock tickers to their respective sectors. The data source is the **US SEC official website**.

## 📂 Directory Structure

   ```plaintext
   sector/
   ├── Communication_Services/
   ├── Consumer_Discretionary/
   ├── Consumer_Staples/
   ├── Energy/
   ├── Financials/
   ├── Healthcare/
   ├── Industrials/
   ├── Information_Technology/
   ├── Materials/
   ├── Real_Estate/
   └── Utilities/
   ```
   Each subdirectory contains text files or JSON files with stock tickers categorized by sector.

## 🛠️ Tools Used

- **Official US Stock Market Data (as of 2024/11/25):** The source of the sector classification for US stock tickers, from the US SEC official website.
- **Yahoo Finance API:** Used to fetch sector information for stock tickers.
- **Python:** For scripting and data processing.
- **Git:** For version control.

## 🚀 Usage

### Classification Script

 1. Clone this repository:
   ```bash
   git clone https://github.com/Zaphkiel1031/US_Sector_Classification.git
   cd US_Sector_Classification
   ```
 2. Ensure the sector/ directory exists with the classified tickers.
 3. Run the Python classification script to reclassify or update tickers if needed:
    
   ```bash
   python classify_tickers.py
   ```
      Note: The classify_tickers.py file is not included in the repository. You can add your custom script for further updates.
   
 4. Uploading Data
    Use the following Git commands to update data in the repository:
   
    ```bash
    git add .
    git commit -m "Update sector classification with data from official source (2024/11/25)"
    git push
    ```
    
## 📝 To-Do List
Add support for additional data points like market capitalization and P/E ratio.
Include error-handling for API rate limits.

## 💡 Contribution Guidelines
Feel free to fork this repository and submit pull requests for improvements or bug fixes.
