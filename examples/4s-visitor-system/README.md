AiPy 实战：用一句话开发 4S 店访客管理系统（Python + SQLite + PyQt）
不用写一行代码，用自然语言让 AiPy 从零开发一套可打包成 EXE 的本地桌面管理系统。
关键词：AiPy、4S 店访客管理系统、Python 桌面应用、SQLite、PyQt、PyInstaller、自然语言编程、AI 开发

什么是 AiPy？
AiPy（爱派）是由**北京知道创宇（Knownsec）**研发的开源 AI 桌面助手，核心理念是 Python-Use：
把自然语言直接翻译成 Python 代码并执行，让 AI 真正「操作你的电脑」，而不是只聊天。

官网：
https://www.aipyaipy.com
特点：本地执行、代码即代理、支持 MCP/Skills、跨平台（macOS / Windows / Linux）
场景
某奥迪 4S 店运营总监，需要一套访客登记管理系统来替代纸质登记本。
痛点：

客户手写填表排队久，字迹潦草难辨认
登记本随意摆放，客户线索易损坏丢失
每日客流全靠 Excel 手动录入，耗时易错
多销售接待同一客户缺乏记录，撞单抢单难追溯
目标：做一个纯本地运行、不依赖网络、可打包成 EXE 的访客管理系统。
操作步骤
打开 AiPy，在集市安装 skill：一站式开发坊
输入提示词（见下方「提示词」）
AiPy 自动完成需求分析、数据库设计、界面开发、功能实现与打包交付
提示词
AiPy 实现过程
步骤	环节	说明
1	需求分析梳理	明确登记、查询、报表等核心业务逻辑
2	数据库设计	SQLite 轻量建表，预置车型与销售字典
3	界面开发	PyQt 商务风 UI，自适应窗口布局
4	功能实现	手机号校验、防撞单、实时看板统计
5	打包交付	PyInstaller 生成 EXE，断网纯本地运行
技术栈：Python、SQLite、PyQt/PySide、PyInstaller		
效果
传统方式	现在用 AiPy
2h/天 手工录入 Excel	5min 前台一键录入
月底盘点易出错	看板自动统计
撞单纠纷无据可查	全程留痕可溯
🚀 每日管理耗时缩短 96%！	
使用心得：	
业务人员也能提需求：不用懂代码，说清管理逻辑就能落地
告别手工对账：数据实时入库，一键导出 Excel 报表
本地部署更安全：客户隐私不出店，符合汽车零售合规要求
## 截图
![4S店访客管理系统运行界面](https://www.aipyaipy.com/cases/case2/材料/4S店访客管理系统.png)
常见问题（FAQ）
Q1：AiPy 需要联网吗？
A：不需要。AiPy 支持纯本地运行，数据不上传云端，客户隐私安全有保障。
Q2：需要会编程吗？
A：不需要。用自然语言描述需求即可，AiPy 会自动生成并执行 Python 代码。
Q3：AiPy 支持哪些操作系统？
A：支持 macOS / Windows / Linux 桌面端。
Q4：生成的程序能打包成 EXE 吗？
A：可以。AiPy 会调用 PyInstaller 自动打包，生成可在 Windows 上直接运行的 EXE 程序。
Q5：数据库存在哪里？
A：使用 SQLite 本地数据库，数据文件保存在本机，不依赖任何服务器。
相关链接
案例原文：
https://www.aipyaipy.com/cases/case2/
AiPy 官网：
https://www.aipyaipy.com
GitHub 仓库：
https://github.com/wuxyknownsec/awesome-aipy
