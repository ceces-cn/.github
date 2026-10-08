# 贡献指南

感谢参与！本项目由 **中电协创新融合（北京）信息科技研究院** 维护，欢迎通过 Issue / Pull Request 参与。

## 提交前
1. 先搜 Issue/Discussions，避免重复；
2. 大改动请先开 Issue 说明动机与方案，达成一致再动手；
3. 一个 PR 只做一件事，附测试或复现步骤。

## 提交规范
- Commit 用 `Signed-off-by`（`git commit -s`），表示同意 DCO；
- 提交信息：`<type>(<scope>): <subject>`，type ∈ feat/fix/docs/refactor/test/chore；
- 中文或英文均可，同一 PR 保持一致。

## 代码要求
- 通过仓库 CI（lint + test）；
- 新增功能带测试；改动公共接口须更新文档。

## 评审
- 至少 1 名维护者 approve 后合并；争议由维护者裁定。
