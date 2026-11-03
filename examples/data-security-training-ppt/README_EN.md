# AiPy in Action: Generate a Data Security & Privacy Protection Training PPT from One Prompt (14 Native Editable Slides)
> Describe the training topic, audience, content structure, and illustration requirements, and AiPy researches authoritative data online, generates 6 themed illustrations, draws 14 slides page by page, and runs strict quality checks.
**Keywords**: AiPy, PPT generation, data security training, privacy protection, information security, corporate training, native editable PPTX, AI illustration, natural language programming
---
## What is AiPy?
AiPy is an open-source AI desktop assistant developed by **Knownsec**, built around the **Python-Use** philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.
- Website: https://www.aipyaipy.com
- Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
---
## Scenario
A corporate security training lead needs to create a PPT for an information security training session aimed at new employees, titled "Data Security and Privacy Protection".
**Pain Points**:
- **Scattered content**: security training materials are fragmented, and authoritative data plus typical cases must be researched and filtered by hand
- **Hard to source illustrations**: the cover, section pages, and risk classification pages all need professional visuals, and finding and editing images costs time and money
- **Tedious layout**: aligning 14 slides page by page, with consistent colors and font hierarchies, is all manual work
- **Compliance concerns**: citing cases risks exposing company names, and anonymizing them while verifying sources is painstaking
**Goal**: Produce a 14-slide, natively editable, visually consistent, and compliance-safe training PPTX.
---
## Steps
1. Open AiPy and install the **PPT Generation** Skill and the **Graphic & Ad Design** agent from the marketplace
2. Describe the training topic, audience, content structure, and illustration requirements in one go (see "Prompt" below)
3. AiPy researches authoritative data online, generates 6 themed illustrations, draws 14 slides page by page, and runs strict quality checks
4. Refine conversationally: say "change this", "switch the color scheme", or "add a page" and get instant revisions
### Prompt
```text
Task objective: Create a PPT for an information security training session aimed at new corporate employees, titled "Data Security and Privacy Protection". The content should include: a review of typical domestic and international data breach and privacy infringement incidents, classification and root-cause analysis of data security risks (such as insider violations, third-party supply chains, out-of-control permissions, phishing attacks, etc.), the impact of these risks on organizations and individuals, targeted countermeasures (policies and processes, technical protection, staff awareness training, incident response), and industry best practices worth learning from.
Data sources: Use public reports, publicly released reports from authoritative institutions, and publicly available industry cases (such as public statistics on data breaches and public compliance guidelines); do not rely on any internal documents or private data. Anonymize all cases — no real company names or personal information.
Processing requirements: Keep the structure clear, organized as "incident review — risk analysis — impact assessment — countermeasures — best practices"; ensure claims are evidence-based and avoid empty slogans; use language suitable for both spoken delivery and on-screen reading during training; the cover and key pages (section pages, risk classification page, countermeasure page, conclusion page) should include topic-relevant diagrams or illustrations, while other pages use clean layouts and bullet points to avoid large blocks of plain text, with a consistent color scheme and professional formatting; illustrations should be AI-generated or public assets.
Deliverable: Output a PPTX file named task-035-presentation.pptx.
```
---
## How AiPy Did It
| Step | Stage | Description |
|------|-------|-------------|
| 1 | Online research of authoritative data | Automatically retrieves public reports such as IBM's Cost of a Data Breach Report and Verizon DBIR plus domestic enforcement bulletins, building a fact file with sources (15 external facts), with all cases anonymized |
| 2 | AI generates 6 themed illustrations | Calls the Graphic & Ad Design agent to produce a cover key visual, section illustrations, a four-panel risk comic, a defense-in-depth diagram, and a team collaboration closing image, all in a deep blue-teal palette matching the slides |
| 3 | Draws 14 slides page by page | Organized as "incident review — risk analysis — impact assessment — countermeasures — best practices", including a 68% human-factor donut chart and a cost comparison bar chart as native editable charts and flow diagrams |
| 4 | Strict QA and PPTX export | Runs two rounds of automated QA (early gate + final gate) with 52 fixes, passing with zero errors and exporting a 14-slide native editable DrawingML PPTX |
**Tech Stack**: Python, python-pptx, PPT Generation Skill, Graphic & Ad Design agent
---
## Results
| Traditional way | Now with AiPy |
|-----------------|---------------|
| 6+ hours | About 12 minutes |
| Research + design + illustrations + layout | One prompt, fully automated |
🚀 **About 30x efficiency gain!**
**Slide Highlights**:
- **Evidence-based data**: 68% of breaches involve human factors, average cost of 4.88 million USD, malicious insider attacks at 4.99 million USD — all from public authoritative reports
- **Compliance-safe**: no real company names or personal information appear in any case, so citations are risk-free
- **Natively editable**: text, shapes, and charts are all native PPT objects — open and edit text or colors directly, not a collage of images
- **Visually consistent**: a deep blue background with teal light effects runs through all 14 slides, with AI illustrations blending seamlessly into the layout for excellent projection quality
---
## Screenshots
📽️ [Data Security & Privacy Protection Training PPT (PDF Preview)](https://www.aipyaipy.com/cases/case341/task-035-presentation.pdf)
---
## FAQ
**Q1: Does AiPy require an internet connection?**
A: This case needs to retrieve public authoritative reports and enforcement bulletins online, so an internet connection is required. AiPy itself runs fully locally and never uploads your data.
**Q2: Do I need design skills?**
A: No. Just describe the training topic, audience, content structure, and illustration requirements, and AiPy handles research, illustrations, and layout.
**Q3: Which operating systems does AiPy support?**
A: macOS / Windows / Linux desktops.
**Q4: Can the generated PPT be edited?**
A: Yes. The export is a natively editable PPTX, so text, shapes, and charts can be modified directly in Office or WPS.
**Q5: Are there compliance risks in citing cases?**
A: No. All cases are anonymized with no real company names or personal information, and every data point is sourced.
---
## Related Links
- Original case study: https://www.aipyaipy.com/cases/case341/
- AiPy website: https://www.aipyaipy.com
- GitHub repository: https://github.com/wuxyknownsec/awesome-aipy
