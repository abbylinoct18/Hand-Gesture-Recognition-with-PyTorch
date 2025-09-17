# Hand-Gesture-Recognition-with-PyTorch
本專案使用 [Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog/data)
透過 **PyTorch CNN 模型** 對手勢影像進行辨識。

---

## 📊 專案目標
1. 使用 64x64 影像建立 CNN 模型。
2. 訓練模型以辨識手勢類別。
3. 展示單張影像的手勢辨識效果，可用 LeapHandGestUAV Dataset 進行測試。

---

## 🛠 使用技術
- **Python**：PyTorch, torchvision, PIL, matplotlib
- **資料前處理**：Ltransforms.Resize, ToTensor, Normalize
- **CNN 模型**：兩層卷積 + 全連接層 + Dropout
- **訓練策略**：CrossEntropyLoss, Adam 優化器
- **驗證**：計算 Validation Accuracy

---

## 📂 資料來源
- 建模資料集: [Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog/data)
- 單張測試資料集: [LeapHandGestUAV Dataset](https://www.kaggle.com/datasets/gti-upm/leaphandgestuav/data)

---

## 📊 單張測試成果
* Predicted class: 02_l
<img width="552" height="388" alt="image" src="https://github.com/user-attachments/assets/fe18a70e-0ac5-4f1f-80bb-876e868874cf" />

👉 測試正確。
