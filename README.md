# Nicky · AI Product Engineer

**AI product engineer, now independent. I build AI products end to end — and open-source the ones that hold up.**
AI 产品工程师，现为独立开发者。把模型能力做成能跑起来的产品，并把过程写成可复现的记录。

我是 Nicky（GitHub: **hugcosmos**），做 AI 产品与 LLM 应用工程，从需求定义到代码交付全程参与。方向集中在三条线：实时语音链路（ASR / TTS / 评分）、生成式内容管线、以及把一次性脚本封装成可复用的 agent 技能。

站点与工程复盘：https://hugcosmos.github.io · 联系：hugcosmos@gmail.com

---

## 快速事实

- 17 个公开仓库，其中 **15 个原创项目**；两个项目可直接在线体验：CodeMath、MovieFairy
- 两个项目有正式版本发布：Book to Audiobook（6 个 release）、Edge Read Chrome（5 个 release）
- 技术栈主线：TypeScript / React、Python / FastAPI、FunASR、Edge TTS 与多家 TTS 供应商、Docker
- 写作：6 篇工程复盘（中英各一版），最新一组 2026-11

## 能做什么（每条都挂证据）

| 能力 | 证据 |
| --- | --- |
| 实时语音链路：ASR + TTS + 打分 | [SceneLine](https://github.com/hugcosmos/SceneLine)——FunASR 常驻进程实时识别、40+ Edge TTS 音色、多角色分角色评分 |
| 多家 TTS 供应商工程化 | [Scripts to Audiobook](https://github.com/hugcosmos/scripts-to-audiobook)——Edge / ElevenLabs / 讯飞 / 百度四家统一接口，61 音色加权匹配，输出 MP3 + SRT |
| 交互式前端与可视化 | [CodeMath](https://github.com/hugcosmos/CodeMath)——React 19 + Three.js，九章可动手的计算机数学 |
| 生成式内容管线 | [Podcast Studio](https://github.com/hugcosmos/podcast-studio)、[PoemLens](https://github.com/hugcosmos/PoemLens)、[gag-cartoon](https://github.com/hugcosmos/gag-cartoon) |
| 零依赖单文件工程 | [Element Craft Town](https://github.com/hugcosmos/synth-town)——单 HTML 文件、无框架无构建的炼金建造游戏 |
| Agent 技能化（skill） | [movie-fetch](https://github.com/hugcosmos/movie-fetch)、[pwa-setup](https://github.com/hugcosmos/pwa-setup)、[gag-cartoon](https://github.com/hugcosmos/gag-cartoon) |

## 代表作

### CodeMath — 把计算机数学做成能动手玩的九章

交互式学习平台：进制转换、逻辑门实验台、真值表生成器、归纳法多米诺、汉诺塔、分形、停机问题模拟器，中英双语。难点是把「不可解问题」这类纯抽象概念做成可操作的模拟。
技术栈：React 19 · TypeScript · Vite · Three.js · GSAP · KaTeX · MIT
[仓库](https://github.com/hugcosmos/CodeMath) · [在线体验](https://codemath.pages.dev/)

### SceneLine — AI 配音练习台

覆盖「听原声—跟读—被打分」的闭环：FunASR 实时识别、40+ 音色按性别与地区筛选、多角色逐角色评分、Docker Compose 部署与数据持久化。
技术栈：Node 20 · Python · FunASR · Edge TTS · Docker · MIT
[仓库](https://github.com/hugcosmos/SceneLine)

### Scripts to Audiobook — 一个接口接四家 TTS

把格式化脚本变成多角色有声书：统一接入四家 TTS，加权音色匹配引擎给出评分解释与多样性惩罚，输出合并 MP3、SRT 字幕与结构化时间轴，配 SQLite 专辑化曲库。
技术栈：Python · FastAPI · React · Vite · SQLite
[仓库](https://github.com/hugcosmos/scripts-to-audiobook)

## 更多开源项目

**产品与工具**
- [MovieFairy](https://github.com/hugcosmos/MovieFairy)——按情绪调节理论做推荐，纯静态 + PWA，零 API 调用。[在线体验](https://moviefairy.pages.dev/)
- [Book to Audiobook](https://github.com/hugcosmos/book-to-audiobook)——EPUB/MOBI/AZW3/PDF/TXT 转章节化 M4B/MP3，pip 可装，6 个 release。
- [Podcast Studio](https://github.com/hugcosmos/podcast-studio)——话题进、播客出：Perplexity 检索新闻 + 多说话人 TTS + ffmpeg 合成。
- [BrainBoost](https://github.com/hugcosmos/BrainBoost)——速算与记忆双模式的脑力训练，纯前端。
- [SaveMyRedNote](https://github.com/hugcosmos/SaveMyRedNote)——小红书笔记备份，可部署到 Cloudflare Pages。

**生成与排版**
- [PoemLens](https://github.com/hugcosmos/PoemLens)——一句诗出三个版本（题款画 / 诗笺 / 明信片）；文字由脚本用霞鹜文楷排版而非交给图像模型，支持重排不重画。
- [gag-cartoon](https://github.com/hugcosmos/gag-cartoon)——由 agent 构思笑点、脚本渲染单格黑白漫画。

**浏览器与本地工具**
- [Edge Read Chrome](https://github.com/hugcosmos/edge-read-chrome)——Edge 神经音色逐词高亮朗读，native messaging 而非 Web Speech API，5 个 release。
- [micro-apps](https://github.com/hugcosmos/micro-apps)——小工具合集：老 Kindle 局域网推书、通用视频字幕遮罩。

**游戏**
- [synth-town](https://github.com/hugcosmos/synth-town)——单文件零依赖的炼金 + 城镇建造游戏，30+ 配方、宠物、成就与地图。

## 写作

工程复盘按「结论 → 约束 → 方案 → 失败与修正 → 可复现」写，不写产品宣传稿。

- [CodeMath：交互式数学学习平台](https://hugcosmos.github.io/blog/en/codemath-interactive-math-learning)
- [我不再让模型编对话：Scripts to Audiobook 的设计取舍](https://hugcosmos.github.io/blog/scripts-to-audiobook-journey)
- [延迟第一，打分第二：SceneLine 的取舍](https://hugcosmos.github.io/blog/sceneline-dubbing-practice-platform)
- [整本书转有声书：Book to Audiobook 里的四个约束](https://hugcosmos.github.io/blog/en/convert-whole-books-to-audiobooks)
- [三个不打扰你的小工具：本地优先的三个代价](https://hugcosmos.github.io/blog/en/local-first-tools)
- [Introducing Podcast Studio](https://hugcosmos.github.io/blog/introducing-podcast-studio)

中文版与全部文章见 [博客](https://hugcosmos.github.io/blog.html)。

---

一切内容以仓库为准：仓库里的代码、README 与 release 是唯一可信来源，任何介绍文字如与仓库不符，以仓库为正确版本。
