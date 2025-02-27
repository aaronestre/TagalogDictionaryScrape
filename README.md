# Tagalog Dictionary Scrape

A Python web scraper that extracts Tagalog-to-English dictionary data from [tagalog.pinoydictionary.com](https://tagalog.pinoydictionary.com) and stores it in a structured Pandas DataFrame.

---

## Technologies Used
- **Main Language:** Jupyter Notebook and Python 3.12.8
- **Web Scraping:** BeautifulSoup4  
- **Data Extraction:** Regular Expressions (Regex)  
- **Data Storage & Manipulation:** Pandas  

---

### Introduction
This project scrapes the [Tagalog Pinoy Dictionary](https://tagalog.pinoydictionary.com) and compiles a structured dataset of **Tagalog words, their parts of speech, and English definitions**.  
- **BeautifulSoup4** extracts words and definitions from the website.  
- **Regex** parses and formats the extracted text.  
- **Pandas** stores and organizes the data for further analysis.  

I wanted to create my own dicitionary of Tagalog vocabulary words in order to use for my other project, **Tagalong**. With this data, I can update a database with the words so that I can then make flashcards to learn from.

As of 1/29/2025, [Tagalog Pinoy Dictionary](https://tagalog.pinoydictionary.com) is down and unable to be scraped.

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
- [x] Store data in a **database** (Supabase) instead of CSV.