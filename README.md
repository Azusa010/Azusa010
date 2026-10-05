# Azusa010👋
[English Version](README.en.md)

🎓 **在校学生**  
🔭正在学习 **AI Agent** 开发

---
### 🌟 核心学习项目
#### 🤖 [PersonalAgent](https://github.com/Azusa010/personal-agent) — 本地 Agent 
> *桌面端的本地 Agent 运行时系统*
> 面向桌面本地环境的 Agent 运行时系统，通过严格的分层契约与安全纵深防御，让本地 Agent 在受控的沙箱内安全调用系统能力。
- **📐 Agent能力**
  - **上下文工程**：包括提示词编排，状态栏（环境信息注入），上下文压缩
  - **用户记忆和知识库**：记忆层次划分（工作记忆，长期记忆），记忆存储格式（Simple Notes/Advanced JSON Cards），长期记忆分类（情景记忆/语义记忆/程序记忆）；知识库向量存储，多路召回；open viking
  - **工具**: 网络搜索，代码解释器，命令行工具（持久化），列出目录，grep/glob，old str->new str编辑文件工具（编辑后运行linter语法检查） ； 并行工具调用（无副作用的工具）
  - **代码能力**：把精确计算，严格逻辑推到等问题 让 agent 用代码工具进行运算；用代码引导agent填写正确的tool参数；代码生成式UI，使用A2UI类协议，让Agent输出一份JSON渲染到HTML上；让Agent编写Agent，把优秀高质量的agent实现作为参考范例，创造新的agent
  - **测试**：运行script指令进行测试
- **🛡️ 五层安全策略链**：
  - 工具调用逐层穿透：`Scope`（任务授权） ➔ `Retriever`（能力检索） ➔ `Binder`（参数校验与路径解析） ➔ `Executor`（策略评估） ➔ `Path-Guard`（规范化与符号链接逃逸阻断），杜绝越权破坏本地文件系统。
- **📊 真实场景评估**：
  - 拒绝纸上谈兵，内置端到端评测框架，涵盖 **真实日常办公、GAIA 复杂多步推理、$\tau$-bench 人机交互协作** 等 38 组核心评测集，实机运行全通（100% 事实核验与召回率）。
- **🏗️ 工程化**：
  - 采用 Monorepo ，全流程执行 `pnpm verify`：整合 TS 类型系统、ESLint、Python Ruff、Vitest 与 Pytest 交叉门禁。

### 💻 更多项目实践
- **[SakiFlow](https://github.com/Azusa010/SakiFlow)**：基于 Vue 3 的前端设计。
- **[SakiVault](https://github.com/Azusa010/SakiVault)**：Vue3前端项目，使用bangumi API。
- 
### 🛠️ 技术栈
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)![CSS](https://img.shields.io/badge/CSS-563d7c?&style=flat&logo=css3&logoColor=white)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Azusa010&layout=compact)
