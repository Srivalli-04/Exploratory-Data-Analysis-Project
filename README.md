# Online Book Dataset Analysis Using Web Scraping

## 📌 Project Overview

The **Online Book Dataset Analysis Using Web Scraping** project focuses on collecting, cleaning, and analyzing book-related information from the [Books to Scrape](https://books.toscrape.com/) website using Python.

The project collects information about book titles, prices, ratings, availability, categories, and product URLs. The collected data is organized into a structured dataset and analyzed using Exploratory Data Analysis (EDA) to understand book price distributions, rating patterns, category distribution, and availability.

This project demonstrates how web scraping and data analysis techniques can transform online information into a structured dataset for meaningful analysis.

## 🎯 Project Objectives

* Collect book information from an online book catalogue using web scraping.
* Extract relevant details from multiple website pages.
* Store the collected information in a structured dataset.
* Clean and prepare the data for analysis.
* Explore book prices, ratings, availability, and categories.
* Create visualizations to identify patterns and distributions.
* Demonstrate the practical application of Python in data analytics.

## 🌐 Data Source

**Website:** Books to Scrape
**URL:** https://books.toscrape.com/
**Collection Method:** Web Scraping
**Pages Scraped:** 50
**Total Records Collected:** 1,000 books

Books to Scrape is a website designed for practicing web scraping. The project collects publicly displayed book information from its catalogue pages.

## 🛠️ Technologies Used

| Technology       | Purpose                                             |
| ---------------- | --------------------------------------------------- |
| Python           | Programming language used for scraping and analysis |
| Requests         | Retrieves webpage content                           |
| BeautifulSoup    | Parses HTML and extracts book information           |
| Pandas           | Organizes, cleans, and analyzes the dataset         |
| Matplotlib       | Creates data visualizations                         |
| Seaborn          | Creates statistical charts                          |
| Jupyter Notebook | Provides an interactive coding environment          |

## 📊 Dataset Description

The final cleaned dataset contains **1,000 records and 6 columns**.

| Column Name  | Description                             |
| ------------ | --------------------------------------- |
| Title        | Name of the book                        |
| Price        | Listed book price in British pounds (£) |
| Rating       | Book rating on a scale of 1 to 5 stars  |
| Availability | Indicates the book's stock status       |
| Category     | Category or genre of the book           |
| Product_URL  | Link to the individual book's webpage   |

## ⚙️ Project Workflow

### 1. Data Collection

* Accessed the Books to Scrape website using Python.
* Retrieved webpage content using the Requests library.
* Used BeautifulSoup to parse HTML and extract book details.
* Collected information from 50 listing pages.

### 2. Data Cleaning and Preparation

* Organized the extracted information into a Pandas DataFrame.
* Checked the dataset for missing values and duplicate records.
* Converted price and rating values into appropriate data types.
* Prepared the dataset for exploratory analysis.

### 3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the characteristics of the collected book data.

The analysis focused on:

* Distribution of books across categories.
* Distribution of book availability.
* Distribution of book ratings.
* Book price distribution.
* Relationship between book prices and ratings.
* Variation in book prices across different categories.

### 4. Data Visualization

Matplotlib and Seaborn were used to create visualizations that make the data easier to understand.

Charts used in the analysis include:

* Bar Chart — Number of Books by Category
* Pie Chart — Book Availability Distribution
* Donut Chart — Distribution of Book Ratings
* Histogram — Book Price Distribution
* Scatter Plot — Price vs. Rating
* Box Plot — Book Price Distribution by Category

## 🔍 Key Fields Analyzed

* **Title:** Identifies each book in the catalogue.
* **Price:** Supports price distribution analysis and price comparisons.
* **Rating:** Helps examine the distribution of book ratings.
* **Availability:** Shows the stock status recorded during data collection.
* **Category:** Enables comparisons of book counts and prices across categories.
* **Product URL:** Provides a reference to the original book webpage.

## 📈 Expected Outcomes

The project provides a structured dataset and visual analysis of the collected online book information.

The analysis helps to:

* Understand how books are distributed across categories.
* Examine the range and distribution of book prices.
* Explore the distribution of ratings.
* Review the recorded availability status of books.
* Compare book price distributions across categories.
* Investigate whether book prices and ratings show an observable relationship.

Actual findings and conclusions should be based on the results obtained from the analysis.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use an environment such as Google Colab.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL.

### Step 2: Navigate to the Project Folder

```bash
cd online-book-data-analysis
```

### Step 3: Install the Required Libraries

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project's `.ipynb` notebook and execute the cells in order.

**Note:** If you are analyzing the saved dataset only, you may not need to rerun the web scraping section. If you rerun the scraper, the website's current content and structure may differ from the original collection.

## 📁 Project Structure

```text
online-book-data-analysis/
│
├── README.md
├── online_book_analysis.ipynb
├── cleaned_books.csv
└── visualizations/
    ├── category_distribution.png
    ├── availability_distribution.png
    ├── rating_distribution.png
    ├── price_distribution.png
    ├── price_rating_scatter.png
    └── price_by_category.png
```

*This is a suggested folder structure. Update the filenames to match the files you actually upload.*

## 💡 Applications

* Practicing web scraping and HTML parsing.
* Learning data cleaning and exploratory data analysis.
* Exploring online product catalogue data.
* Comparing prices and ratings across product categories.
* Building a portfolio project for entry-level data analytics roles.

## 🔮 Future Enhancements

* Collect additional book attributes, where available.
* Automate periodic data collection.
* Build an interactive dashboard using Power BI or Plotly.
* Perform statistical hypothesis testing on book ratings.
* Compare book prices and ratings across categories using additional statistical methods.

## 📝 Conclusion

This project demonstrates the use of Python-based web scraping to collect online book information and transform it into a structured dataset. By applying data cleaning, exploratory data analysis, and visualization techniques, the project explores book prices, ratings, availability, and category distribution.

The project provides practical experience in data collection, data preparation, analysis, and visualization, which are important skills for a Data Analyst.

## 👩‍💻 Author

**Srivalli Janani**
B.Tech — Data Science
Sreyas Institute of Engineering and Technology
