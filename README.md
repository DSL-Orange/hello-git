# hello-git

GitHub 练习仓库。用来走通「本地改 → 提交 → 推送到云端」这一条链路。

## 这个仓库是用来干什么的

- 练习 `git add` / `commit` / `push`
- 确认 SSH 通道正常
- 练坏了直接删掉重来，没有心理负担

## 日常循环

```bash
git status                 # 看改了啥
git add -A                 # 纳入存档
git commit -m "说明"       # 拍快照
git push                   # 上云
```

## 进度

- 2026-11-08：第一次推送成功，本地 `7f3c909` 和远程 `refs/heads/main` 哈希一致
- 2026-11-08：概念、装环境、第一次推送三篇读完，全链路走通
- 踩过的坑：PowerShell 的 `Out-File` 默认编码是 UTF-16，写中文文件要用编辑器保存