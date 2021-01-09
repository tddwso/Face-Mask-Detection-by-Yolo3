# Face-Mask-Detection-by-Yolo3
## 背景介紹:
建構辨識是否有戴口罩的人臉辨識系統模型

![image](https://github.com/tddwso/Face-Mask-Detection-by-Yolo3/blob/main/pic.PNG)

## 預計完成目標:
建立YOLO訓練模型，辨識信心度達到80%以上

## 使用的模型: 
YOLOv3 (即時物件偵測)

YOLOv3是目前對於物件偵測被最廣泛應用的一項技術，先在影像中框出bounding box選出懷疑候選的區域,再針對bounding box裡的資訊截取特徵值解析並分類。
## 資料集:
Train Data : 853

來源網址: https://www.kaggle.com/andrewmvd/face-mask-detection

## 使用環境:
Python 3.8

TensorFlow 2.3.1 
## 訓練和測試結果

![image](https://github.com/tddwso/Face-Mask-Detection-by-Yolo3/blob/main/IMG_2334_mask.JPG)

## 使用Streamlit App展示成果

![image](https://github.com/tddwso/Uniqlo-Label-Defect-Classification-by-Deep-Learning/blob/main/Stream%20Logo.png)

Streamlit 是一個開源Python函式庫，可以快速製作Data App。

實作影片(以下為Youtube影片連結)

APP操作方法:

1.開啟資料夾選取想要測試的影像

2.APP執行影像辨識

3.顯示辨識結果
[![IMAGE ALT TEXT HERE](https://github.com/tddwso/Face-Mask-Detection-by-Yolo3/blob/main/streamlit.PNG)](https://youtu.be/6oOH7tESTw0)





