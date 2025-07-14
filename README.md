# AI Stock Analysis Agent 📈

An intelligent AI agent that provides comprehensive stock analysis by combining technical chart analysis with real-time sentiment data.

## What It Does

This workflow creates an AI agent that:
- **Identifies stock tickers** from company names
- **Generates technical analysis** using MACD charts and other indicators
- **Performs sentiment analysis** by scraping recent news and analyst opinions
- **Synthesizes everything** into a comprehensive investment outlook

## Tools Used

- **N8N** - Workflow automation platform
- **OpenAI GPT-4** - AI model for analysis and synthesis
- **Tavily** - Web search and sentiment analysis (1,000 free credits/month)
- **Chart-Image.com** - Chart generation API (50 free calls/day)
- **HTTP Requests** - Data fetching and API integration

## Sample Output

The agent provides:
1. **Overall Summary** - Quick 2-3 sentence overview
2. **Quantitative Snapshot** - Key financial metrics and embedded chart
3. **Technical Analysis** - MACD analysis, trends, support/resistance levels
4. **Qualitative Context** - Recent news and market sentiment
5. **Integrated Outlook** - Synthesized investment perspective

## Reference

Based on the tutorial: [How to Build an AI Stock Analysis Agent](https://www.youtube.com/watch?v=-GP9tGaWfcs&t=148s)

## Quick Start

1. Set up accounts for Tavily and Chart-Image.com
2. Configure API keys in N8N
3. Import the workflow templates
4. Test with any stock ticker (e.g., "Tesla", "Apple")

*Perfect for traders and investors who want AI-powered stock analysis combining technical indicators with market sentiment.*
