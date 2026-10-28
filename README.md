# 👋 你好，我是Alex

🎓 Beijing Jiaotong University · CS
💻 AI🧠 HCI🤖 Idea💡 Biking🚴 Reading📚 Cooking🥞  
🏠 Online

---
- **飞书** ：https://hcnazkqtqx69.feishu.cn/wiki/M4Amwp68Hi8E6vkwVlAcgBUmnFf?from=from_copylink

## 🔧 技术栈

- **能力**：AI全栈 FDE部署
- **其他**：人机交互，图数据库, 用户体验，知识图谱, 算法设计

---

## 📁 项目&经历

### 🎮 BoomTap 游戏化微循环原型

*   **描述**：基于 HCI 理论与行为心理学设计的 5 秒核心微循环 H5 游戏。包含收缩环判定、多邻国级 Q 弹特效反馈及完整的数值难度曲线。
*   **技术**：Vanilla HTML/CSS/JS、Web Audio API、CSS Animations、Vibe-coding (AI 辅助开发)
*   **亮点**：纯前端单文件实现，零外部依赖，离线可跑；预埋 17 个全链路行为埋点 (Console 输出)，支持漏斗分析与 AB 测试；优化 60FPS 手感，具备防挫败机制。
*   **链接**：[GitHub 仓库](https://github.com/artist1016/minds-gamified-prototype) | [在线试玩 Demo](https://minds-gamified-prototype.vercel.app)

---

### 🧠 AI 心理教练平台 (PKU心理博士的科研团队)

*   **描述**：面向行为科学研究的 AI 心理教练 Web 平台。支持 AI 对话、用户首用体验引导，并在后台自动记录多维度的用户行为数据（对话内容、设备信息、交互时长），支持一键导出 Excel。
*   **技术**：Node.js、SQLite、智谱 GLM-4-Flash、Caddy、阿里云、PM2
*   **亮点**：全栈 FDE 独立交付，完成从云服务器部署、HTTPS 配置到数据闭环搭建；内置 Harness 风控机制（设置 Human-in-the-loop 防止 AI 幻觉）；采用 PM2 实现平滑热更新，保障数据安全。
*   **链接**：[在线体验 (前台)](https://coach.rfastgo.com/c/coach) | [系统交付与维护指南 (飞书)](https://hcnazkqtqx69.feishu.cn/wiki/M4Amwp68Hi8E6vkwVlAcgBUmnFf)

---

### 🌐 Web3 研报分析 AI Agent (Agentplace)

*   **描述**：基于 Agentplace 平台通过 Vibe-coding 搭建并发布的垂直领域 AI Agent。擅长提炼硬核英文研报，并输出结构化的四段式分析（关键事件、技术数据、核心风险、市场反应）。
*   **技术**：Agentplace、Prompt Engineering、LLM 边界约束
*   **亮点**：内置企业级数值风控护栏。当用户提问原文未提及的金融数据时，Agent 会触发 Harness 机制，拒绝瞎编并输出 `⚠️ Data not found. Requires human verification.`，确保数据安全底线。
*   **链接**：[在线体验 Demo](https://6oloyimsflps.run.agentplace.io) 

---

### 🦩 Flamatch · AI 简历 × 岗位匹配分析
- **描述：** 基于 Streamlit + Plotly 的本地优先简历匹配分析工具。上传/粘贴「目标 JD」与「你的简历」，实时对比匹配度、技能缺口与能力雷达图；内置岗位推荐页（免费公开 API），按匹配度排序并一键投递。数据本地 SQLite 持久化，可选 Supabase 云端按用户隔离同步。
- **技术：** Streamlit, Plotly, Python；Supabase（云端 Postgres + RLS）与本地 SQLite 双后端；pypdf / python-docx 文档解析；Supabase Auth 邮箱登录。
- **亮点：** 本地优先、隐私友好，云端不可用时自动回退本地，自研 SPA 导航，彻底解决 Streamlit 原生多页"新开标签页"问题，多记录文档管理：简历/JD 历史版本可随时查看、设为当前，报告可导出 JSON / CSV / Markdown；完整中英文 i18n + 多主题 + 深色模式
- **链接：** [GitHub 仓库](https://github.com/artist1016/JD-Analyzer)


### 🤖 RAG 智能文档问答助手
- **描述**：基于智谱 GLM-4-Flash 免费模型和 Streamlit 构建的轻量级 RAG 应用。支持上传 PDF/Word 文档，通过语义检索与大模型生成相结合的方式，实现基于文档内容的精准问答。独立完成文本分块、Embedding 调用、余弦相似度检索及前端界面开发。
- **技术**：Streamlit, 智谱 AI (glm-4-flash, embedding-2), Python, requests, pypdf, python-docx
- **亮点**：纯 Python 实现，无向量数据库依赖；支持相似度展示与原文引用；已部署至 Streamlit Cloud 可在线体验
- **链接**：[GitHub 仓库](https://github.com/artist1016/rag-demo) | [在线 Demo](https://rag-demo-gf3acwjuz3q7awqhtj7rvq.streamlit.app/)

---

### 🎓 毕业设计：基于知识图谱的应急事件处置问答系统
- **描述**：独立完成应急事件数据的清洗与知识图谱构建，基于Flask开发后端API，实现与Neo4j的交互，利用AC算法进行实体识别，模板匹配问答。
- **技术**：Flask, Neo4j, Python, AC算法
- **代码**：[https://github.com/artist1016/QAsystem-knowledge-graph.git]

---

### 🤖 大学生创新创业项目：基于YOLOv8的运动记录小车
- **描述**：参与YOLOv8目标检测算法在Jetson Nano上的部署，完成运动控制模块与数据采集的代码整合。
- **技术**：Python, YOLOv8, 嵌入式, 硬件调试
- **展示**：[https://cs.bjtu.edu.cn/bkstd/bkszs/dxal/yxdc/202315440.htm]

---

## 📫 联系我

- **邮箱**：1137251662@qq.com
- **手机**：19847431120

---

## ✨ 关于我

- 对AI驱动的交互产品有浓厚兴趣，善于从用户视角思考设计
- 技术改变世界，人机交互/新媒体艺术设计爱好者

---

⭐️ 欢迎来我仓库逛逛，也期待有机会一起合作！
