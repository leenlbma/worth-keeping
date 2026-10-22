# 值得留下 · worth-keeping

看过觉得有价值的内容，整理成可直接在手机或电脑上打开的可视化页面。

在线浏览：https://leenlbma.github.io/worth-keeping/

## 目录
- [存量代码的 AI 重构：“改错了，谁先知道？”](ai-refactor-legacy/)：21 个公开案例复盘 AI 在存量代码迁移里的实际效果，附 10 张数据图（2026-10-22）
- [对话孙宇晨：年轻人如何抓住 AI 时代的机会？](sun-yuchen-ai-youth/)：播客 39 章逐章整理（2026-10-09）
- [【译】Agentic evals：如何判断 AI 智能体有没有把事办成](agentic-evals-zh/)：原文作者 Sergii Makarevych，[X 原文](https://x.com/sermakarevich/status/2108942010123968804)，中文全文翻译（2026-10-11）

## 如何添加新内容
1. 新建文件夹放页面，例如 `my-entry/index.html`。
2. 打开根目录 `index.html`，在 `<script id="entries">` 的 JSON 数组里加一个对象：`id, type, title, desc, date, author, source_url, path, length, tags`（模板见文件顶部注释）。
3. 在上面的「目录」里加一行，提交并推送到 `main`，约 1 分钟后生效。

首页自带搜索、按类型筛选、明暗主题切换。封面默认按 `id` 生成抽象图；如需换成自己的图片，在条目里加 `cover` 字段（2:1，图片放在条目文件夹内）。

## 说明

**内容**　个人阅读笔记，每条独立成页，来源与口径写在各自页面里。播客整理基于语音识别，人名、数字可能有误，引用前对照原视频；译文以原文为准；原创内容的数据来源见文末引用。涉及健康、投资的观点属于原讲者，不构成建议。

**版权**　原创内容（如《存量代码的 AI 重构》）采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans) 许可：可转载、改编，需署名、非商业用途、相同方式共享。译文版权归原作者，仅作学习交流。权利人如希望下架，提 issue 即删。

**纠错**　发现错字、数据错误或链接失效，欢迎提 issue 或 PR。
