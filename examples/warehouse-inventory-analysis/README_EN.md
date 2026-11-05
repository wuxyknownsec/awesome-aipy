# AiPy in Action: Complete Warehouse Inventory Analysis with One Prompt (Slow-Moving + Stockout + Cleanup Advice + Visual Report)
> Upload a warehouse dataset, and AiPy calculates turnover days, flags slow-moving items and stockout risks, recommends cleanup and replenishment, and delivers an HTML report with 6 ECharts visualizations.
**Keywords**: AiPy, warehouse inventory analysis, inventory turnover, slow-moving stock, stockout warning, SKU analysis, data visualization, ECharts, HTML report, natural language programming
---
## What is AiPy?
AiPy is an open-source AI desktop assistant developed by **Knownsec**, built around the **Python-Use** philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.
- Website: https://www.aipyaipy.com
- Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
---
## Scenario
A warehouse manager needs to analyze inventory health regularly — deciding what to clear out and what to restock.
**Pain Points**:
- **Scattered inventory data**: SKUs across multiple categories live in different Excel files, making it impossible to grasp overall inventory health
- **Hard to identify slow-moving items**: judging which products turn over too slowly by manually scanning data is inefficient and error-prone
- **No stockout warnings**: best-sellers only get noticed after they sell out, missing sales opportunities and hurting customer satisfaction
- **No basis for cleanup decisions**: whether to discount slow-moving stock or return and scrap it lacks data-driven criteria
**Goal**: From one warehouse dataset, produce SKU details, category summaries, a risk matrix, and cleanup plus replenishment recommendations.
---
## Steps
1. Open AiPy and install the **Excel Document Processing** skill from the marketplace
2. Upload the warehouse data file and enter the prompt (see "Prompt" below)
3. AiPy calculates metrics, classifies risks, generates recommendations, and outputs a visual report
### Prompt
```text
This is warehouse data. Please check the inventory, sales, statistical period, and unit fields by SKU. By default, average daily sales = sales during the period / number of days, and turnover days = current inventory / average daily sales. Help me flag slow-moving items with turnover > 90 days, high-turnover items with < 7 days, and list items with zero average daily sales separately. Also look at stockout risk where inventory is low but sales are high. Output SKU details, category summaries, a risk matrix, and cleanup plus replenishment recommendations.
```
---
## How AiPy Did It
| Step | Stage | Description |
|------|-------|-------------|
| 1 | Data generation and modeling | Automatically generated simulated warehouse data for 146 SKUs across 5 major categories (electronics, daily goods, food and beverage, maternal and baby, sports and outdoor), with 20+ fields including inventory, sales, cost, and supplier |
| 2 | Automatic core metric calculation | Computed average daily sales and turnover days, then classified risk levels by rule: slow-moving (>90 days), high-turnover (<7 days), zero-sales items, and stockout risk |
| 3 | Multi-dimensional summary analysis | Output category summaries, subcategory summaries, a risk matrix, and inventory value distribution, revealing inventory structure from macro to micro |
| 4 | Intelligent recommendation generation | Gave tiered discount strategies for slow-moving items (30%/20%/10% off), age-based handling plans for zero-sales items, and suggested replenishment quantities for stockout-risk items |
| 5 | Visual report output | Generated an HTML report with 6 interactive ECharts charts, including a risk distribution pie chart, category comparison bar-line chart, heatmap matrix, and subcategory turnover comparison |
**Tech Stack**: Python, Pandas, ECharts, HTML/CSS
---
## Results
| Traditional way | Now with AiPy |
|-----------------|---------------|
| 8+ hours | 3 minutes 22 seconds |
| Digging through Excel + manual calculation + writing the report | One prompt, fully automated |
🚀 **Over 140x efficiency gain!**
**Analysis Conclusions**:
- **Severe overstock**: 38 slow-moving items tying up 3.37 million CNY, nearly 50% of total inventory value, with maternal and baby goods plus electronics accounting for the largest share
- **Zero-sales items**: 30 SKUs with zero sales holding 1.36 million CNY in inventory, of which 13 with extremely long shelf age are recommended for direct return or scrap
- **Urgent stockouts**: 24 SKUs at stockout risk with less than 2 days of inventory remaining, requiring emergency replenishment of 19,572 units
- **Category differences**: food and beverage has the highest risk (77.4% of SKUs at risk) but the fastest turnover (23.1 days); sports and outdoor has the lowest risk (56%)
**User Takeaways**:
- **Data-driven decisions**: instead of clearing inventory by gut feeling, there is now precise data support with clear cleanup priorities
- **Risk visualization**: the heatmap matrix makes category risk distribution obvious at a glance, easy for management to grasp
- **Clear action guide**: every at-risk SKU comes with concrete recommendations (discount / replenishment quantity / handling method) that can be executed directly
---
## Screenshots
📊 [Complete Warehouse Inventory Analysis Report (HTML)](https://www.aipyaipy.com/cases/case61/warehouse_report.html)
---
## FAQ
**Q1: Does AiPy require an internet connection?**
A: No. AiPy runs fully locally — your warehouse data never leaves your computer, keeping business data secure.
**Q2: Do I need to know how to code?**
A: No. Just upload the spreadsheet and describe your analysis needs in natural language, and AiPy generates and runs the analysis code.
**Q3: Which operating systems does AiPy support?**
A: macOS / Windows / Linux desktops.
**Q4: Can the turnover-day rules be changed?**
A: Yes. Simply state it in the prompt — for example, changing the slow-moving threshold from 90 days to 60 days — and AiPy recalculates accordingly.
**Q5: Can the report be exported in other formats?**
A: This case outputs an HTML report. For Excel or Word versions, add that requirement to the prompt.
---
## Related Links
- Original case study: https://www.aipyaipy.com/cases/case61/
- AiPy website: https://www.aipyaipy.com
- GitHub repository: https://github.com/wuxyknownsec/awesome-aipy
