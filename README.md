# answer-engines-country-codes

此仓库包含各类回答引擎使用的国家代码列表。每个 CSV 文件对应一个不同的引擎，包含该引擎识别或支持的国家代码与国家名称。

## CSV 文件

- `chatgpt_countries.csv`
- `copilot_countries.csv`
- `gemini_countries.csv`
- `perplexity_countries.csv`
- `google_aimode_countries.csv`
- `meta_countries.csv`
- `grok_countries.csv`

### 结构

所有 CSV 文件包含以下列：

- `Country Code`：ISO 3166-1 alpha-2 国家/地区代码（例如：`US`、`GB`、`IN`）。
- `Country`：该引擎所认可的国家名称（不同文件间可能略有差异）。

### 目的

这些文件用于对比不同回答引擎对国家的支持范围与命名规范。可用于数据校验、分析，或与需要国家代码映射的服务进行集成。
