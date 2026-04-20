# git-work-report
一个  Skill，将本地 Git 提交记录自动转化为日报、周报和月报。
报告聚焦交付结果——按模块描述完成了什么。项目名称自动从 Git remote 提取。输出语言跟随你的输入：中文提问即输出中文报告。

## 使用方式
直接告诉 Agent 你需要什么：
```
帮我生成今天的日报
根据 git 生成本周周报
这个月的工作月报

Generate today's daily report from git
Summarize this week's work
Give me a monthly report for last month
```

## 输出内容

每份报告包含：

1. **完成工作** — 按模块归类，每条一句话描述交付结果
2. **进度节奏** — 每日进度（周报）或按周进度（月报）
3. **小结** — 1-2 句话概括整体交付价值

不含提交次数，不含代码行数，不含下一步计划。

## License

MIT
