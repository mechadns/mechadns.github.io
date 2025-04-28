---
title: Python Web Scrape
description: This script was written to scrape phone numbers of various restaurants from Google. Perfect for data enrichment and lead generation projects.
publishDate: 2024-08-09
tags:
  - Web Scraping
  - BeautifulSoup
  - Python
  - Phone Number Scraper
  - Data Enrichment
seo:
  image:
    src: /portfolio-1.jpg
    alt: Python Web Scrape Project
isFeatured: true
---

<p style="text-align: center;">
The GitHub repository for this project can be viewed <a href="https://github.com/mechadns/python_phone_number_web_scrape" target="_blank">here</a>.
</p>

# Phone Number Scraper

In this project, I created a simple Python script designed to collect **publicly available** phone numbers from **Google Search** results. The tool automates queries, extracts visible phone numbers, and populates them into a structured CSV file for easy enrichment and further use.

> ⚡️ **Disclaimer**: This tool is designed to strictly scrape publicly available phone numbers. Ensure your usage complies with Google's Terms of Service and local data privacy regulations.

---

## 🚀 Features

- Automated querying via Google Search.
- Extraction of publicly visible phone numbers from result pages.
- CSV output (`Enriched_Dataset.csv`) with enriched data.
- Built-in basic error handling for common scraping issues.
- Written in Jupyter Notebook (`Scrapping_script.ipynb`).

---

## 📂 Files in the Repository

| File | Description |
|:-----|:------------|
| `Scrapping_script.ipynb` | Jupyter Notebook containing the scraping script and all processing logic. |
| `Enriched_Dataset.csv` | Output CSV containing the extracted and enriched phone number data. |
| `requirements.txt` | Contains the dependencies required to run this script. |

---

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook
- Key Libraries:
  - `requests`
  - `beautifulsoup4`
  - `gspread`
  - `oauth2client`
  - `re` (regular expressions)

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## 🧹 How to Use

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/phone-number-scraper.git
   cd phone-number-scraper
   ```

2. **Install dependencies**.

3. **Run the Notebook**:

   Open `Scrapping_script.ipynb` using Jupyter Notebook or JupyterLab, and execute the cells sequentially.

4. **Customize Search Terms** (Optional):

   Modify the query section inside the notebook to change the search keywords according to your needs.

5. **View Results**:

   After execution, the enriched phone numbers will be saved in `Enriched_Dataset.csv`.

---

## ⚠️ Important Notes

- **Respect Robots.txt**: Always check and respect the `robots.txt` file of any site you scrape.
- **Rate Limiting**: Add delays between requests to avoid being IP-banned.
- **Legal Compliance**: Scrape responsibly and ensure you adhere to all applicable data privacy laws.

---

## 🧺 Future Improvements

- Integrate proxy support.
- Implement CAPTCHA handling.
- Add multi-threaded scraping for faster data collection.
- Deploy as a Python package or CLI tool.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file in the GitHub repository for more details.

---