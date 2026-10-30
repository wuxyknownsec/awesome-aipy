# AiPy in Action: Generate a DJI Osmo Pocket 3 Product Research Report from One Prompt (Single-File HTML)
> Describe your need in plain language, and AiPy verifies official specs, aggregates three-source reviews, generates a 7-module report, and adds 4 AI-generated scene illustrations.
**Keywords**: AiPy, product research, competitive analysis, DJI Osmo Pocket 3, gimbal camera, HTML report, data analysis, AI illustration, natural language programming
---
## What is AiPy?
AiPy is an open-source AI desktop assistant developed by **Knownsec**, built around the **Python-Use** philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.
- Website: https://www.aipyaipy.com
- Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
---
## Scenario
A tech enthusiast wants to produce a product research report on the **DJI Osmo Pocket 3** gimbal camera, aimed at ordinary consumers and content creators to help them decide whether it is worth buying.
**Pain Points**:
- **Hard to verify specs**: official site, e-commerce listings, and review articles each say something different, with key specs scattered everywhere
- **Hard to tell real reviews from marketing**: sponsored content is mixed with genuine feedback, making it unclear which pros and cons are widely agreed upon
- **No clear basis for a decision**: unsure whether it suits them, afraid of spending thousands only to let it gather dust
**Goal**: Produce a well-structured, source-traceable research report with audience-specific conclusions (single-file HTML).
---
## Steps
1. Open AiPy and install the **Web Frontend Development** Skill and the **Graphic & Ad Design** agent from the marketplace
2. Send the task prompt to AiPy as-is (see "Prompt" below)
3. AiPy fetches the official product page to verify specs, summarizes media reviews and user feedback, generates a 7-module report, and adds 4 AI-generated scene illustrations
4. Refine conversationally: say "make the conclusion sharper" or "add a price comparison section" and get instant revisions
### Prompt
```text
Task objective: Write a product research report on the "DJI Osmo Pocket 3 pocket gimbal camera" for ordinary consumers and content creators, to help them decide whether it is worth buying.
Data sources: Use publicly available official product pages, public e-commerce specs and user reviews, and public media reports and review articles; do not rely on any local private files or internal systems. If sample data is needed, construct it yourself and mark it as sample data.
Processing requirements: The report must include the following modules — (1) product positioning and core selling points; (2) feature highlights (gimbal stabilization, 1-inch sensor, rotating touchscreen, audio and battery life, etc.); (3) an objective comparison of pros and cons (listed item by item, avoiding exaggeration); (4) recommendations on target users and typical use cases; (5) price range and purchase channels (only public e-commerce platforms and the official store; no specific accounts or internal links); (6) a brief side-by-side comparison table with competitors in the same price range. All information must be labeled by source type (official/media/user review), and uncertain information marked as "to be verified".
Deliverable: Output a single-file HTML page with clear heading hierarchy, comparison tables, and card-style key points, with a consistent color scheme and professional layout; the cover and key section pages (such as highlights, comparison, and conclusion) should include topic-relevant diagrams or product scene illustrations (AI-generated or public assets), while other pages use clean typography to avoid large blocks of plain text; the page must adapt to both desktop and mobile browsing.
```
---
## How AiPy Did It
| Step | Stage | Description |
|------|-------|-------------|
| 1 | Auto-verify official specs | Fetch DJI's official product and spec pages, checking sensor, screen, battery life, charging, and other hard specs item by item |
| 2 | Aggregate three-source reviews | Summarize common ground and disagreements across public media reviews and e-commerce/community user feedback, distinguishing source types |
| 3 | Structured report generation | Generate key-point cards and comparison tables across 7 modules: positioning, highlights, pros and cons, target users, pricing, competitors, conclusion |
| 4 | Illustrations and responsive layout | Call the Graphic & Ad Design agent to generate 4 themed scene illustrations, outputting a dark studio-style single-file HTML that adapts to desktop and mobile |
**Tech Stack**: Python, Web Frontend Development Skill, Graphic & Ad Design agent, HTML/CSS
---
## Results
| Traditional way | Now with AiPy |
|-----------------|---------------|
| 4+ hours | About 10 minutes |
| Reading reviews, taking notes, doing layout | Automated research + writing + illustration |
🚀 **About 24x efficiency gain!**
**Page Highlights**:
- **Traceable sources**: every piece of information carries a badge, with official/media/user review color-coded and uncertain items clearly flagged
- **Audience-specific conclusions**: no one-size-fits-all verdict — three tiers (worth buying / wait and see / not recommended) based on usage frequency and scenarios
- **Intuitive comparison**: a four-way competitor table covering all-in-one gimbal cameras vs. the previous generation vs. phone gimbals vs. mirrorless setups
---
## Screenshots
📊 [DJI Osmo Pocket 3 Product Research Report (HTML)](https://www.aipyaipy.com/cases/case186/assets/report.html)
---
## FAQ
**Q1: Does AiPy require an internet connection?**
A: This case needs to fetch public official specs and media reports, so an internet connection is required. AiPy itself runs fully locally and never uploads your data.
**Q2: Do I need to know how to code?**
A: No. Just describe your need in plain language, and AiPy handles research, writing, and layout automatically.
**Q3: Which operating systems does AiPy support?**
A: macOS / Windows / Linux desktops.
**Q4: Can the report be revised?**
A: Yes. Say something like "make the conclusion sharper" or "add a price comparison section" and AiPy responds instantly.
**Q5: Does the report work on mobile?**
A: Yes. The single-file HTML adapts to both desktop and mobile.
---
## Related Links
- Original case study: https://www.aipyaipy.com/cases/case186/
- AiPy website: https://www.aipyaipy.com
- GitHub repository: https://github.com/wuxyknownsec/awesome-aipy
