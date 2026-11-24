# 不同语言讲解核验

本地演练资料记录普通话和晋地方言讲解版本、知识题目对应关系、课程轮次、并行试填和匿名作答。题目关系可能是等值、改写或拆分。

## Local checks

Python 3.9 or newer is sufficient. The repository has no third-party runtime dependencies.

Run `python3 input_audit.py` to verify the declared files and columns. Run `python3 -m unittest discover -s tests -v` to check the prepared input contract.

The records are synthetic fixtures. Empty values and status labels retain their literal input meaning. The manifest lists file columns and the stable row identifier used by the input audit.
