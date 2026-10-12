AiPy in Action: Build a 4S Dealership Visitor Management System with One Prompt (Python + SQLite + PyQt)
No coding required — use natural language to have AiPy build a local desktop management system from scratch, packaged as a standalone EXE.
Keywords: AiPy, 4S dealership visitor management, Python desktop app, SQLite, PyQt, PyInstaller, natural language programming, AI development

What is AiPy?
AiPy is an open-source AI desktop assistant developed by Knownsec, built around the Python-Use philosophy:
it translates natural language directly into Python code and executes it, so AI truly "operates your computer" instead of just chatting.

Website: 
https://www.aipyaipy.com
Highlights: local execution, code as agent, MCP/Skills support, cross-platform (macOS / Windows / Linux)
Scenario
The operations director of an Audi 4S dealership needed a visitor registration and management system to replace the paper logbook.
Pain Points:

Customers queue up to fill in forms by hand, and handwriting is hard to read
The logbook is left around and easily damaged or lost, wasting valuable leads
Daily foot traffic is entered manually into Excel — time-consuming and error-prone
When multiple salespeople serve the same customer, there is no record, making commission disputes hard to trace
Goal: Build a visitor management system that runs fully locally, requires no network connection, and can be packaged as an EXE.
Steps
Open AiPy and install the skill One-Stop Development Studio from the marketplace
Enter the prompt (see "Prompt" below)
AiPy automatically completes requirement analysis, database design, UI development, feature implementation, and packaging
Prompt
How AiPy Did It
Step	Stage	Description
1	Requirement analysis	Clarified core business logic for registration, query, and reporting
2	Database design	Lightweight SQLite tables with pre-seeded models and salespeople
3	UI development	Business-style PyQt UI with adaptive window layout
4	Feature implementation	Phone number validation, duplicate-lead prevention, live dashboard stats
5	Packaging & delivery	PyInstaller-generated EXE, runs fully offline
Tech Stack: Python, SQLite, PyQt/PySide, PyInstaller		
Results
Traditional way	Now with AiPy
2h/day entering data into Excel	5min one-click entry at the front desk
Error-prone month-end reconciliation	Automatic dashboard statistics
No evidence for commission disputes	Full traceability end to end
🚀 Daily management time cut by 96%!	
User Takeaways:	
Business users can define requirements too: no coding needed — just describe the management logic clearly
No more manual reconciliation: data is stored in real time, with one-click Excel export
Local deployment is more secure: customer data never leaves the dealership, meeting auto-retail compliance requirements
## Screenshots
![4S Dealership Visitor Management System UI](https://www.aipyaipy.com/cases/case2/材料/4S店访客管理系统.png)
FAQ
Q1: Does AiPy require an internet connection?
A: No. AiPy runs fully locally — your data never leaves your computer, keeping customer privacy secure.
Q2: Do I need to know how to code?
A: No. Just describe your needs in natural language, and AiPy generates and runs the Python code for you.
Q3: Which operating systems does AiPy support?
A: macOS / Windows / Linux desktops.
Q4: Can the generated program be packaged as an EXE?
A: Yes. AiPy calls PyInstaller to package it automatically, producing an EXE that runs directly on Windows.
Q5: Where is the database stored?
A: It uses a local SQLite database, stored on your own machine with no server dependency.
Related Links
Original case study: 
https://www.aipyaipy.com/cases/case2/
AiPy website: 
https://www.aipyaipy.com
GitHub repository: 
https://github.com/wuxyknownsec/awesome-aipy
