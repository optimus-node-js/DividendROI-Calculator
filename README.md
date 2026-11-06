# DividendROI-Calculator

> A Python tool that tells you how much dividend income you can still earn with your available capital, using live NSE prices from Angel One and ex-dividend dates stored in MongoDB.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Angel One SmartAPI](https://img.shields.io/badge/Angel%20One%20SmartAPI-E4572E?style=flat-square)

## Features

- Fetches current stock prices through the Angel One SmartAPI
- Determines whether each dividend is still **active** (before ex-date) or **missed**
- Calculates shares affordable and potential dividend earnings per company for your balance
- Summarises total earnable dividends, missed opportunities and remaining upside

## Usage

```bash
git clone https://github.com/optimus-node-js/DividendROI-Calculator.git
cd DividendROI-Calculator
```

```bash
pip install pymongo requests smartapi-python
python driver.py      # enter your available balance when prompted
```

Set your own MongoDB URI and Angel One credentials (redacted in this public repo) before running.

---

## Author

**Rahul Vishwakarma**, Senior Full Stack Developer based in Ahmedabad, India

[![Portfolio](https://img.shields.io/badge/Portfolio-rahul--vishwakarma--portfolio.vercel.app-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://rahul-vishwakarma-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Vishwakarma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-vishwakarma-101346192)
[![Email](https://img.shields.io/badge/Email-karmarahul67%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karmarahul67@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-optimus--node--js-181717?style=flat-square&logo=github)](https://github.com/optimus-node-js)

