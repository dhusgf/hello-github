# 怎么让 AI 往这个仓库里放东西

## 一句话模板

> 把 `<本地文件或内容>` 提交到 `DHUSGF/hello-github` 的 `main` 分支，commit message 用 `<说明>`，推完告诉我 commit 哈希。

## 需要说清的四件事

1. **仓库**：`DHUSGF/hello-github`（或者直接说仓库全名）
2. **放哪里**：具体目录/文件名，例如 `notes/2026-11-08.md`
3. **写什么**：文件内容，或者"用工作区里的 `xxx.py`"
4. **怎么提交**：commit message；要不要推送

## 常用说法

- 只改本地、先看效果：`改完先别 push，给我看 diff`
- 拉最新再改：`先 pull，再改 xxx，然后 push`
- 新建分支提 PR：`开分支 feat/xxx 提交，然后开 PR`
- 只读不写：`只帮我看看仓库里 xxx 怎么写的，别改`

## 注意

- 仓库是 **public**，别放密钥、隐私数据、客户资料
- `.gitignore_global` 已经挡掉 `.env`、`*.pem`、`*.key` 之类的常见密钥文件，但不是万能的，自己也要留意
- AI 的 push 权限来自 Windows 凭据管理器里的 GitHub token，任何在本机跑的进程都能用；不想让它推就说清楚"只提交不推送"
