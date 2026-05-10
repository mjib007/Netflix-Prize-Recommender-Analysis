![Profile views](https://komarev.com/ghpvc/?username=mjib007&label=Profile%20views&color=4c8eda&style=flat)
[![Stars](https://img.shields.io/github/stars/mjib007/Netflix-Prize-Recommender-Analysis?style=flat&color=yellow)](https://github.com/mjib007/Netflix-Prize-Recommender-Analysis/stargazers)
[![Forks](https://img.shields.io/github/forks/mjib007/Netflix-Prize-Recommender-Analysis?style=flat&color=blue)](https://github.com/mjib007/Netflix-Prize-Recommender-Analysis/network/members)

# 🎬 Netflix Prize：酸民 vs. 好人預測 (推薦系統實作)

這是一個基於 2006 年 Netflix 百萬美金挑戰賽資料集的機器學習專案。透過分析電影評分數據，我們嘗試預測不同使用者對電影的評分偏好。

## 🚀 專案連結
你可以在 Kaggle 上查看完整的程式碼與執行結果：
👉 [點此查看我的 Kaggle 教材 / Notebook](https://www.kaggle.com/code/shihchiehchien/netflix-prize-vs/)

## 📝 專案目標
- **半結構化資料處理**：解析複雜的 `.txt` 格式評分資料。
- **特徵工程**：處理「資料洩漏 (Data Leakage)」問題，學習正確的特徵構建流程。
- **模型應用**：使用隨機森林 (Random Forest) 演算法預測評分。

## 💡 我學到了什麼？
1. **RMSE (均方根誤差)**：了解如何評估預測精準度，以及為什麼數字越小越好。
2. **資料清洗**：使用 `ffill` 處理缺失的 Movie ID。
3. **陷阱識別**：識別「作弊版」與「正確版」模型的差異（RMSE 從 0.71 回歸到真實的 0.95-1.0）。

## 🛠️ 使用工具
- Python
- Pandas / Numpy
- Scikit-learn
- Kaggle Environment
