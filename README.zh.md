# 钉钉悟空技能库 (DingTalk Wukong Skills)

钉钉生态系统与专业文档处理的 Agent 技能精选集。

> [!IMPORTANT]
> 本项目是从 Wukong v0.9.2 (arm64) 中提取的技能集合。
> 这些技能已针对 [cli-gemini](https://github.com/google-gemini/cli)、[claude-code](https://github.com/anthropics/claude-code) 和 [codex](https://github.com/vercel-labs/codex) 等 Agent 环境进行了优化。

## 安装

要安装本仓库中的所有技能：

```bash
npx --yes skills add stvlynn/dingtalk-wukong-skills --skill='*' --full-depth
```

或者进行全局安装：

```bash
npx --yes skills add stvlynn/dingtalk-wukong-skills --skill='*' --full-depth -g
```


## 技能列表

本集合提供了一套完整的办公自动化和出行辅助技能。

### 钉钉工作台 (DingTalk Workspace)

用于与钉钉产品交互的定制化技能。

| 技能 | 描述 | 来源 |
| :--- | :--- | :--- |
| [dws](./dws) | 全面的钉钉工作台操作（OA、待办、日历、文档等） | Wukong v0.9.2 |

### 文档处理 (Document Processing)

用于高保真处理 Office 和 PDF 文档的专业工具。

| 技能 | 描述 | 来源 |
| :--- | :--- | :--- |
| [docx](./docx) | 支持修订和格式保留的高级 Word 文档处理 | Wukong v0.9.2 |
| [xlsx](./xlsx) | 支持公式和数据分析的 Excel 表格处理 | Wukong v0.9.2 |
| [pptx](./pptx) | PPT 演示文稿处理，包括 HTML 转 PPT 功能 | Wukong v0.9.2 |
| [pdf](./pdf) | PDF 文档处理，支持文本/表格提取和表单填写 | Wukong v0.9.2 |
| [pdf-convert-to-word](./pdf-convert-to-word) | 专业的 PDF 转 Word/Markdown 工具 | Wukong v0.9.2 |

### 出行与信息 (Travel & Information)

用于出行和本地生活的实时查询技能。

| 技能 | 描述 | 来源 |
| :--- | :--- | :--- |
| [12306-train-query](./12306-train-query) | 实时 12306 火车车次及余票查询 | Wukong v0.9.2 |
| [ctrip-flight-search](./ctrip-flight-search) | 通过携程进行全球航班搜索和价格对比 | Wukong v0.9.2 |
| [dianping-info-query](./dianping-info-query) | 来自大众点评的本地商户信息和评论 | Wukong v0.9.2 |

### 开发者工具 (Developer Tools)

| 技能 | 描述 | 来源 |
| :--- | :--- | :--- |
| [skill-creator](./skill-creator) | 用于设计、校验和打包新 Agent 技能的工具 | Wukong v0.9.2 |

