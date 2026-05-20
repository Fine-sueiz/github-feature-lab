# Day 2: 分支与 Pull Request

## 今天要理解的概念

- Branch: 从主线复制出来的一条独立开发线。
- Pull Request: 请求把某个分支的改动合并回主分支。
- Base branch: 想要合并进去的目标分支，通常是 `main`。
- Compare branch: 带着新改动的来源分支，比如 `feature/day2-profile`。
- Merge: PR 检查完成后，把分支改动合并到目标分支。

## 练习分支

当前练习分支:

```text
feature/day2-profile
```

## PR 描述模板

```markdown
## 做了什么

- 更新 README 的学习进度。
- 新增 Day 2 分支和 PR 学习笔记。

## 为什么做

用于练习 GitHub flow: 创建分支、提交修改、发起 PR、检查差异、合并回 main。

## 检查清单

- [ ] 已查看 Files changed
- [ ] 已确认提交记录清晰
- [ ] 已准备合并到 main
```

## 给自己的复盘问题

- 为什么不要直接在 `main` 上做所有修改？
- PR 页面里的 Conversation、Commits、Checks、Files changed 分别看什么？
- 合并 PR 后，功能分支为什么通常可以删除？
