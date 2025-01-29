# Tagalog Dictionary Scrape

A Python web scraper that extracts Tagalog-to-English dictionary data from [tagalog.pinoydictionary.com](https://tagalog.pinoydictionary.com) and stores it in a structured Pandas DataFrame.

---

## Technologies Used
- **Web Scraping:** BeautifulSoup4  
- **Data Extraction:** Regular Expressions (Regex)  
- **Data Storage & Manipulation:** Pandas  

---

### Introduction
This project scrapes the [Tagalog Pinoy Dictionary](https://tagalog.pinoydictionary.com) and compiles a structured dataset of **Tagalog words, their parts of speech, and English definitions**.  
- **BeautifulSoup4** extracts words and definitions from the website.  
- **Regex** parses and formats the extracted text.  
- **Pandas** stores and organizes the data for further analysis.  

---

### Example Output
After running the script the resulting DataFrame will look like this:
| Tagalog           | Part of Speech | Definition |
| :---------------- | :------------: | ---------: |
| Bahay             |   noun         | house      |
| Takbo             |   verb         | run        |
| mabilis           |   adjective    | fast       |

---
### Future Improvements

- [ ] Implement **multi-threading** for faster scraping.
- [ ] Add **error handling** for missing or malformed data.
- [ ] Store data in a **database** (Firebase) instead of CSV.