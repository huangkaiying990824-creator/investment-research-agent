# Investment Research Agent

这是一个用于一级市场投研的 Codex Skill Library。

## 目标

根据企业资料和公开资料，辅助完成：

1. 公司基本面分析
2. 行业研究
3. 产业链拆解
4. 竞品对比
5. 投资 memo 生成

## Skills

当前包含：

- company_research：公司分析
- industry_research：行业研究
- value_chain_mapping：产业链拆解
- competitor_benchmark：竞品对比
- investment_memo：投资 memo

## 输入资料

企业资料放在：

inputs/company_materials/

## 输出报告

报告输出到：

outputs/reports/

## 使用方式

让 Codex 读取 inputs/company_materials/ 下的企业资料，并调用 .codex/skills/ 下的投研 Skill，生成结构化投资 memo。
