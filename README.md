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

首页自带搜索、按类型筛选、明暗主题切换；封面默认由 id 自动生成，条目里加 `cover` 字段可换成自己的图片（比例 2:1，放在条目文件夹内）。

## 说明
内容为个人学习整理。部分来自语音识别，可能有错字或错误的人名、数字；引用前请对照原内容。观点属于原作者或嘉宾，不构成医疗或投资建议。

翻译类内容版权属于原作者，仅作学习交流；如原作者希望下架，请提 issue，会立即删除。

本站原创内容（如上列《存量代码的 AI 重构》）采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans) 许可：可自由转载、改编，需署名、非商业用途、相同方式共享。
