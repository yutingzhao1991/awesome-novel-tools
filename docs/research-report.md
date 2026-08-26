# 小说写作开源生态调研报告

> 调研时间：2026 年（star 数截至调研当日，来自 GitHub 页面/API 实测；许可证为仓库 LICENSE 文件检出结果，标注"无"表示仓库未检出标准许可证文件）。所有条目均经 GitHub 页面或官方站点核实存在。

---

## 一、开源 AI 写作 / 小说生成项目

### 1.1 国际主流（角色扮演 / AI 写作前端）

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| SillyTavern | https://github.com/SillyTavern/SillyTavern | 最流行的开源 LLM 前端，支持角色扮演、长文写作、世界设定与记忆（原为 TavernAI 的 fork） | ≈3.3 万（32,657） | AGPL-3.0 |
| KoboldCpp | https://github.com/LostRuins/koboldcpp | 单文件、零安装运行 GGUF 模型并自带 KoboldAI 写作界面，本地 AI 写作最常用入口 | ≈1.2 万（11,524） | AGPL-3.0 |
| text-generation-webui → oobabooga/textgen | https://github.com/oobabooga/textgen | 老牌本地 LLM 桌面/Web 前端（原 oobabooga/text-generation-webui，仓库已更名） | ≈4.8 万（47,577） | AGPL-3.0 |
| KoboldAI-Client | https://github.com/KoboldAI/KoboldAI-Client | KoboldAI 经典浏览器客户端，叙事/写作专用 UI | ≈3,900 | AGPL-3.0 |
| AIDungeon（开源版） | https://github.com/latitudegames/AIDungeon | AI 文字冒险游戏的早期开源版本，常被用作 AI 叙事生成参考 | ≈3,200 | MIT |
| NovelAI | https://novelai.net | 商业闭源的 AI 小说/图像生成服务（非开源，作为参照物；开源替代见上表与本地模型一节） | — | 闭源商业 |

补充：LlmKira/novelai-python（https://github.com/LlmKira/novelai-python，49★，Apache-2.0）是 NovelAI 非官方 API 的 Python SDK，属于第三方封装，不是自托管替代品。

### 1.2 中文开源小说写作项目（按 star 排序）

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| oh-story-claudecode | https://github.com/zenstory-ai/oh-story-claudecode | 网文/小说写作 skill 包，覆盖长篇与短篇网络小说的扫榜、拆文、写作、去 AI 味、封面图全流程 | ≈6,100（6,087） | MIT |
| AI_NovelGenerator | https://github.com/YILING0013/AI_NovelGenerator | 用 AI 自动生成多章节长篇小说，自动衔接上下文与伏笔 | ≈6,000（5,959） | AGPL-3.0 |
| AI-Writer | https://github.com/BlinkDL/AI-Writer | RWKV 作者 BlinkDL 的中文小说生成项目（玄幻、言情网文），基于 RWKV 预训练模型 | ≈3,900（3,868） | Apache-2.0 |
| chinese-novelist-skill | https://github.com/PenglongHuang/chinese-novelist-skill | AI 驱动的中文小说创作助手 skill：三层递进问答、跨会话偏好记忆、中断续写、每章悬念钩子 | ≈2,700（2,736） | 无 |
| AI-Novel-Writing-Assistant | https://github.com/ExplosiveCoderflome/AI-Novel-Writing-Assistant | AI Native 长篇小说创作系统：Agent、世界观、写法引擎、RAG、整本生产工作流 | ≈2,600（2,630） | 自定义许可证 |
| AI-automatically-generates-novels | https://github.com/wfcz10086/AI-automatically-generates-novels | 基于 AI+提示词的智能小说创作生产力工具 | ≈900（919） | Apache-2.0 |
| MaliangAINovalWriter（马良写作） | https://github.com/Deng-m1/MaliangAINovalWriter | 面向中文网文作者的 AI 小说写作工具 | ≈860（856） | 无 |
| QMAI（青幕AI写作） | https://github.com/Mochocyang/QMAI | 青幕 AI 写作软件，侧重长篇小说角色性格统一、防止人设崩坏 | ≈730（733） | 自定义（NOASSERTION） |
| Ai-Novel | https://github.com/inliver233/Ai-Novel | AI 小说创作网站 | ≈750（748） | 无 |
| Openwrite | https://github.com/LiPu-jpg/Openwrite | AI 小说创作引擎：对话式引导建项目、多维风格提取与合成、质量审核 | ≈640（639） | Apache-2.0 |
| ai-novel-writer | https://github.com/Jieice/ai-novel-writer | 网文自动化创作系统：项目模板、章节润色、AI 率检测、一键发布到番茄小说 | ≈95 | 无 |
| novel_agent | https://github.com/blackzhanzhan/novel_agent | Git 原生的 AI 小说写作工作台，基于 Dify agents | ≈90（87） | 无 |
| ai-novel-lab | https://github.com/xindoo/ai-novel-lab | AI 小说生成实验室 | ≈60（57） | MIT |
| novel-ai | https://github.com/lvi166/novel-ai | 基于大模型的智能小说创作工具，支持多种 AI 模型 | 0（新建） | MIT |
| novel-writer-skills | https://github.com/Shine8592/novel-writer-skills | 零成本中文小说写作 OpenClaw skills（宣称 900K+ 字符产出） | ≈15 | 无 |
| human-writing | https://github.com/KKKKhazix/human-writing | 让 AI 写的中文读起来像真人说话，通用创作与改稿 skill（写作质量向，非完整写作软件） | ≈3,100（3,068） | MIT |

---

## 二、自托管推理基础设施（跑写作模型）

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| llama.cpp | https://github.com/ggml-org/llama.cpp | C/C++ 的 LLM 推理引擎，几乎所有本地写作模型（GGUF）的基础 | ≈12.6 万（125,681） | MIT |
| Ollama | https://github.com/ollama/ollama | 一键自托管运行开源模型（含 Qwen、RWKV 等），本地写作模型的最简单入口 | ≈17.9 万（179,446） | MIT |
| Open WebUI | https://github.com/open-webui/open-webui | 用户友好的自托管 LLM Web 界面，支持 Ollama/OpenAI 兼容 API，可当写作聊天台 | ≈15.0 万（149,944） | Open WebUI License（BSD-3 变体 + 品牌保留条款） |
| Jan | https://github.com/janhq/jan | 本地优先的 AI 桌面客户端（离线可用） | ≈4.4 万（44,181） | Jan License（自定义） |
| LM Studio | https://lmstudio.ai | 流行的本地模型桌面客户端（参照物） | — | 闭源商业 |

---

## 三、开源写作软件（非 AI / 传统小说写作软件）

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| novelWriter | https://github.com/vkbo/novelWriter | 专为写小说设计的纯文本编辑器（Markdown 风格，含大纲/章节/角色管理） | ≈3,100（3,091） | GPL-3.0 |
| Manuskript | https://github.com/olivierkes/manuskript | 面向作家的开源写作工具（大纲、角色卡、思维导图式结构） | ≈2,400（2,418） | GPL-3.0 |
| bibisco | https://github.com/andreafeccomandi/bibisco | 小说写作软件，侧重角色/情节/世界观分析与叙事结构 | ≈770（767） | GPL-3.0 |
| Quoll Writer | https://github.com/garybentley/quollwriter | 让作者专注于文字的写作应用 | ≈220（216） | Apache-2.0 |
| Wavemaker v3 | https://github.com/mayasky76/WaveMaker-Novel-Writing-Software-Version-3 | 网页版小说规划与写作软件（官网 wavemaker.cards，Chrome 商店版用户量大）；旧版 wavemakercards/wavemaker-v2（10★） | ≈70（73） | 仓库未见标准 LICENSE 文件 |
| Obsidian | https://obsidian.md | 极受欢迎的知识库/笔记软件（写作向），核心闭源、免费个人使用；插件生态开源 | — | 核心闭源（插件各自开源） |

---

## 四、写作辅助开源库 / 工具 / 模型

### 4.1 写作辅助工具

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| Wordcraft（Google PAIR） | https://github.com/PAIR-code/wordcraft | Google PAIR 出品的 AI 短篇故事写作编辑器（原型性质） | ≈310（307） | Apache-2.0 |
| Sudowrite | https://www.sudowrite.com | 商业闭源 AI 小说助手（参照物）。开源替代没有 1:1 等价物，实际组合方案：SillyTavern / Open WebUI + 本地模型（llama.cpp / Ollama）+ 上述中文写作项目 | — | 闭源商业 |
| InkPilot（Obsidian 插件） | https://github.com/Nicholas-Yu/InkPilot | Obsidian 小说家插件：AI 规划、角色设计、大纲生成、章节写作与一致性审查 | ≈3 | MIT |
| eventide-quill（Obsidian 插件） | https://github.com/EventideMiles/eventide-quill | Obsidian 反馈优先写作助手：本地/云端 AI 异步评阅、文风检查、连续性检查、情节分支 | ≈6 | MIT |

### 4.2 可用于写作的开源模型（GitHub 仓库）

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| RWKV-LM | https://github.com/BlinkDL/RWKV-LM | RNN 架构大模型，长上下文、低显存，社区广泛用于小说续写/生成（注意：RWKV/RWKV-LM 是 fork，62★，正主是 BlinkDL 仓库） | ≈1.5 万（14,682） | Apache-2.0 |
| Qwen3（通义千问 3） | https://github.com/QwenLM/Qwen3 | 阿里通义千问系列，中文写作能力强；原 QwenLM/Qwen2.5 仓库已重定向并入 Qwen3 | ≈2.8 万（27,557） | 仓库无 LICENSE 文件；模型权重许可证为 Apache-2.0（见 HF 模型卡） |
| Yi | https://github.com/01-ai/Yi | 零一万物大模型系列（Yi-34B 等），中文写作可用 | ≈7,800（7,835） | Apache-2.0 |

### 4.3 HuggingFace 社区小说专用模型（未做 API 实测，许可证以模型卡为准）

- xiaol/rwkv-novel-agent-g1h-13b-ctx10240 — RWKV 小说 Agent 模型（13B，10,240 上下文）— https://huggingface.co/xiaol/rwkv-novel-agent-g1h-13b-ctx10240
- xiaol/rwkv-7B-world-novel-128k — RWKV 世界小说 7B（128K 长上下文）— https://huggingface.co/xiaol/rwkv-7B-world-novel-128k
- Dxniz/NaNovel-27B — NaNovel 27B 小说模型 — https://huggingface.co/Dxniz/NaNovel-27B
- yuxinlu1/qwen3-6-27b-chinese-realistic-fiction-lora-v1 — 中文现实主义小说 LoRA（Qwen3.6-27B）— https://huggingface.co/yuxinlu1/qwen3-6-27b-chinese-realistic-fiction-lora-v1

---

## 五、社区与资源

### 5.1 社区

| 名称 | URL | 简介 |
|---|---|---|
| r/writing | https://www.reddit.com/r/writing/ | Reddit 最大的英文写作社区 |
| r/WritingWithAI | https://www.reddit.com/r/WritingWithAI/ | Reddit 上专门讨论 AI 辅助写作的社区 |
| 龙的天空（龙空） | https://lkong.com | 中文网文圈最老牌的作者论坛（含 AI 写作讨论区） |
| 百度贴吧「起点吧」/网文作者相关贴吧 | https://tieba.baidu.com | 中文网文读者/作者聚集地，起点相关讨论的主阵地 |
| NaNoWriMo | https://nanowrimo.org | 全球性"11 月写 5 万字小说"写作活动 |
| NaNoGenMo | https://github.com/NaNoGenMo | GitHub 上的"全国小说生成月"活动（每年一个仓库，如 NaNoGenMo/2024，18★），用代码生成小说的社区 |

### 5.2 Awesome 列表 / 提示词库

| 名称 | URL | 一句话简介 | star 量级 | 许可证 |
|---|---|---|---|---|
| awesome-novel-agent | https://github.com/modoojunko/awesome-novel-agent | 让 AI agent 成为小说创作搭档的精选资源列表（世界观→角色→章节→正文全流程） | ≈660（662） | GPL-3.0 |
| awesome-llm-story-generation | https://github.com/Picrew/awesome-llm-story-generation | LLM 故事生成方向的论文与开源项目精选列表 | ≈100（97） | 无 |
| awesome-ai-book-writing | https://github.com/finxter/awesome-ai-book-writing | 用 AI 写书/出书的工具与工作流精选 | ≈17 | 无 |
| prompts.chat（原 awesome-chatgpt-prompts） | https://github.com/f/prompts.chat | 全球最大的 ChatGPT 提示词库（仓库已更名；含大量写作/创作类提示词） | ≈16.8 万（167,915） | 自定义（NOASSERTION） |
| awesome-chatgpt-prompts-zh | https://github.com/PlexPt/awesome-chatgpt-prompts-zh | 中文版 ChatGPT 提示词大全（含写作相关分类） | ≈6.2 万（61,813） | MIT |
| Prompt-Engineering-Guide | https://github.com/dair-ai/Prompt-Engineering-Guide | 提示工程权威指南（含中文版），写作提示词设计的理论支撑 | ≈7.8 万（77,792） | MIT |
| awesome-ChatGPT-repositories | https://github.com/taishi-i/awesome-ChatGPT-repositories | ChatGPT/OpenAI 相关开源仓库精选 | ≈3,200（3,214） | CC0-1.0 |

其他相关（一般写作向）：jenniferlynparsons/awesome-writing（699★，Unlicense，帮开发者写作的信息清单）、yowainwright/awesome-writing-tools（162★，MIT）。

---

## 六、教程 / 方法论类资源

| 名称 | URL | 简介 |
|---|---|---|
| Helping Writers Become Authors | https://www.helpingwritersbecomeauthors.com | K.M. Weiland 的写作方法论网站（结构、大纲、角色弧光），非 AI 但常被 AI 写作工作流引用 |
| The Creative Penn | https://www.thecreativepenn.com | Joanna Penn 的网站，专注"AI 时代作者生存/写作出版"，有大量 AI 辅助写作文章与播客 |
| NaNoWriMo 写作指南 | https://nanowrimo.org | 官方写作方法/训练营资源 |
| Prompt-Engineering-Guide（教程属性） | https://github.com/dair-ai/Prompt-Engineering-Guide | 提示工程教程，AI 辅助写作的提示词方法论基础（有中文翻译） |

说明：中文体系内，"AI 辅助写作"教程目前主要散落在知乎专栏、公众号与上述中文项目 README 中，未发现高 star 的独立中文教程仓库；龙的天空论坛与各网文项目 README 是实操经验的主要来源。

---

## 附：全部来源 URL

**GitHub 仓库（已核实存在）：**
https://github.com/SillyTavern/SillyTavern · https://github.com/LostRuins/koboldcpp · https://github.com/oobabooga/textgen · https://github.com/KoboldAI/KoboldAI-Client · https://github.com/latitudegames/AIDungeon · https://github.com/LlmKira/novelai-python · https://github.com/zenstory-ai/oh-story-claudecode · https://github.com/YILING0013/AI_NovelGenerator · https://github.com/BlinkDL/AI-Writer · https://github.com/PenglongHuang/chinese-novelist-skill · https://github.com/ExplosiveCoderflome/AI-Novel-Writing-Assistant · https://github.com/wfcz10086/AI-automatically-generates-novels · https://github.com/Deng-m1/MaliangAINovalWriter · https://github.com/Mochocyang/QMAI · https://github.com/inliver233/Ai-Novel · https://github.com/LiPu-jpg/Openwrite · https://github.com/Jieice/ai-novel-writer · https://github.com/blackzhanzhan/novel_agent · https://github.com/xindoo/ai-novel-lab · https://github.com/lvi166/novel-ai · https://github.com/Shine8592/novel-writer-skills · https://github.com/KKKKhazix/human-writing · https://github.com/ggml-org/llama.cpp · https://github.com/ollama/ollama · https://github.com/open-webui/open-webui · https://github.com/janhq/jan · https://github.com/vkbo/novelWriter · https://github.com/olivierkes/manuskript · https://github.com/andreafeccomandi/bibisco · https://github.com/garybentley/quollwriter · https://github.com/mayasky76/WaveMaker-Novel-Writing-Software-Version-3 · https://github.com/wavemakercards/wavemaker-v2 · https://github.com/PAIR-code/wordcraft · https://github.com/Nicholas-Yu/InkPilot · https://github.com/EventideMiles/eventide-quill · https://github.com/BlinkDL/RWKV-LM · https://github.com/RWKV/RWKV-LM · https://github.com/QwenLM/Qwen3 · https://github.com/01-ai/Yi · https://github.com/modoojunko/awesome-novel-agent · https://github.com/Picrew/awesome-llm-story-generation · https://github.com/finxter/awesome-ai-book-writing · https://github.com/f/prompts.chat · https://github.com/PlexPt/awesome-chatgpt-prompts-zh · https://github.com/dair-ai/Prompt-Engineering-Guide · https://github.com/taishi-i/awesome-ChatGPT-repositories · https://github.com/jenniferlynparsons/awesome-writing · https://github.com/yowainwright/awesome-writing-tools · https://github.com/NaNoGenMo

**HuggingFace 模型：**
https://huggingface.co/xiaol/rwkv-novel-agent-g1h-13b-ctx10240 · https://huggingface.co/xiaol/rwkv-7B-world-novel-128k · https://huggingface.co/Dxniz/NaNovel-27B · https://huggingface.co/yuxinlu1/qwen3-6-27b-chinese-realistic-fiction-lora-v1

**官网/社区/教程站点：**
https://novelai.net · https://lmstudio.ai · https://obsidian.md · https://www.sudowrite.com · https://wavemaker.cards · https://www.novelwriter.io · https://www.bibisco.com · https://lkong.com · https://nanowrimo.org · https://www.helpingwritersbecomeauthors.com · https://www.thecreativepenn.com · https://www.reddit.com/r/writing/ · https://www.reddit.com/r/WritingWithAI/ · https://tieba.baidu.com

**网络搜索结果来源（发现线索用）：**
https://dev.co/ai/frameworks/sillytavern · https://olud.ai/project/lostruins-koboldcpp.html · https://repos.ecosyste.ms/hosts/GitHub/repositories/oobabooga%2Ftext-generation-webui · https://relatedrepos.com/gh/KohakuBlueleaf/Kohaku-NAI · https://onegen.ai/project/text-generation-webui-the-most-versatile-interface-for-local-llms/ · https://relatedrepos.com/gh/LlmKira/novelai-python · https://reddifier.com/free-subreddit-analysis-tool/r/WritingWithAI · https://repos.ecosyste.ms/hosts/GitHub/topics/ai-writing · https://alternativeto.net/software/sudowrite/ · https://github.com/pollinations/pollinations/blob/be33dc3a/apps/GREENHOUSE.md
