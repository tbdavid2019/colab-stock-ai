# Colab Stock AI - 股票分析智能助手

<img width="1476" alt="image" src="https://github.com/user-attachments/assets/ae3dbab9-2798-47f7-b13f-4dd7d70f3472" />

## 項目簡介

這是一個基於人工智能的股票分析工具，集成於Google Colab環境中。該工具利用LangChain、OpenAI的GPT模型和Yahoo Finance API，提供全面的股票基本面分析，包括價格趨勢、技術指標、財務指標、產業趨勢以及市場新聞等多維度評估。

## 功能特點

- **股票價格分析**：分析股價走勢、波動性及技術指標
- **技術指標計算**：包含RSI、MACD、VWAP等多種技術分析指標
- **財務健康評估**：分析獲利能力、流動性、償債能力等財務比率
- **新聞情緒分析**：自動擷取並分析影響個股的最新新聞
- **產業競爭分析**：評估公司在產業中的競爭地位與市場表現
- **中文化輸出**：分析結果以繁體中文呈現，適合台灣投資者使用

## 使用方式

1. 複製程式碼到Google Colab運行環境
2. 確保安裝所需依賴庫（yfinance, langchain, dotenv等）
3. 設置環境變數（需要OpenAI API金鑰）
4. 指定股票代號（例如 6669.TW）進行分析

## 範例輸出

分析輸出將包含以下幾個主要部分：
```
{
  "stock": "<股票代號>",
  "price_analysis": "<股票價格趨勢與技術指標分析>",
  "technical_analysis": "<技術指標分析與見解>",
  "financial_analysis": { ... },
  "news_analysis": "<近期新聞摘要與其對股價的潛在影響>",
  "industry_analysis": "<產業趨勢、成長動力與潛在風險>",
  "competitor_analysis": "<主要競爭對手比較與市場地位分析>",
  "final_summary": "<整體綜合結論與投資建議>"
}
```

---

# Colab Stock AI - Stock Analysis Intelligent Assistant

## Project Introduction

This is an AI-powered stock analysis tool integrated with Google Colab environment. The tool leverages LangChain, OpenAI's GPT models, and Yahoo Finance API to provide comprehensive fundamental stock analysis, including price trends, technical indicators, financial metrics, industry trends, and market news.

## Key Features

- **Stock Price Analysis**: Analyze price movements, volatility, and technical indicators
- **Technical Indicator Calculation**: Includes RSI, MACD, VWAP, and other technical analysis indicators
- **Financial Health Assessment**: Analyzes profitability, liquidity, solvency ratios
- **News Sentiment Analysis**: Automatically fetches and analyzes latest news affecting individual stocks
- **Industry Competition Analysis**: Evaluates company's competitive position and market performance
- **Traditional Chinese Output**: Analysis results presented in Traditional Chinese, suitable for Taiwanese investors

## How to Use

1. Copy the code to Google Colab runtime environment
2. Ensure required dependency libraries are installed (yfinance, langchain, dotenv, etc.)
3. Set up environment variables (requires OpenAI API key) 
4. Specify stock symbol (e.g., 6669.TW) for analysis

## Sample Output

The analysis output will include these main sections:
```
{
  "stock": "<Stock Symbol>",
  "price_analysis": "<Stock price trends and technical indicator analysis>",
  "technical_analysis": "<Technical indicator analysis and insights>",
  "financial_analysis": { ... },
  "news_analysis": "<Recent news summary and potential impact on stock price>",
  "industry_analysis": "<Industry trends, growth drivers and potential risks>",
  "competitor_analysis": "<Main competitor comparison and market position analysis>",
  "final_summary": "<Overall comprehensive conclusion and investment recommendations>"
}
```
