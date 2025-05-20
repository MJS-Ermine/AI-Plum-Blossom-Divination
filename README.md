# 梅花問卦．智能解易
# AI Plum Blossom Divination

## 專案簡介 | Project Introduction

本專案是一個結合 RAG（檢索增強生成）、LLM（大型語言模型）、Gradio 互動介面與易經卦象資料庫的智能解卦系統。用戶可輸入問題，系統自動起卦並給出專業的易經解釋與建議。

This project is an AI-powered I Ching (Yijing) divination system, combining RAG (Retrieval-Augmented Generation), LLM, Gradio UI, and a comprehensive hexagram database. Users can ask questions, and the system will generate a hexagram and provide professional interpretations.

## 主要功能 | Features
- 隨機起卦與動爻判斷
- 支援 RAG + LLM 智能解卦
- 3000 筆訓練資料，64 卦完整建議
- Gradio 互動網頁介面
- 支援自訂問題輸入

## 安裝方式 | Installation
```bash
# 建議使用 Python 3.10+
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## 快速開始 | Quick Start
```bash
python aifortune.py
```

## 資料來源 | Data Source
- yijing_training_data_3000.jsonl：自動生成的易經卦象問答資料集
- 64卦建議資料整理

## 貢獻方式 | Contribution
歡迎提交 issue、pull request 或建議改進！

Contributions are welcome via issues, pull requests, or suggestions.

## 授權條款 | License
本專案採用 MIT License。

This project is licensed under the MIT License.
