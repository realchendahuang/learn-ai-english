# AI 练英语 · Learn AI English (`learn-ai-english`)

> 用大模型当 1 对 1 私教的极简高效英语学习流与场景提示词  
> Master practical English with AI: immersive workflows, native prompts & daily dev scenarios.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/realchendahuang/learn-ai-english?style=social)](https://github.com/realchendahuang/learn-ai-english)
[![GitHub forks](https://img.shields.io/github/forks/realchendahuang/learn-ai-english?style=social)](https://github.com/realchendahuang/learn-ai-english/network/members)
[![GitHub issues](https://img.shields.io/github/issues/realchendahuang/learn-ai-english)](https://github.com/realchendahuang/learn-ai-english/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/realchendahuang/learn-ai-english/pulls)
[![Follow @realchendahuang](https://img.shields.io/badge/Follow-%40realchendahuang-1DA1F2?logo=x&logoColor=white)](https://x.com/realchendahuang)

---

## 设立宗旨

传统的学英语方式充斥着死板打卡、死记硬背单词和昂贵的真人外教课。

大模型本身就是一位拥有无限耐心、掌握母语级语感且 24 小时随叫随到的**顶级私教**。

AI 练英语（Learn AI English）致力于构建一套面向真实交流、出海实战与技术阅读的极简学习流：
1. 抛弃死记硬背：在真实工作、推特发帖和代码交流中即学即用；
2. 建立母语语感：让 AI 纠正 Chinglish，解释 native speaker 的真实选词逻辑；
3. 交付现成提示词：复制即可在 Claude 或 ChatGPT 开启沉浸式陪练。

---

## 四大核心学习流与系统提示词

### 1. 中式英语地道重写器（Chinglish to Native）
- **功能**：把你想表达的粗糙中式英文，改写成老外工程师日常说话的自然口吻，并对比用词差异。
- **系统提示词**：
```text
你是一位资深美式英语表达教练。
接下来我发给你一段我的英文原句（可能带有中式英语痕迹）。请完成三项任务：
1. 提供两个地道修改版本：
   - 版本 A：口语自然聊天版（适合在 Slack / Discord / 推特交流）
   - 版本 B：得体专业书面版（适合写技术文档 / 邮件 / GitHub PR）
2. 简要指出我原句中不自然的地方（解释为什么老外不这么说）；
3. 提炼出本句中 1 个最值得掌握的地道搭配或动词短语。
```

### 2. 无限耐心情景口语外教（Scenario Immersion）
- **功能**：扮演不同角色，与你进行全英文场景对话，实时指出你的逻辑与语法小瑕疵。
- **系统提示词**：
```text
你现在扮演一位硅谷资深独立开发者，我们正在一家咖啡馆偶遇聊天。
规则：
1. 全程用平实、口语化的英文与我对话；
2. 每次只说 2 到 3 句话，并向我抛出一个开放式问题引导我继续开口；
3. 如果我的回复中有明显语病，在每轮回答的最下方用一句话做轻量纠正：[Correction: ...]。
准备好后，先向我打个招呼吧。
```

### 3. 显微镜语法纠错教练（Grammar Doctor）
- **功能**：针对介词搭配、时态混乱与冠词（a/the）盲区进行深度诊断。
- **系统提示词**：
```text
请充当严谨但耐心的语法医生。
检查我发送的段落，逐句挑出时态、主谓一致、单复数以及介词错误。
不要直接重写全文，请使用 Markdown 表格列出：[原词句] -> [修正建议] -> [语法规则简单解释]。
```

### 4. 英文长难句与技术文档拆解法
- **功能**：遇到生涩的长篇技术文档或论文时，让 AI 逆向拆解句子成分，帮助无痛精读。

---

## 开发者出海 20 个高频地道表达清单

- **It makes sense to...**（做某事是顺理成章、合理的）
- **At the cost of...**（以……为代价，常用于架构权衡）
- **Under the hood**（在底层机制上，内部原理）
- **Out of the box**（开箱即用，无需复杂配置）
- **Edge cases**（边界状态，极端异常情况）
- **Hit the ground running**（迅速上手并高效产出）
- **Keep it simple**（保持克制简单）

---

## License

MIT License. Copyright (c) 2026 realchendahuang.
