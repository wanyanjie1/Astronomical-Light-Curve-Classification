# Astronomical Light Curve Classification (天文光變曲線分類)

## 專案簡介
本專案基於 Kaggle 競賽數據，利用機器學習模型 (LightGBM/XGBoost) 分析天文光變曲線，自動分類不同類型的天體（如變星、超新星）。

## 使用技術 (Tech Stack)
* **語言:** Python 3
* **模型:** LightGBM, XGBoost (Ensemble Learning)
* **特徵工程:** * 物理特徵提取 (顏色/溫度、週期性)
    * 訊號處理 (Von Neumann Ratio, Skewness, Kurtosis)
    * 誤差加權處理 (Weighted Mean)
* **驗證策略:** Stratified K-Fold Cross Validation

## 成果
* 使用 K-Fold 交叉驗證尋找最佳閾值 (Threshold Optimization)。
* 成功利用物理特徵提升模型準確度。
