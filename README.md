<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0f2027,50:203a43,100:2c5364&amp;height=200&amp;section=header&amp;text=Jichao%20Chen&amp;fontSize=48&amp;fontColor=ffffff&amp;animation=fadeIn&amp;fontAlignY=38&amp;desc=AI%20Product%20%C2%B7%20LLM%20Apps%20%C2%B7%20Evaluation&amp;descAlignY=58&amp;descSize=18" alt="Jichao Chen — AI Product · LLM Apps · Evaluation" />
</p>

<p align="center">
  <a href="https://github.com/JichaoChen1123">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=500&amp;size=20&amp;pause=1000&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=600&amp;lines=%E8%AE%A9%E6%96%87%E6%A1%A3%E5%8F%AF%E4%BB%A5%E8%A2%AB%E6%8F%90%E9%97%AE%E3%80%81%E8%A2%AB%E5%BC%95%E7%94%A8%E3%80%81%E8%A2%AB%E8%AF%84%E6%B5%8B;Hybrid+Search+%2B+Rerank+%2B+Citations;Building+RAG+apps+that+you+can+measure" alt="让文档可以被提问、被引用、被评测" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=JichaoChen1123&amp;color=38bdf8&amp;style=flat-square&amp;label=Profile+Views" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/JichaoChen1123?style=flat-square&amp;color=38bdf8" alt="GitHub followers" />
  <img src="https://img.shields.io/github/stars/JichaoChen1123?style=flat-square&amp;color=38bdf8&amp;affiliations=OWNER" alt="GitHub stars" />
</p>

---

## 👋 关于我

```python
class JichaoChen:
    focus     = ["AI 应用产品", "RAG 应用", "质量评测与迭代"]
    stack     = ["Python", "FastAPI", "React", "TypeScript"]
    exploring = ["混合检索 & 重排", "RAG 评测与诊断", "结构化输出"]
    motto     = "回答要有来源，效果要能评测。"
```

## 🌟 重点项目 · 练有引力

<a href="https://github.com/JichaoChen1123/favorite-clash">
  <img src="https://raw.githubusercontent.com/JichaoChen1123/favorite-clash/main/docs/assets/hero.svg" alt="练有引力 — 从看懂，到练懂" width="100%" />
</a>

**把健身视频、动作教学和训练记录连起来，让想练的动作真正进入日常训练。**

从用户的两种困惑出发：想练某块肌肉，却不知道选什么动作；收藏了很多视频，却看不清建议之间的差别。项目把肌群探索、器材指南、视频观点对照与训练记录放进同一个手机优先的网页。

| 场景 | 产品如何回应 |
| --- | --- |
| **不知道练哪里、怎么练** | 可旋转3D人体，确认肌群后进入动作页；按器材找动作，配步骤、常见错误与教学视频 |
| **健身建议听起来互相矛盾** | 对照2–3条B站视频，区分观点与适用条件；展开字幕原句、前后文与时间链接核对 |
| **动作收藏后很少再看** | 收藏与训练衔接，从已收藏动作开始记录每组重量、次数与完成情况 |
| **练过之后记不清进度** | 保存训练历史、上次表现和本次小结，配组间休息计时；手机与电脑共用后台数据 |

**产品实现：** `13个肌群` · `16个代表动作` · `6类器材指南` · `手机底栏 / PC侧栏` · `私人HTTPS访问`

**AI与质量：** JSON Schema约束输出、Pydantic校验；引用绑定实际保存的字幕分段，原句和时间由程序读取；失败保留已完成材料，额度不足时持久化暂停。肌群、收藏和训练记录无需模型调用。

**技术：** `React` · `TypeScript` · `Three.js` · `FastAPI` · `SQLite` · `Faster Whisper` · `官方 Codex CLI` · `Tailscale Serve`

<a href="https://github.com/JichaoChen1123/favorite-clash#界面预览">
  <img src="https://raw.githubusercontent.com/JichaoChen1123/favorite-clash/main/docs/assets/muscle-desktop.png" alt="实际运行界面：3D人体肌群选择与中文肌群列表" width="100%" />
</a>

<p align="center">
  <a href="https://github.com/JichaoChen1123/favorite-clash"><b>查看项目 →</b></a> ·
  <a href="https://github.com/JichaoChen1123/favorite-clash#本地部署"><b>部署指南</b></a> ·
  <a href="https://github.com/JichaoChen1123/favorite-clash#使用指南"><b>如何使用</b></a>
</p>

<details>
<summary><b>展开手机端：器材指南与动作教学</b></summary>

<p align="center">
  <img src="https://raw.githubusercontent.com/JichaoChen1123/favorite-clash/main/docs/assets/equipment-mobile.png" alt="手机端器材指南" width="260" />
  <img src="https://raw.githubusercontent.com/JichaoChen1123/favorite-clash/main/docs/assets/teaching-mobile.png" alt="手机端动作教学" width="260" />
</p>

</details>

## 🚀 更多项目

| 项目 | 简介 | 技术 |
| --- | --- | --- |
| 🔍 [**RAGOps**](https://github.com/JichaoChen1123/RAGOps) | RAG 应用评测与诊断平台：导入样本、执行评测、诊断失败、人工复核、导出报告 | FastAPI · React · SQLAlchemy · Docker |
| 💬 [**源答 · yuanda-rag-assistant**](https://github.com/JichaoChen1123/yuanda-rag-assistant) | 基于 [PiriTnz/enterprise-rag-system](https://github.com/PiriTnz/enterprise-rag-system) 二次开发的 SaaS 知识助手：向量检索 + BM25 混合搜索、RRF 融合、CrossEncoder 重排、来源引用 | FastAPI · Chroma · sentence-transformers · Streamlit |
| 📖 [**知页 · zhiye-ai-study**](https://github.com/JichaoChen1123/zhiye-ai-study) | 基于 [beltromatti/get-it](https://github.com/beltromatti/get-it) 二次开发的 AI 文档学习助手：文档问答、概念可视化、闪卡、测验、费曼练习 | Next.js · React 19 · Three.js · Tailwind |

<p align="center">
  <a href="https://github.com/JichaoChen1123/RAGOps">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=JichaoChen1123&amp;repo=RAGOps&amp;theme=tokyonight&amp;hide_border=true" alt="RAGOps repository card" />
  </a>
  <a href="https://github.com/JichaoChen1123/yuanda-rag-assistant">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=JichaoChen1123&amp;repo=yuanda-rag-assistant&amp;theme=tokyonight&amp;hide_border=true" alt="源答 repository card" />
  </a>
</p>

## 🛠️ 技术栈

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,sqlite,docker,nginx,githubactions&amp;theme=dark" alt="Python, FastAPI, SQLite, Docker, Nginx, GitHub Actions" /><br />
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,vite,tailwind,threejs,electron,git&amp;theme=dark" alt="TypeScript, React, Next.js, Vite, Tailwind, Three.js, Electron, Git" />
</p>

**RAG / AI：** `Chroma` · `BM25` · `RRF` · `CrossEncoder` · `sentence-transformers` · `OpenAI Codex SDK` · `JSON Schema`

## 📊 GitHub 统计

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JichaoChen1123&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;hide_rank=true" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JichaoChen1123&amp;layout=compact&amp;theme=tokyonight&amp;hide_border=true" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=JichaoChen1123&amp;theme=tokyo-night&amp;hide_border=true&amp;area=true" alt="GitHub activity graph" />
</p>

## 📫 联系我

<p align="center">
  <a href="https://github.com/JichaoChen1123">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Contact me on GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:2c5364,50:203a43,100:0f2027&amp;height=100&amp;section=footer" alt="Footer" />
</p>
