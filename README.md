# 问卷趋势衔接分析

本地演练资料记录问卷版本、题目映射、课程轮次、并行试填和匿名作答。分值标签只按所列版本解释，未回答原因可能不同。

## Local checks

Python 3.9 or newer is sufficient. The repository has no third-party runtime dependencies.

Run `python3 input_audit.py` to verify the declared files and columns. Run `python3 -m unittest discover -s tests -v` to check the prepared input contract.

The records are synthetic fixtures. Empty values and status labels retain their literal input meaning. The manifest lists file columns and the stable row identifier used by the input audit.
