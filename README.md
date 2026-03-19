# DingTalk Wukong Skills

> 集成 10+ 款深度优化的 AI 技能，助力 AI Agent 掌控钉钉生态与专业文档处理。

[![Skills Count](https://img.shields.io/badge/Skills-10-blue.svg)](#技能清单)
[![Source](https://img.shields.io/badge/Source-Wukong%20v0.9.2-orange.svg)](https://github.com/stvlynn/dingtalk-wukong-skills)
[![CLI](https://img.shields.io/badge/Tools-Skills%20CLI-green.svg)](https://github.com/vercel/skills)

本项目是从 Wukong v0.9.2 提取并整理的技能仓库。所有技能均已适配 [Skills CLI](https://github.com/vercel/skills)，可直接安装至你的 AI Agent 环境中（如 cli-gemini, claude-code, codex 等）。


---

## 技能清单

我们将技能分为四大核心类别，满足不同场景需求：

### 钉钉生态 (DingTalk Workspace)
| Skill ID | 功能描述 | 典型用途 |
| :--- | :--- | :--- |
| **`dws`** | 钉钉工作台全能入口 | 操作审批、待办、日历、文档、群聊、AI 表格、钉盘等 |

### 文档处理 (Office & PDF)
| Skill ID | 功能描述 | 特点 |
| :--- | :--- | :--- |
| **`docx`** | Word 文档专家 | 深度处理 .docx，支持修订、批注与格式保留 |
| **`xlsx`** | Excel 数据大师 | 支持公式计算、数据分析、多格式互转 (.xlsx/.csv) |
| **`pptx`** | PPT 演示助手 | 支持 HTML 转 PPT、内容提取与批量编辑 |
| **`pdf`** | PDF 全能工具 | 文本/表格提取、表单填写、拆分合并 |
| **`pdf-convert-to-word`** | PDF 格式转换 | 精准将 PDF 转换为可编辑的 Word 或 Markdown |

### 生活与出行 (Travel & Info)
| Skill ID | 功能描述 | 典型用途 |
| :--- | :--- | :--- |
| **`12306-train-query`** | 火车票实时查询 | 查询班次、余票、票价及正晚点信息 |
| **`ctrip-flight-search`** | 携程航班搜索 | 搜索全球单程/往返机票，对比价格与时刻 |
| **`dianping-info-query`** | 大众点评查询 | 获取门店评分、地址、人均消费及精华点评 |

### 开发工具 (Developer Tools)
| Skill ID | 功能描述 | 典型用途 |
| :--- | :--- | :--- |
| **`skill-creator`** | 技能开发套件 | 自动化设计、校验与打包自定义 AI 技能 |

---

## 高级安装选项

| 场景 | 命令示例 |
| :--- | :--- |
| **按需安装** | `npx skills add stvlynn/dingtalk-wukong-skills --skill dws --skill pdf --full-depth` |
| **全局安装** | `npx skills add stvlynn/dingtalk-wukong-skills --all --full-depth -g` |
| **指定 Agent** | `npx skills add stvlynn/dingtalk-wukong-skills --all --full-depth --agent claude-code -y` |
| **本地开发测试** | `npx skills add ./ --list --full-depth` |
