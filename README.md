# SMBU-CA 招新报名数据清洗与统计工具

深圳北理莫斯科大学计算机协会（SMBU·CA）招新报名表（问卷导出 CSV）的
读入概览、校验清洗、统计分析小工具。

> 本仓库按三个需求分三次 PR 迭代开发：
> - PR #1：读入与概览
> - PR #2：校验与清洗（问题清单导出）
> - PR #3：统计与导出
>
> 完整使用说明、校验规则与边界假设见 README 后续章节（随各次 PR 逐步完善）。

## 环境

- Python 3.8+（仅标准库，无第三方依赖）
- 无需安装任何包

## 快速开始（随 PR #1 后可用）

```bash
python recruit_tool.py overview --input data/raw/2026-recruit-signup.csv
```

> AI生成
