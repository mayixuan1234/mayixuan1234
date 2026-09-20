# 马怡煖 · Mayixuan1234

> 2026 届软件工程本科· 福州
> 全栈开发 / 大模型应用方向
> 能独立跑通「数据处理 → 向量库 / 知识图谱 → 大模型 API → 前后端 → 部署上线」全链路

📮 3338329122@qq.com ｜ 📱 13665029873 ｜ 📍 福州 · 随时到岗

---

## 我做过什么

四个独立完成、真实上线的项目，覆盖 RAG / 知识图谱 / 纯前端数据平台 / 三端产品。

### 1. 医疗问答系统（毕业设计 · 优秀毕设 90 分）

基于**知识图谱 + 通义千问 API** 的医疗问答系统，针对通用大模型的医疗幻觉做可追溯生成。

- 从 Huatuo-26M 抽取 **50 万+ 实体、125 万+ 关系边**，入 MySQL 轻量存储
- 「图谱检索 → 结构化 Prompt → 通义千问生成」链路抑制幻觉，支持文本+图片多模态问答
- ECharts 做图谱可视化（BFS 最短路径）
- **技术栈：** Spring Boot + MyBatis ｜ Vue 3 + Vite ｜ MySQL ｜ 通义千问 API ｜ ECharts
- 70 个测试用例全部通过；JMeter 压测 100 并发 **602.3 req/s、0 错误**

### 2. 基于 Vector RAG 的智能医疗问答助手（实践学期二等奖）

用「FAISS 向量检索 + 通义千问 API」在消费级显卡上跑起医疗 RAG。

- Huatuo-26M 清洗出约 **18 万问答对、183 万文本片段**，text2vec-base-chinese 编码 **384 维** 建 FAISS 索引
- 通义千问 Qwen-Turbo 流式输出，Gradio 做「咨询 / 用药 / 健康档案 / 对话历史」四模块
- 检索约 0.7s，问答准确率约 90%，多轮病史记忆率 95%
- **技术栈：** Python ｜ FAISS ｜ text2vec-base-chinese ｜ Gradio ｜ 通义千问 API
- 工程取舍：RTX 3050 显存不足以微调大模型，改用「向量检索 + API」零训练成本方案

### 3. 十万级订单数据分析平台（真实落地）

给粉丝社群做的浏览器端数据审核平台，纯前端零后端。

- SheetJS 本地解析 **6.8 万行** 主订单 Excel，ECharts 出多维统计
- 碎卡兑换审核 + 集赞礼兑核对，每条修改留痕
- 多管理员 4 班轮班，Cloudflare Workers KV 云端同步审核小表
- 服务 **3,400+ 用户**，已被社群实际采纳
- **技术栈：** 原生 JavaScript ｜ SheetJS ｜ ECharts ｜ Cloudflare Workers KV

🔗 在线：https://zhoukeyu-gacha-order-data-analysis.pages.dev/

### 4. 抽抽乐（盲盒抽卡）记录器 v6.1（三端产品 · 1000+ 用户）

面向粉丝社群的抽卡记录工具，Web / 微信小程序 / Android APK 三端。

- 单文件 SPA（244KB），三种录入：Excel 导入 / OCR 双引擎降级识别 / 手动录入
- 88 张卡牌图鉴、个人总抽数、9+7 档满赠追踪
- Chart.js 打包进本地实现离线可用；数据 JSON 一键导入导出
- 命令行 aapt2 + d8 + apksigner 打 Android APK（约 190KB），不依赖 Android Studio
- **技术栈：** 原生 HTML/CSS/JS ｜ Chart.js ｜ Tesseract.js ｜ Cloudflare Pages / Workers

🔗 在线：https://zhoukeyu-gacha.pages.dev/ ｜ 📦 APK 直接下载

---

## 技术栈

| 方向 | 技能 |
|------|------|
| 前端 | HTML / CSS / JavaScript，Vue 3 + Vite，ECharts / Chart.js |
| 后端 | Java (Spring Boot + MyBatis)，Python (Gradio / 脚本) |
| 大模型应用 | RAG（FAISS / text2vec）、知识图谱、通义千问 API、Prompt 工程 |
| 数据 | SheetJS / Excel 解析、数据清洗、统计可视化 |
| 部署 | Cloudflare Pages / Workers、静态站部署、命令行打 APK |
| 协作 | Git / GitHub |

---

## 作品与链接

- 在线作品集：https://zhoukeyu-gacha.pages.dev/ ｜ https://zhoukeyu-gacha-order-data-analysis.pages.dev/ ｜ https://focusworkspace.pages.dev/
- GitHub：https://github.com/mayixuan1234

---

📬 正在看**全栈 / 大模型应用**方向的机会，福州优先，可随时到岗。欢迎联系。
