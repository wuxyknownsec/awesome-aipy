# AiPy in Action: Deep Quantitative Analysis of Stock Holdings with One Prompt (Technical + Fundamental + HTML Report)
> Tell AiPy about your 4 holdings, and it automatically fetches data, runs quantitative analysis, draws charts, and delivers a ready-to-open responsive HTML report.
**Keywords**: AiPy, portfolio quantitative analysis, stock analysis, technical analysis, fundamental analysis, data visualization, HTML report, investment decision, natural language programming
---
## What is AiPy?
AiPy is an open-source AI desktop assistant developed by **Knownsec**, built around the **Python-Use** philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.
- Website: https://www.aipyaipy.com
- Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
---
## Scenario
An investment manager at a private equity fund needs to analyze 4 holdings in depth and produce a briefing report on a regular basis.
**Pain Points**:
- **Scattered data, hard to see the full picture**: fundamental data, technical indicators, and news are spread across multiple platforms, requiring constant switching
- **High barrier to technical analysis**: MACD, RSI, Bollinger Bands, and moving averages require expertise to interpret
- **Decisions lack systematicity**: with multiple holdings, there is no unified evaluation framework or decision matrix, so decisions are often gut-driven
- **Report creation is time-consuming**: regular portfolio reporting requires extensive time to organize data and build charts
- **Emotions interfere with judgment**: market volatility triggers greed and fear, undermining objective analysis
**Goal**: Input 4 holdings and automatically produce a quantitative analysis report covering both technical and fundamental dimensions.
---
## Steps
1. Open AiPy and install the agents **Smart Portfolio Assistant**, **Investment Master Deep Analysis**, and **Web Frontend Development** from the marketplace
2. Enter the prompt (see "Prompt" below)
3. AiPy fetches data, runs quantitative analysis, and generates an HTML report
### Prompt
```text
I have 4 holdings. Please combine quantitative algorithms with the latest market data to perform an in-depth analysis across both technical and fundamental dimensions, give clear action recommendations, and generate a minimalist business-style, responsive, high-quality static HTML analysis report with refined layout, data visualization, and rigorous logic.
1. Holdings
Bank of Chengdu (cost 15.259 CNY), Sanwei Communication (cost 8 CNY), Capital Online (cost 34.87 CNY), Goldwind Science & Technology (cost 8.51 CNY)
2. Per-stock analysis requirements
Market performance: 1-year price trend, change percentage, volatility, relative strength vs. the broad market;
Latest developments: announcements, industry policies, and institutional ratings over the past month, with impact on share price noted;
Fundamentals: revenue, net profit, P/E ratio, industry position, core business, financial health, growth attributes, risk factors;
Technicals: moving averages, support/resistance levels, volume, MACD, KDJ, trend judgment;
Action conclusion: quantitative model verdict (increase/buy/hold/reduce/exit).
3. Hard requirements for the HTML report
Layout: responsive, works on desktop and mobile, minimalist business color scheme;
Top section: portfolio overview, cost, P&L reference, overall rating;
Required module: a decision table (stock, action recommendation, core logic, impact of developments, risk warning);
Per-stock section: an independent card for each stock covering fundamentals, technicals, latest developments, and rationale;
Typography: card layout, tiered headings, highlighted annotations, concise tables, no redundant content.
4. Output requirements
Objective and professional analysis, clear conclusions without ambiguity; the HTML deliverable must open directly, visualize data, and highlight key points.
```
---
## How AiPy Did It
| Step | Stage | Description |
|------|-------|-------------|
| 1 | Parse holdings | Extract the 4 stock codes and cost basis |
| 2 | Auto-fetch market data | Retrieve 1-year price data, announcements, and institutional ratings |
| 3 | Technical quantitative analysis | Compute moving averages, MACD, KDJ, support/resistance |
| 4 | Fundamental deep analysis | Revenue, net profit, P/E, financial health |
| 5 | Generate recommendations | Quantitative model outputs increase/hold/reduce verdicts |
| 6 | Output HTML report | Responsive business style with data visualization, ready to open |
**Tech Stack**: Python, Pandas, quantitative indicator libraries, HTML/CSS
---
## Results
| Traditional way | Now with AiPy |
|-----------------|---------------|
| 8+h | 15' |
| Manually collecting data for each stock | Fully automated data acquisition and analysis |
| Checking indicators in trading software | Smart generation of professional charts |
| Staying up late writing the report | Objective, neutral action recommendations |
| Easily influenced by emotions | Polished, reusable report |
🚀 **Over 32x efficiency gain!**
**Analysis Conclusions**:
- **Goldwind Science & Technology**: holding gain exceeds 226.7% with a huge cumulative rise; hold as the main strategy and take profits gradually on rallies
- **Sanwei Communication**: breakout pattern intact, MACD in bullish alignment, medium-to-long-term trend upward; consider adding on dips
- **Capital Online**: strong AI compute demand, volume breakout opens upside room, strong trend; actively add
- **Bank of Chengdu**: extremely low valuation, high dividend yield, strong defensive profile, suited to value investing; hold without chasing highs
**User Testimonial**:
> "Previously, producing a portfolio analysis report — from data collection to chart creation to writing recommendations — took at least a full day. Now with AiPy, I just tell it my holdings during a break, grab a coffee, and it's all done! The report quality is excellent, with professional charts and objective analysis; some recommendations are even more comprehensive than what our team discussed."
>
> —— Mr. Wang | Investment Department, Private Equity Fund, using AiPy for 1 month
---
## Screenshots
📊 [Deep Quantitative Analysis Report of Stock Holdings (HTML)](https://www.aipyaipy.com/cases/case8/材料/stock_analysis_report.html)
---
## FAQ
**Q1: Does AiPy require an internet connection?**
A: AiPy itself runs fully locally, but this case needs the latest market data, so an internet connection is required to fetch quotes and news.
**Q2: Do I need to know how to code?**
A: No. Just describe your holdings and analysis requirements in natural language, and AiPy generates and runs the analysis code.
**Q3: Which operating systems does AiPy support?**
A: macOS / Windows / Linux desktops.
**Q4: Can the conclusions be used directly for investment decisions?**
A: Not recommended. This analysis is AI-generated based on historical data and technical indicators and does not constitute investment advice. Invest with caution.
**Q5: How many holdings are supported?**
A: This case analyzed 4 holdings; the number is adjustable.
---
## Risk Warning
⚠️ This analysis is AI-generated based on historical data and technical indicators and **does not constitute investment advice**. Please invest with caution. The stock market carries risk; invest prudently!
---
## Related Links
- Original case study: https://www.aipyaipy.com/cases/case8/
- AiPy website: https://www.aipyaipy.com
- GitHub repository: https://github.com/wuxyknownsec/awesome-aipy
