---
name: data-analysis
description: Explore, clean and summarize tabular data (CSV/XLSX/SQL) and report findings. Use for analytics questions and ad-hoc reporting.
---
# Data Analysis

## Workflow
1. **Clarify** the question and the decision it supports.
2. **Profile** the data: shape, types, nulls, duplicates, ranges.
3. **Clean**: fix types, handle missing values explicitly, document each change.
4. **Analyze**: aggregate, segment, compare; sanity-check totals against the source.
5. **Report**: lead with the answer, then evidence, then caveats.

## Rules
- Never silently drop rows; report counts removed and why.
- State assumptions and data limitations.
- Choose the simplest chart that answers the question.
