# Web_Scraping_application
# Web Scraping and Data Extraction Application

## 📌 Project Overview

This project demonstrates web scraping using Python to extract product information from a webpage. It uses **Requests** to retrieve webpage content, **BeautifulSoup** to parse HTML and extract product details, and **Pandas** to organize the collected information into a structured DataFrame and export it to a CSV file.

The project was developed and executed using Google Colab.

## 🎯 Objectives

* Retrieve webpage HTML content using Python.
* Extract product names, prices, and image source paths using BeautifulSoup.
* Organize the extracted information into a Pandas DataFrame.
* Export the collected product details into a CSV file for further use.

## 🛠️ Technologies Used

* **Python** — Core programming language.
* **Requests** — Sends HTTP requests to retrieve webpage content.
* **BeautifulSoup** — Parses HTML and extracts product information.
* **Pandas** — Organizes extracted data into a DataFrame and exports it to CSV.
* **Google Colab** — Environment used to develop and run the notebook.

## ⚙️ How It Works

1. **Send an HTTP request:** The Requests library retrieves the webpage content.
2. **Parse HTML:** BeautifulSoup parses the HTML using Python's `html.parser`.
3. **Extract product details:** The application identifies product containers and extracts product names, prices, and image source paths.
4. **Create a DataFrame:** Pandas organizes the extracted details into columns.
5. **Export the data:** The DataFrame is saved as `productdetails.csv`.
6. **Download the CSV:** Google Colab's file download functionality allows the generated CSV file to be downloaded.

## 📊 Data Extracted

The application extracts the following information:

| Field        | Description                               |
| ------------ | ----------------------------------------- |
| Product Name | Name of the product                       |
| MRP          | Product price displayed on the webpage    |
| Image Source | Image source path extracted from the HTML |

The notebook demonstrates extraction of nine product records.

## 📁 Expected Output

The generated CSV file is named:

`productdetails.csv`

Example output:

| Product Name | MRP | Image Source |
| ------------ | --: | ------------ |
| Robot 1      | 100 | toy.png      |
| Teddy 1      | 120 | toy.png      |
| Car 1        |  99 | toy.png      |

The CSV file contains the extracted product details in tabular form.

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Open Google Colab.
2. Upload or open the project notebook (`.ipynb`).
3. Run the notebook cells in sequence.
4. Execute the scraping and data extraction steps.
5. Generate `productdetails.csv`.
6. Download the CSV file using the provided download functionality.

### Option 2: Run Locally

1. Install Python on your computer.

2. Install the required libraries:

   ```bash
   pip install requests beautifulsoup4 pandas
   ```

3. Copy the code from the notebook into a Python script or run it in Jupyter Notebook.

4. Execute the script or notebook.

5. Check the output directory for `productdetails.csv`.

**Note:** The webpage must be accessible, and its HTML structure must match the selectors used in the notebook for the extraction to work correctly.

## 💡 Key Learnings

* Understanding HTTP requests and webpage responses.
* Parsing HTML content using BeautifulSoup.
* Extracting specific information using HTML tags and CSS classes.
* Organizing collected data with Pandas DataFrames.
* Exporting structured data to CSV files.
* Working with Python in Google Colab.

## 🔮 Future Enhancements

* Add error handling for failed HTTP requests.
* Convert product prices into numeric values for analysis.
* Add data validation and duplicate detection.
* Support configurable webpage URLs and product selectors.
* Add data visualization to compare product prices.

## 👩‍💻 Author

**Niharika Komaragiri**

GitHub: [NiharikaKomaragiri](https://github.com/NiharikaKomaragiri)
