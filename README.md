# Sustainability reports & NLP
This repository accompanies Finastra's Hack to the Future 4 learning session "Sustainability Reports and NLP" presented on March 17, 2022.  

---

### What is ESG?
**E**nviornmental issues, such as climate change and pollution  
**S**ocial issues around workplace practices and human capital  
**G**overnance issues such as executive pay, accounting, and ethics   

---

### Why care about ESG?
In addition to just being "good" to care about for obvious reasons, investors like ESG because it has been shown [^1][^2][^3] that 
- Higher ESG is associated with higher profitability and lower volatility
- High-ESG performance companies are good allocators of capital
- Good-ESG companies generally have higher valuations, EVA Growth, size, and returns
- Higher-ESG performance and profitable firms have higher returns with lower risk  

---

### ESG Reporting
A corporate social responsibility (CSR) report is an internal and external facing document companies use to communicate CSR efforts around environmental, ethical, philanthropic, and economic impacts on the environment and community. 
- 92% of S&P 500 index companies published annual sustainability reports in 2020[^4]
- There is not one standard reporting format in the US, but there are general reporting guidelines, such as that provided by Nasdaq[^5]
- Reports range from 30 pages to 200+ pages 
- Each CSR report highlights the company’s strong suits, goals, and plans around ESG
- Analysts and investors read multiple reports to understand and compare company trends and themes


---

### Natural Language Processing
Natural language processing (NLP) is a field of linguistics and machine learning that deals with natural (i.e., human) languages. The goal is to "understand" the unstructured text data and produce something new. Examples of NLP tasks are language translation, text summarization, and sentiment analysis.   
Here are a handful of the many NLP tasks:
- Language translation
- Sentiment analysis
- Text classification
- Document summarization
- Chat bots
- Autocomplete

---

### Zero-Shot Learning
Human languages are really complex, so it is impossible to train classifiers on every single phrase. Zero-shot learning (ZSL) models allow classification of text into categories unseen by the model during training. These methods work by combining the observed/seen and the non-observed/unseen categories through auxiliary information, which encodes properties of objects.

Other common uses for zero-shot learning models are images and videos. And the uses keep growing, such as activity recognition from sensors.

Zero-shot learning models are extremely helpful when you want to classify text on very specific labels and don't have labeled data. Labeled data can be difficult, expensive, and tedious to acquire, so zero-shot learning provides a quick way to get a classification without specialized data and additional model training.

The downside to zero-shot learning is that it is extremely slow compared to models trained on specific labels. It basically has to compute "what it means to be that label" then it has to check if your sentence "is that label."

---
### Sources
[^1]: https://corpgov.law.harvard.edu/2020/01/14/esg-matters/
[^2]: https://corpgov.law.harvard.edu/2021/06/02/esg-matters-ii/
[^3]: https://www.blackrock.com/corporate/literature/publication/blk-esg-investment-statement-web.pdf
[^4]: https://www.ga-institute.com/index.php?id=9128
[^5]: https://www.nasdaq.com/ESG-Guide
