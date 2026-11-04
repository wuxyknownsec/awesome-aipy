# AiPy 实战：一句话自动打印局域网 PDF 文件（PowerShell + 打印机控制）
> 只要说一句「帮我用它打印 c:\1.pdf」，AiPy 自动扫描局域网打印机、设为默认、调用系统命令完成打印。
**关键词**：AiPy、打印机自动化、局域网打印机、PDF 打印、PowerShell、办公自动化、批量打印、自然语言编程
---
## 什么是 AiPy？
AiPy（爱派）是由**北京知道创宇（Knownsec）**研发的开源 AI 桌面助手，核心理念是 **Python-Use**：
把自然语言直接翻译成 Python 代码并执行，让 AI 真正「操作你的电脑」，而不是只聊天。
- 官网：https://www.aipyaipy.com
- 特点：本地执行、代码即代理、支持 MCP/Skills、跨平台（macOS / Windows / Linux）
---
## 场景
一位办公室职员，需要打印局域网内一台打印机上的 PDF 文件。
**痛点**：
- **不知道打印机 IP 和名称**：局域网里的打印机怎么找？网络路径怎么填？
- **驱动安装麻烦**：换台电脑就要重新装驱动，IT 不在就卡住了
- **PDF 打印格式错乱**：直接拖进去经常出现字体缺失、排版变形
- **不会写脚本批量打印**：几十份文件一个个点「打印」按钮，效率极低
**目标**：一句话让 AiPy 自动找到打印机并成功打印 PDF。
---
## 操作步骤
1. 打开 AiPy，在集市安装智能体：**打印机控制**
2. 上传要打印的文件，输入提示词（见下方「提示词」）
3. AiPy 自动扫描局域网、设为默认打印机、调用系统命令完成打印
### 提示词
```text
局域网内有一台打印机，请帮我用它打印c:\1.pdf。
```
---
## AiPy 生成的核心指令
```
# 扫描局域网，发现可用打印机
Get-Printer | Select-Object Name, DriverName, PortName
# 设置默认打印机（按发现的打印机名）
(New-Object -ComObject WScript.Network).SetDefaultPrinter("\\192.168.x.x\PrinterName")
# 调用系统命令打印 PDF
Start-Process -FilePath "c:\1.pdf" -Verb Print -Wait
```
---
## AiPy 实现过程
| 步骤 | 环节 | 说明 |
|------|------|------|
| 1 | 扫描局域网打印机 | 通过 PowerShell 列出当前可用打印机及其端口信息 |
| 2 | 自动识别目标打印机 | 根据网络环境选择合适的打印机设备 |
| 3 | 设置为默认打印机 | 通过 WScript.Network 将选定打印机临时设为默认 |
| 4 | 调用系统打印命令 | 使用 Start-Process -Verb Print 直接打印 PDF，格式完整保留 |
| 5 | 确认打印任务完成 | 等待打印队列清空，输出执行结果 |
**技术栈**：PowerShell、WScript.Network COM 对象、Start-Process
---
## 效果
| 以前的做法 | 现在用 AiPy |
|-----------|------------|
| 15~30min | ~30s |
| 查打印机 IP | 一句话触发 |
| 手动添加网络打印机 | 自动发现打印机 |
| 安装/更新驱动 | 直接打印成功 |
🖨️ **从「找 IT 帮忙」到「自己 30 秒搞定」**
**使用心得**：
- **不用知道打印机 IP**：让 AiPy 自己去扫，找到了直接用，省掉查网络配置这一步
- **PDF 格式完好无损**：系统级打印命令直接调用，比用浏览器打印靠谱多了
- **可以轻松改成批量打印**：告诉 AiPy「把这个文件夹里的所有 PDF 都打印」，它会自动循环
- **IT 不在也能自己搞定**：不用等人，不用装驱动，一句话就解决
---
## 截图
![Canon 局域网打印机成功打印](https://www.aipyaipy.com/cases/case26/images/pic_20.png)
---
## 常见问题（FAQ）
**Q1：AiPy 需要联网吗？**
A：不需要外网。AiPy 本身纯本地运行，本案例只在局域网内操作打印机，数据不出内网。
**Q2：需要会编程吗？**
A：不需要。用一句大白话说出打印需求即可，AiPy 自动生成 PowerShell 指令并执行。
**Q3：AiPy 支持哪些操作系统？**
A：AiPy 主程序支持 macOS / Windows / Linux，本案例的打印脚本基于 Windows PowerShell，需在 Windows 环境运行。
**Q4：能批量打印吗？**
A：可以。只需说「把这个文件夹里的所有 PDF 都打印」，AiPy 会自动循环处理。
**Q5：找不到打印机怎么办？**
A：AiPy 会先执行 Get-Printer 扫描可用设备，如果列表为空，需要先确认打印机已开机并连入同一局域网。
---
## 相关链接
- 案例原文：https://www.aipyaipy.com/cases/case26/
- AiPy 官网：https://www.aipyaipy.com
- GitHub 仓库：https://github.com/wuxyknownsec/awesome-aipy
