# tesla-gamestop-stock-analysis
This Jupyter notebook assignment, "Extracting and Visualizing Stock Data," guides learners through extracting stock and revenue data for Tesla and GameStop using yfinance and web scraping, and plotting the results into graphs.


# Extracting and Visualizing Stock Data

## Project Overview
Extracting essential data from financial datasets and displaying it visually is a fundamental skill in data science, empowering analysts and stakeholders to make informed decisions[cite: 10]. This project demonstrates an end-to-end data pipeline using Python to extract historical stock prices and quarterly revenue data for major companies (**Tesla** and **GameStop**), clean the datasets, and plot comprehensive comparative charts[cite: 10].

## Technologies & Libraries Used
* **Python**[cite: 10]
* **yfinance** – For extracting stock market history[cite: 10]
* **BeautifulSoup (`bs4`) & Requests** – For web scraping HTML financial tables[cite: 10]
* **Pandas** – For data wrangling, cleaning, and structuring dataframes[cite: 10]
* **Matplotlib** – For generating static visualization dashboards[cite: 10]

---

## Project Steps & Workflow

### 1. Custom Graphing Function Setup
* Developed a helper function named `make_graph` utilizing `matplotlib.pyplot`[cite: 10].
* Configured a dual-panel layout showing historical share prices on the top axis and historical quarterly revenue trends on the bottom axis[cite: 10].

### 2. Tesla Data Extraction (`TSLA`)
* **Stock Data:** Created a `yfinance` Ticker object for Tesla (`TSLA`) and extracted maximum-period historical pricing information[cite: 10]. Reset the dataframe index for clean chronological formatting[cite: 10].
* **Revenue Data:** Downloaded historical financial web pages using `requests` and parsed the raw HTML via `BeautifulSoup`[cite: 10]. Extracted quarterly revenue records, removed currency symbols and commas, and eliminated null entries[cite: 10].

### 3. GameStop Data Extraction (`GME`)
* **Stock Data:** Followed the same extraction procedure using `yfinance` for GameStop (`TSLA` equivalent ticker `GME`) to capture historical market performance[cite: 10].
* **Revenue Data:** Scraped GameStop's quarterly revenue data tables from source HTML pages, applying rigorous data cleaning to ensure accurate numeric formatting[cite: 10].

### 4. Visualization & Dashboards
* Successfully invoked the graphing pipeline to render comparative historical stock performance and revenue charts for both Tesla and GameStop[cite: 10].

---

## How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)



