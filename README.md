
# Public Opinion on AI 

It contains data on three public consultation rounds where (business, academic, EU citizens, NGOs) expressed their views on policy options proposed in the White Paper on Artificial Intelligence.


## Documentation

 [Codebook Survey: Consultation No.1](https://linktodocumentation)


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Acknowledgements

 - [Institute for Technology Assessment and Systems Analysis (ITAS)](https://www.itas.kit.edu/english/index.php)
 - [BERTopic](https://maartengr.github.io/BERTopic/index.html)



## Feedback

If you have any feedback, please reach out to us at veronika.batzdorfer@gesis.org

# Public Opinion on AI Technologies- Consultations on Inception Impact Assessment

- The pdf-documents are in the data folder
- Descriptives and Data exploration: explore.ipynb
- Analysis: analysis.ipynb

## About
Proposal for a EU regulation of Artificial Intelligence. It contains three public consultation rounds where stakeholders expressed their views on policy options proposed in the [White Paper on Artificial Intelligence](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/12527-Artificial-intelligence-ethical-and-legal-requirements_en).

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
Dependencies:

- Web scraping with `Selenium` and [Chrome driver](https://chromedriver.chromium.org/downloads)
- Parsing pdf-documents and html `BeautifulSoup`
- `pdfplumber` `PyPDF2` `pdftools`

- Translation of multilingual text with googletranslate
 `deep-translator`
