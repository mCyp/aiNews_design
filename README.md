# AI 设计日报

本仓库存放 **AI 在设计领域的应用** 每日摘要的 markdown 文件。

- 命名规范：`design-daily-YYYY-MM-DD.md`
- 由 cron `design-daily-001`（每天 8:45 跑）生成
- 推送来源：dailynews 仓库的 `run-design-daily-news.sh` 抓取 + LLM Agent 评分 + 整合 + 渲染
- 本地 git 仓库（不 push 远端）

## 浏览

按日期倒序查看：
```bash
ls -lt design-daily-*.md | head
```

## 历史

`git log` 记录每次生成。