# 🤖 Blue Prism RPA: Web Scraping Automation

An RPA project built using **Blue Prism** to automate web scraping tasks such as extracting product details like name, price, and rating from e-commerce platforms and exporting the data to Excel. This project demonstrates how Robotic Process Automation can simplify repetitive data gathering operations.

---

## 📌 Project Overview

The primary objective of this project is to automate the process of **scraping product data**—including name, price, and rating—from online platforms (e.g., Flipkart), consolidate it, compare the results, and store the final sorted output in an Excel sheet.

This is accomplished entirely using **Blue Prism**, leveraging:
- **Process Studio** for flow control
- **Object Studio** for UI automation
- **VBOs (Visual Business Objects)** like:
  - *Utility - Collection Manipulation*
  - *MS Excel VBO*

---

## 🧠 Key Features

- 🔍 Scrape product details (name, price, rating) from e-commerce websites.
- 🗃️ Consolidate and merge datasets.
- 📊 Sort based on price to identify lowest-cost products.
- 📁 Export results into Excel automatically.
- ⏱️ Zero manual intervention once the bot is launched.

---

## 🛠️ Tech Stack

| Component          | Technology Used         |
|--------------------|--------------------------|
| RPA Tool           | Blue Prism               |
| Data Output        | Microsoft Excel          |
| Browser Interface  | Internet Explorer        |
| OS Compatibility   | Windows 8/10             |

---

## 🖥️ System Requirements

### Software
- Blue Prism (version 6 or higher recommended)
- Microsoft Excel
- Internet Explorer

### Hardware
- CPU: Pentium IV 2.4 GHz or above
- RAM: 4 GB or higher
- HDD: 40 GB minimum

---

## 🚀 Implementation Flow

1. **Start Process** in Blue Prism Process Studio.
2. Use **Object Studio** to:
   - Launch browser
   - Navigate to product page
   - Extract product info (name, price, rating)
3. Store the data in **collections**.
4. Use **Merge Collection** to consolidate multiple data sources.
5. Apply **sorting** to identify the best/lowest price.
6. Write the final output to Excel.

📌 **Note:** The `.bprelease` file included in this project can be imported into Blue Prism for immediate testing and execution.

---

## 📂 Project Files

```

blueprism-rpa-webscraping/
├── Web Scraping.bprelease       # Blue Prism release file
├── Web Scrapping.xlsx           # Sample Excel output
├── 1AM18CS016 Web Scraping Project Report.pdf  # Documentation
├── README.md

```

---

## ✍️ Author

- Aman Haris (1AM18CS016)

Guided by:
- Ms. Sonali S Dash  
- Ms. Sowmya B K  
  *Assistant Professors, Dept. of Computer Science, AMC Engineering College*

---

## 📚 References

- [Blue Prism Official Site](https://www.blueprism.com)
- [Blue Prism Community](https://community.blueprism.com)
- [YouTube Tutorials](https://www.youtube.com/results?search_query=data+extract+from+flipkart+using+blueprism)
