# faceid
# ⚾ AI Face Recognition System
### 棒球教練與球員辨識系統（Deep Learning）

本專案基於 **深度學習（Deep Learning）與電腦視覺（Computer Vision）** 技術，開發一套可於影片中自動辨識特定人物（如教練與球員）的系統，應用於運動分析與影像辨識場景。

---

## 🎯 專案目標
- 自動辨識影片中的指定人物
- 提升辨識準確率與穩定性
- 優化影片處理效能（降低延遲）

---

## 🧠 技術架構

- **人臉辨識模型**：`face_recognition`（基於 dlib ResNet）
- **影像處理**：OpenCV
- **程式語言**：Python
- **數據處理**：NumPy

---

## ⚙️ 核心技術

### 🔹 人臉特徵編碼（Face Encoding）
將人臉轉換為 **128維特徵向量**，用於高精度比對。

### 🔹 多樣本學習（Multi-image Training）
每個人物使用多張照片訓練，提高不同角度與表情的辨識能力。

### 🔹 異常與誤判控制
透過距離閾值（Distance Threshold）調整辨識準確度，降低誤判率。

### 🔹 影像效能優化（Frame Skipping）
採用跳幀處理技術：
- 降低運算量
- 提升處理速度
- 維持辨識準確率

---

## 🚀 功能展示

- 🎥 影片人臉即時辨識
- 🟩 自動框選人物位置（Bounding Box）
- 🏷️ 顯示人物名稱標籤
- ⚡ 高效能影片處理
<img width="1696" height="732" alt="zhen" src="https://github.com/user-attachments/assets/0967b764-9a1c-4dfa-8324-7aebfa2dfb75" />

---

## 🛠️ 環境需求
請確保你的電腦已安裝以下環境：
- Python 3.12+
- OpenCV 4.9.0.80 (穩定版)
- face_recognition
- dlib
- Numpy 1.26.4 (穩定版，避免版本衝突)

