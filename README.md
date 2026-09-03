# CodeAlpha_webscraping
# CodeAlpha Web Scraping Project

## 📌 Internship Task 1: Web Scraping

This project was completed as part of my **CodeAlpha Data Analytics Internship**.

The objective of this task is to collect useful information from a website using **Python and web scraping techniques**, organize the collected information into a structured dataset, and save it as a CSV file for further analysis.

## 🎯 Objective

* Extract book information from a website.
* Understand the basic structure of HTML webpages.
* Use Python to collect data automatically.
* Store the scraped information in a structured format.
* Create a CSV dataset that can be used for further data analysis.

## 🛠️ Tools and Technologies Used

* **Python**
* **Google Colab**
* **Requests**
* **BeautifulSoup**
* **Pandas**
* **CSV**

## 🌐 Website Used

**Books to Scrape**

The website is a practice website designed for learning web scraping.

## 📊 Data Collected

The following information was collected for each book:

| Column       | Description                  |
| ------------ | ---------------------------- |
| Book Title   | Name of the book             |
| Price        | Price of the book in pounds  |
| Rating       | Customer rating from 1 to 5  |
| Availability | Whether the book is in stock |
| Book URL     | Link to the book             |

## 🔄 Web Scraping Process

The project follows these steps:

1. Send a request to the website using the `Requests` library.
2. Retrieve the webpage HTML.
3. Parse the HTML using `BeautifulSoup`.
4. Find the required book information.
5. Extract the title, price, rating, availability, and URL.
6. Store the extracted information in a Pandas DataFrame.
7. Clean the price data.
8. Check for missing and duplicate values.
9. Save the final dataset as a CSV file.

## 📁 Project Files

```text
CodeAlpha_webscraping/
│
├── README.md
├── Web_Scraping.ipynb
└── Books  E-commerce
```

## 📈 Output

The final output is a structured CSV dataset containing information about **1,000 books** collected from the website.

The dataset can be used for the next internship tasks, including:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis

## 💡 Learning Outcomes

Through this project, I learned:

* How web scraping works.
* How to send HTTP requests using Python.
* How to parse HTML using BeautifulSoup.
* How to extract specific information from webpages.
* How to use Pandas for data processing.
* How to create and save a CSV dataset.
* How to prepare scraped data for further analysis.

## 🚀 Future Work

The scraped dataset will be used for **Task 2: Exploratory Data Analysis (EDA)** and **Task 3: Data Visualization** to identify trends, patterns, and useful insights from the book data.

## 👨‍💻 Internship

**Organization:** CodeAlpha
**Task:** Task 1 – Web Scraping
**Domain:** Data Analytics
