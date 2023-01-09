
# Code and Data for Web-Scraping EC Initiatives and Text Mining

- The pdf-documents are in the data folder
- Descriptives and Data exploration: explore.ipynb
- Analysis: analysis.ipynb

## Summary Data 
(Status: 07/01/2023)


#### + Commission Adoption, Feedback Period: [Artificial intelligence – ethical and legal requirements](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/12527-Artificial-intelligence-ethical-and-legal-requirements/feedback_en?p_id=24212003) 
- *N* = 304
- Feedback period: 2021-08-06  — 2021-04-27 


#### + Roadmap, Feedback Period: [Artificial Intelligence - ethical and legal requirements](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/12527-Kunstliche-Intelligenz-ethische-und-rechtliche-Anforderungen/feedback_de?p_id=8242911&page=13)
- *N* = 133
- Feedback period: 2020-07-23 — 2020-09-10 



#### + Public Consultation: [Artificial intelligence – ethical and legal requirements](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/12527-Artificial-intelligence-ethical-and-legal-requirements/public-consultation_en) 
- *n* = 440 pdfs (*n* = 1216 total submissions) 
- Feedback period: 2020-02-20  — 2020-06-14



## Summary Web-Scrapping

- Web scraping with *Selenium* and [Chrome driver](https://chromedriver.chromium.org/downloads)

```bash
pip install selenium
```
- Parsing pdf-documents and html (*BeautifulSoup*)
```bash
pip install pdfplumber
pip install PyPDF2
```

- Translation of multilingual text with deepl
```bash
pip install deep-translator
```

