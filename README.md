# 🎬 IMDB Top 250 Movies Web Scraper 🕷️

## 📝 Description

This project is an automated web scraper designed to extract information about the top 250 movies according to IMDB. It uses advanced web scraping techniques to collect data such as titles, release years, runtime, and ratings, providing an efficient solution for analyzing movie data.

## ✨ Features

- 🤖 Automated data extraction from IMDB's Top 250 page.
- 🌐 Handling of dynamic web page elements.
- 🧠 Intelligent classification of metadata (year, runtime, rating).
- 📊 Generation of an Excel file with structured and clean data.

## 🛠️ Technologies Used

- 🐍 Python
- 🌐 Selenium with undetected_chromedriver
- 🐼 Pandas for data manipulation
- 🔍 Regular expressions for text processing

## 🚀 How It Works

1. **🔧 WebDriver Initialization**: Sets up an undetectable Chrome browser to avoid blocks.
2. **📚 Title Extraction**: Navigates to the IMDB page and extracts movie titles.
3. **🕵️ Metadata Collection**: Makes a second pass to gather additional information (year, duration, rating).
4. **🧮 Data Processing**: Sorts and structures the extracted information.
5. **🔗 Data Merging**: Combines titles with their respective metadata.
6. **💾 Export**: Generates an Excel file with all the collected and processed information.

## 💡 Benefits

- **⏱️ Automation**: Significantly reduces the time needed to collect data manually.
- **🎯 Accuracy**: Minimizes human errors in data collection.
- **🔄 Updating**: Makes it easier to obtain updated data regularly.
- **📈 Analysis**: Provides a structured database ready for further analysis.
  
## 🔧 Usage

1. Make sure you have all the dependencies installed.
2. Run the main script.
3. The script will automatically browse IMDB, extract the data, and generate an Excel file called 'df_merged.xlsx'.

## ⚠️ Note

This project is designed for educational and demonstration purposes. Make sure to comply with IMDB's terms of service and intellectual property laws when using this scraper.
