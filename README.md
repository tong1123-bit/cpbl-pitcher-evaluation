# cpbl-pitcher-evaluation
# CPBL Pitcher Evaluation Model

This project presents a **pitch-type–level pitcher evaluation framework** designed to support
pitcher development and pitch usage strategy, rather than relying solely on traditional outcome-based metrics.

---

## 🔍 Why This Matters

Traditional pitching metrics such as ERA and WHIP are heavily influenced by defense, ballpark effects,
and random variation.  
This project focuses on **controllable pitch attributes** to better understand a pitcher's true skill set
and improvement potential.

---

## 📊 Core Metrics

Each pitch is evaluated based on the following dimensions:

- **Whiff (Stuff)** – Ability to generate swinging strikes  
- **Zone Control** – Ability to produce strike outcomes (called strikes, swinging strikes, fouls)  
- **Command** – Ability to avoid over-centralized, highly hittable locations  
- **Contact Risk** – Risk of hard contact when the pitch is put into play  
- **Velocity** – Baseline physical condition of the pitch

These metrics are aggregated into an **Overall Pitch Score (20–80 scale)** for intuitive comparison.

---

## 🎯 Key Insights

- Differentiates **Stuff-oriented pitchers** from **Soft-contact pitchers**
- Identifies pitchers with league-average results but high development potential
- Demonstrates how analytics can support **coaching and pitch usage decisions**, not just evaluation

---

## 🛠 Tools & Technologies

- Python
- Pandas / NumPy
- Scikit-learn
- Data Visualization

---

## ⚠️ Note on Data Usage

Raw CPBL pitch-level data are **not publicly shared** due to usage restrictions.  
Notebook structure, methodology, and feature definitions are fully reproducible.

---

---

# 中華職棒投手球種評估模型（中文說明）

本專案建立一套以「**球種層級（Pitch-Type Level）**」為核心的投手評估框架，
目的在於輔助投手養成與配球策略分析，而非僅依賴傳統結果型指標。

---

## 🔍 為什麼要做這個？

ERA、WHIP 等傳統投手指標高度受到守備、球場因素與運氣影響，
難以真實反映投手本身的能力結構。

本研究聚焦於 **投手可控的球種特徵**，
以更精細的角度理解投手的實力與成長空間。

---

## 📊 核心評估指標

每一球種從以下五個面向進行量化：

- **Whiff（揮空能力 / Stuff）**：製造揮空的能力  
- **Zone Control（進壘控制）**：製造好球結果的能力（含裁判判定好球、揮空、界外）  
- **Command（控球品質）**：避免球路過度集中於高風險區域的能力  
- **Contact Risk（被有效擊球風險）**：被強勁擊球的風險程度  
- **Velocity（球速）**：球種的基礎物理條件  

上述指標將加權整合為 **20–80 分制的 Overall Pitch Score**，
用於球種間與投手間的直觀比較。

---

## 🎯 分析成果與應用

- 區分 **Stuff 型投手** 與 **Soft Pitcher** 的不同成功路徑  
- 找出成績接近聯盟平均，但具備改善潛力的投手族群  
- 證明模型不僅能「評分」，也能實際輔助教練與球隊決策  

---

## 🛠 使用工具

- Python
- Pandas / NumPy
- Scikit-learn
- 資料視覺化

---

## ⚠️ 資料倫理與使用說明

由於資料使用限制，原始中職逐球資料未公開提供。  
本專案完整保留分析流程、方法設計與特徵定義，具備可重現性。
