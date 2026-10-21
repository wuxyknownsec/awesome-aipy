# AiPy in Action: Analyze 3C Appliance Chain Store Sales Data with One Prompt (HTML + Word + PPT)
> Upload a sales dataset and use natural language to have AiPy clean, analyze, and report in three formats automatically.
**Keywords**: AiPy, sales data analysis, 3C appliances, Excel analysis, data visualization, HTML report, business intelligence, natural language programming
---
## What is AiPy?
AiPy is an open-source AI desktop assistant developed by **Knownsec**, built around the **Python-Use** philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.
- Website: https://www.aipyaipy.com
- Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
---
## Scenario
The sales lead of a national 3C appliance retail chain needed to analyze store-level sales data.
**Pain Points**:
- **Overwhelming data volume**: 2,800+ orders, manual analysis is slow and error-prone
- **Multi-dimensional needs**: overall performance + product mix + store ranking + customer profile + promotion effect
- **Anomaly detection**: suspected promotion abuse needs to be located quickly
- **Lack of decision support**: needs data-driven sales strategy recommendations
**Goal**: Produce a multi-dimensional HTML sales report from a single sales detail table.
---
## Steps
1. Open AiPy and install the skills **Excel Visualization Analysis** and **Web Frontend Development** from the marketplace
2. Upload the sales data table and enter the prompt (see "Prompt" below)
3. AiPy reads the data, writes the analysis script, and generates the report
### Prompt
```text
I am the sales lead of a national 3C appliance retail chain. Please help me analyze this store-level sales summary data.
1. File path: (upload the table file here)
2. File content: the headers are order_id, date, product_category, product_name, brand, unit_price, quantity, total_amount, payment_method, customer_gender, customer_age_group, promotion, store_location, sales_time, salesperson
3. Analysis content: write an HTML store sales analysis report covering total sales, product sales distribution, promotion status, store sales ranking, customer profile, salesperson performance, whether there is any promotion abuse, and optimization suggestions for future sales strategy adjustments.
4. Analysis rules: before analyzing, read the first 30 rows to understand the data format, then write a suitable analysis script based on the actual format.
5. Save the report to the current working directory.
```
How AiPy Did It
## How AiPy Did It
| Step | Stage | Description |
|------|-------|-------------|
| 1 | Auto data acquisition | Intelligently reads the raw sales table |
| 2 | Data cleaning | Handles missing values and unifies formats |
| 3 | Multi-dimensional analysis | Sales trends, customer profile, store ranking |
| 4 | Professional charts | Auto-generated trend, comparison, and share charts |
| 5 | In-depth report | Output in HTML + PPT + Word |
**Tech Stack**: Python, Pandas, Matplotlib, HTML/CSS
---
## Results
| Traditional way | Now with AiPy |
|-----------------|---------------|
| 4-6h | 2'45" |
| Tedious Excel formulas | Fully automated analysis |
| Adjusting charts step by step | Auto-generated charts |
| Manual anomaly screening | Automatic anomaly detection |
🚀 **About 100x efficiency gain! Full analysis done in 2 minutes 45 seconds**
**User Takeaways**:
- **The more specific the request, the more accurate the result**: state data fields, analysis dimensions, and output format all at once
- **Use raw data directly**: AiPy cleans and aligns automatically, skipping the most annoying preprocessing
- **One dataset, multiple formats**: HTML for online viewing, Word for printing, PPT for meetings
- **Verify key numbers**: double-check decision-critical conclusions for both professionalism and efficiency
---
## Screenshots
![3C Appliance Store Sales Analysis Report](https://www.aipyaipy.com/cases/case1/3C家电门店销售分析报告.html)
**Deep Research Report (PDF)**: https://www.aipyaipy.com/cases/case1/deep_research_report.pdf
**Sales Analysis PPT (PDF)**: https://www.aipyaipy.com/cases/case1/3c_sales_ppt.pdf
---
## FAQ
**Q1: Does AiPy require an internet connection?**
A: No. AiPy runs fully locally — your sales data never leaves your computer.
**Q2: Do I need to know how to code?**
A: No. Just upload the table and describe your analysis needs; AiPy generates and runs the code.
**Q3: Which operating systems does AiPy support?**
A: macOS / Windows / Linux desktops.
**Q4: How much data can it handle?**
A: This case processed 2,800+ orders; the volume scales with your machine's capability.
**Q5: What output formats are supported?**
A: HTML, Word, and PPT — suitable for online viewing, printing, and meetings respectively.
---
## Related Links
- Original case study: https://www.aipyaipy.com/cases/case1/
- AiPy website: https://www.aipyaipy.com
- GitHub repository: https://github.com/wuxyknownsec/awesome-aipy
