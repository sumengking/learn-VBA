# 不背单词｜精算英语词本 v1.0

这是一个按主题拆分的精算英语词本，文件采用 **UTF-8 TXT**，每行一个英文词条，便于导入「不背单词」自制词书。

## 目录

- `01_cm1_life_finance.txt` — CM1 / 寿险精算 / 利息理论 / 现金流：117 词
- `02_cs_statistics_models.txt` — CS1/CS2 / 概率统计 / 随机模型 / 时间序列：147 词
- `03_general_insurance_reserving.txt` — 非寿险 / Claims / Reserving / Reinsurance：131 词
- `04_risk_business_professional.txt` — 风险管理 / 商业 / 治理 / 专业实践：136 词
- `actuarial_all.txt` — 合并去重版：471 词

## 不背单词导入

1. 登录不背单词网页版。
2. 打开自定义词书/上传词书功能。
3. 上传任意 `.txt` 文件。
4. 让平台识别词条后，填写词书名称和描述。
5. 在 App 内选择对应的自制词书开始学习。

## 设计原则

- 采用单行单词格式，优先保证不背单词识别率。
- 暂不把多词术语直接写成一行，例如 `present value`、`loss development factor`。
- 多词术语拆解为高频核心词，如 `present`、`value`、`development`、`factor`。
- 去除了同一本词书内重复词。
- 词表围绕 IFoA 核心模块与精算实践主题组织。

## 后续版本

- Life Insurance / Pensions 专项
- General Insurance Pricing 专项
- Actuarial Data Science / Python / R 专项
- 中文释义与专业例句（单独 CSV/Markdown）
