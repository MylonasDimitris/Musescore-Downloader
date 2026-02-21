# [ARCHIVED] Musescore Downloader

> **Note:** This project is no longer functional due to changes in Musescore's website security and hashed URLs.

## 📝 Overview
A simple Python script I built to automate downloading sheet music and converting it into PDF files. It was one of my first projects involving web automation and image processing.

## 🛠️ How it worked
* **Web Scraping:** Used Selenium to navigate the site and trigger lazy-loading of music sheets.
* **Image Conversion:** Used `PIL` and `svglib` to handle PNG and SVG files.
* **PDF Compilation:** Combined individual pages into a single document and fixed transparent backgrounds for better printing.

## 🧪 Technical Logic
* **`main.py`**: Selenium-based browser automation and element searching.
* **`download_manager.py`**: Handles downloading resources and determining file types.
* **`image_converter.py`**: Logic for fixing image transparency and merging pages into a PDF.

---
*Archived in 2026. This code is for reference only.*
