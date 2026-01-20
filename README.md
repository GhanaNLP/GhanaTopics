# Ghana News 2025: Key Word Analysis

A collaborative public information project to identify and visualize the **Top 50 Keywords** appearing in Ghanaian news throughout 2025. This project aims to provide insights into national discourse and trending topics for social media sharing.

## Project Overview

The goal is to scrape at least 5 major Ghanaian news outlets, process the text data, and perform keyword extraction to see what dominated the headlines and reports in 2025.

**Core Objectives:**

1. **Scrape** content published in 2025 from selected news sites.
2. **Clean and Tokenize** the data into sentences and words.
3. **Analyze** frequency to find the top 50 keywords.
4. **Visualize** the results for social media distribution.

------

## Tech Stack

- **Language:** Python 3.x
- **Scraping:** `newspaper3k` (for article parsing) or `BeautifulSoup`/`Scrapy`.
- **NLP & Tokenization:** `spaCy` (preferred) or `NLTK`.
- **Data Handling:** `pandas`.

------

## Contributors & Assignments

Each participant is responsible for a specific news outlet to ensure broad coverage without duplicating efforts.

| Contributor                                                  | News Site                                    | Status   |
| ------------------------------------------------------------ | -------------------------------------------- | -------- |
| [Kasuadana Sulemana Adams](https://www.linkedin.com/in/kasuadana1/) | [GhanaWeb](https://www.ghanaweb.com)         | Assigned |
| [Obrempong Kwabena Osei-Wusu](https://www.linkedin.com/in/obrempong-kwabena-osei-wusu-7b0217257/) | [TV3 / 3News](https://3news.com)             | Assigned |
| [Jonathan Ato Markin](https://www.linkedin.com/in/atomarkin/) | [Citi Newsroom](https://citinewsroom.com)    | Assigned |
| [Josephus Bawah](https://www.linkedin.com/in/josephus-bawah/) | [Graphic Online](https://www.graphic.com.gh) | Assigned |
| [Bernard Zephaniah](https://www.linkedin.com/in/bernard-zephaniah-addo-addo-6a728b220/) | [MyJoyOnline](https://www.myjoyonline.com)   | Assigned |
| [Gerhardt Datsomor](https://www.linkedin.com/in/gerhardt-datsomor/) | [Ghana News Agency](https://gna.org.gh)      | Assigned |

------

## 🚀 Getting Started

### 1. Installation

Clone the repository and install the necessary libraries:

Bash

```
pip install newspaper3k spacy pandas
python -m spacy download en_core_web_sm
```

### 2. Scraping Guidelines

When scraping your assigned site, please ensure:

- Only articles published between **January 1, 2025, and December 31, 2025**, are included.
- Data is saved in a standardized format (CSV or JSON) with the following fields: `date`, `title`, `content`, and `url`.

### 3. Processing (Tokenization)

As discussed in the group, we are using **spaCy** for tokenization.

**Basic Workflow:**

1. Load the `en_core_web_sm` model.
2. Remove stop words (e.g., "and", "the", "is").
3. Tokenize the remaining text into cleaned keywords.

------

## Communication

All project discussions happen in the project group. If you encounter any issues or have any questions, please post in the group for support.
