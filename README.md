# 🚀 LLM + LangChain 實戰應用課程  
## 從零到上線：LangChain × 多模態 LLM 實戰營（2026 最新版）

> 一門帶你把 LLM 真正做成「產品」的實戰課程，從原型到可部署的多模態 AI Agent。

---

## 📌 課程資訊

- **課程時長**：8 週（每週 3 小時實作）
- **上課方式**：Jupyter Notebook 互動教學 + 每週實作專案
- **適合對象**：
  - 軟體工程師 / 後端工程師，想升級 AI 開發能力
  - 產品經理 / 創業者，想理解 LLM 產品化的技術邊界
  - 資料科學家 / AI 工程師，想補齊工程化部署能力
  - 想用 LLM 接案、創業或打造 SaaS 產品的你
- **難度**：中上～進階（建議具備 Python 實務開發經驗，熟悉基本 API 概念）
- **學習曲線**：前 3 週友善入門，第 4 週起密度與深度明顯提升；第 7-8 週進入 Agent 架構是整門課最硬的段落

---

## 🎯 課程目標

完成課程後，你將能：

- 熟練使用 **LangChain / LangGraph** 打造 Chain、Agent 與 Tool Calling 工作流
- 建構 **RAG 知識庫**（稠密 × 稀疏混合檢索），掌握 Embedding 與語意搜尋的底層原理
- 實作 **Reflection Pipeline**：讓 LLM 自我反思、審核並自動修訂輸出
- 打造 **文字 × 圖像 × 語音** 的多模態 AI 產品（理解、生成、閉環對話）
- 導入 **MLflow** 進行實驗追蹤、Prompt 版本管理與模型 Registry 部署
- 透過 **LangServe / Flask / Streamlit** 將專案部署成可展示、可上線的服務

---

## 🗺️ 課程大綱

| 週次 | 主題 | 難度 | 學完你會做到 | 核心技術 | 作業 / 專案 |
|------|------|------|---------------|-----------|--------------|
| 1 | LangChain 入門與核心組件 | 🟢 入門 | 30 分鐘內上手 OpenAI API，透過系統提示與角色 Prompt 控制輸出格式 | LLM、PromptTemplate、Structured Output、SystemMessage | Gordon Ramsay 吐槽機 + 唐詩生成器 |
| 2 | Prompt 工程 + 語意檢索 | 🟡 中等 | 自建知識庫、語意搜尋（稠密 × 稀疏混合檢索），測試模型穩健性 | FAISS、BM25、Ensemble Retriever、Word2Vec、Gensim | 唐詩三百首語意搜尋 + 風格 RAG |
| 3 | RAG 進階 + MLflow 實驗追蹤 | 🟡 中等 | 風格化 RAG、N-Shot 自動分類、非同步爬蟲建立職缺知識庫 | N-Shot、MLflow、非同步爬蟲、FAISS | 履歷–職缺自動匹配系統 |
| 4 | Reflection Pipeline + MLflow 模型管理 | 🟠 中上 | 自我反思→修訂的多階段流程，學會用 LangServe / Flask / Streamlit 三種方式部署 | Reflection、Pydantic、RunnablePassthrough、LangServe、MLflow Registry | 作文自動批改 + 重寫系統 |
| 5 | 多模態：圖像理解 × 文件解析 | 🟡 中等 | 讓 LLM 看懂圖片（二次元標籤＋通用描述），解析 PDF 與非結構化文件 | GPT-4o、WD-14、Florence-2、Unstructured、Gemma 4 | 二次元角色心理側寫器 + 文件解析流水線 |
| 6 | 語音閉環：STT + TTS + 本地部署 | 🟠 中上 | 說話→辨識→理解→語音回覆，逐步迭代 v1~v5，支援 Ollama 本地模型 | Whisper、TTS、Ollama、LangServe、Video-to-Frames | 語音點餐機器人 |
| 7 | 文生圖 + LangGraph Agent | 🔴 進階 | 自動化圖像生成 Agent，含工具調用（搜尋／計算／向量庫）與圖生圖 | GPT-Image-2、LangGraph、WD-14、LCEL、Tool Calling | 自動化繪本單頁生成器 |
| 8 | 🎓 期末專案：多模態 Agent 工廠 | 🔴 進階 | 串接文字→圖片→語音，多 Agent 協作（規劃→審核→微調→數學驗證） | LangGraph Agent、Multi-Agent、GPT-Image-2、TTS、LangServe | 全自動有聲繪本生成工廠 |
| ✨ Bonus | NotebookLM Python API | 🟡 中等 | 將課程內容一鍵轉成 Podcast、影片、投影片、心智圖、閃卡 | NotebookLM API、Async I/O | 雙人對話 Podcast + 全自動內容工廠升級 |

---

## ✨ 課程特色

- ✅ **100% 實作導向**：每週產出一個可放入作品集的專案，期末整合為完整產品
- 🔥 **2026 最新技術**：
  - GPT-4o / GPT-Image-2 / GPT-4o-mini-TTS
  - LangGraph Agent + Multi-Agent 協作
  - MLflow 全流程：實驗追蹤 → Prompt 版本管理 → 模型 Registry
  - WD-14 / Florence-2 / Unstructured / Gemma 4
- 🧠 **多模態全覆蓋**：文字理解 × 圖像生成 × 語音閉環（STT + TTS）
- 🔓 **雲地雙方案**：
  - OpenAI API（雲端快速迭代）
  - Ollama（本地部署，適合敏感資料與私有模型）
- 🏗️ **生產級思維**：從 Notebook 原型 → LangServe API → Flask/Streamlit 前端，一套完整部署管線
- 🎁 **Bonus 模組**：NotebookLM API — 從課程內容一鍵生成 Podcast、影片、投影片、心智圖

---

## 🎁 結業你將擁有

- 🎨 一個完整可展示的 **AI 產品原型**，例如：
  - 自動有聲繪本工廠
  - 語音點餐助理
  - 圖文生成 Agent
- 📂 可直接放入作品集 / Demo / 提案
- 🚀 具備從 **Prototype → MVP → 上線** 的實戰能力

---

## 🛠️ 技術棧

**框架與工具**
- Python 3.10+, LangChain, LangGraph, LangServe
- FastAPI, Flask, Streamlit

**模型與 API**
- OpenAI API：GPT-4o, GPT-Image-2, GPT-4o-mini-TTS, Whisper
- HuggingFace：Gemma 4
- 本地：Ollama（Llama, Qwen 等開源模型）

**檢索與向量**
- FAISS, BM25, Ensemble Retriever
- Gensim, Word2Vec

**影像與文件**
- WD-14 Tagger, Florence-2
- Unstructured（PDF / 文件解析）

**MLOps**
- MLflow（Tracking, Registry, Prompt Management）

**內容自動化**
- NotebookLM Python API（Podcast / Video / Slide Deck / Mind Map）

---

## 📣 適合誰加入？

如果你想要：

- 把 LLM **從玩具變成真正能賣、能用的產品**
- 不只會 `pip install openai`，而是會設計 **RAG 管線、Agent 架構、部署策略**
- 理解 Prompt Engineering 的底層原理（Embedding、檢索、Reflection），而不只是瞎試關鍵字
- 在 2026 年站上 **AI 工程實戰前線**，具備端到端交付能力

👉 這門課就是為你設計。

---

> Made with ❤️ for builders who want to turn LLMs into real products.
