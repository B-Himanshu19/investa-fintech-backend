# Investa Analytics Engine 📊 — AI-powered Fintech Analytics System

## AI-Powered Financial Analysis Platform

Investa Analytics Engine is a backend-driven financial analysis platform that leverages AI models for institutional-grade stock reports, financial scoring, portfolio monitoring, and real-time analytics — designed for seamless integration into payment, credit, or fraud detection ecosystems.

## 🏗️ Backend Architecture Highlights

- **Microservice-ready backend**: Modular design for scaling financial scoring engines
- **Secure API endpoints**: Enabling secure data ingestion from external payment or credit systems
- **Real-time ML scoring**: On-the-fly generation of analytics reports & financial scores
- **Designed for integration**: Can plug into KYC, credit scoring, or payment risk pipelines


[Investa.webm](https://github.com/user-attachments/assets/0f32976d-8911-4bbc-88bd-cbc8ecafde6c)

*Disclaimer : Investa Analytics Engine is built for backend financial data processing and analysis. It is for educational/demo purposes and not intended for direct investment advice.*

## 🔍 Financial Analysis Capabilities

Investa Analyzr excels in providing in-depth financial analysis:

- **Fundamental Analysis**: Comprehensive evaluation of financial statements, including:
  - Balance Sheet Analysis
  - Income Statement Breakdown
  - Cash Flow Statement Examination
- **Ratio Analysis**: 
  - Liquidity Ratios (Current Ratio, Quick Ratio)
  - Profitability Ratios (ROE, ROA, Profit Margins)
  - Valuation Ratios (P/E, P/B, EV/EBITDA)
- **Discounted Cash Flow (DCF) Modeling**
- **Comparative Analysis**: Peer comparison and industry benchmarking
- **Technical Analysis**: 
  - Moving Averages
  - Relative Strength Index (RSI)
  - MACD (Moving Average Convergence Divergence)
- **Risk Assessment**: 
  - Beta calculation
  - Value at Risk (VaR) estimation

## 🚀 Key Features

- **AI-Driven Insights**: Leverages advanced language models for nuanced financial interpretation
- **Real-Time Market Data**: Integration with Yahoo Finance API
- **News Sentiment Analysis**: Aggregates and analyzes recent news for market sentiment
- **Interactive Visualizations**: Dynamic stock charts and financial metric graphs
- **Automated Reporting**: Generates comprehensive PDF reports for professional presentations
- **User Authentication**: Secure login system with usage tracking

## 🛠️ Tech Stack

- **Backend**: Python (Flask APIs), Streamlit UI
- **AI/ML**: Groq API (LLaMA 3.1 model)
- **Data Sources**: Yahoo Finance, DuckDuckGo News API
- **Visualization**: Plotly
- **PDF Generation**: ReportLab
- **Database**: SQLite
- **Authentication**: bcrypt
- **Backend-Ready Architecture**: Suitable for integration into financial services or transaction monitoring systems


## 📊 Sample Analysis Output

```markdown
# AAPL: Comprehensive Financial Analysis

## Executive Summary
Apple Inc. demonstrates strong financial health with robust revenue growth and profitability...

## Financial Metrics
- Revenue Growth (YoY): 8.1%
- Gross Margin: 43.3%
- Operating Margin: 30.3%
- Net Profit Margin: 25.5%
- Return on Equity (ROE): 160.9%
- Debt-to-Equity Ratio: 2.31

## Valuation
- P/E Ratio: 30.2
- Forward P/E: 28.5
- PEG Ratio: 2.5
- EV/EBITDA: 22.7

... [Additional sections]

## Investment Recommendation
Based on our comprehensive analysis, we maintain a STRONG BUY recommendation for Apple (AAPL)...
```

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/bharathajjarapu/investa.git

# Navigate to the project directory
cd investa

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
echo "GROQ_API_KEY=your_api_key_here" > .env

# Run the application
streamlit run app.py
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
