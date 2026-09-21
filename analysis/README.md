# 研究方法 | Research Methods

## 研究链路

1. 问卷设计与数据质量筛选（Questionnaire Design & Data Quality）。
2. 探索性分析与量表整理（Exploratory Analysis）。
3. 因子分析与潜变量构建（Factor Analysis）。
4. 基于标准化因子得分的骑手画像（K-means Clustering）。
5. 回归、交互效应和异质性检验（OLS / Interaction / Heterogeneity）。
6. 开放题定性补充与治理建议（Qualitative Coding）。

## 变量说明

- `F1`：系统/平台体验因子。
- `F2`：工作压力或损耗因子。
- `Q37`、`Q38`、`Q39`：职业态度结果变量。

## 关键结果

交互检验文件记录了 `N = 542` 的模型结果，多个结果变量的 `R²` 位于 `0.380–0.450` 区间。`F1` 在主要模型中保持正向关联，聚类结果用于补充群体画像和差异化治理解释。

## 复现边界

Notebook 默认读取本地 `clean.xlsx`。该文件不随仓库提供，运行者应使用经过授权和脱敏的本地数据；仓库仅提供分析代码与聚合结果。
