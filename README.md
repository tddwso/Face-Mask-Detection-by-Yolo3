# Face-Mask-Detection-by-Yolo3
## 背景介紹:
建構辨識是否有戴口罩的人臉辨識系統模型

![image](https://github.com/tddwso/Face-Mask-Detection-by-Yolo3/blob/main/pic.PNG)

## 預計完成目標:
使用的模型: Yolo3
## 資料集:
Train Data : 853

來源位址: https://www.kaggle.com/andrewmvd/face-mask-detection

## 使用環境:
Python 3.8

TensorFlow 1.10 
## 訓練和測試結果
結果為VGG16最佳，模型訓練準確度100%
 
Xception最佳的訓練模型準確率(accuracy): 80%

Resnet50最佳的訓練模型準確率(accuracy): 60%

Nasnet最佳的訓練模型準確率(accuracy): 60%
 

![image](https://github.com/tddwso/Covid-19-identity/blob/main/ACC.PNG)

ROC曲線 (Receiver operating characteristic curve) & AUC (Area Under Curve)

ROC曲線會以對角線為基準，曲線下的面積(AUC)來判別ROC曲線的鑑別力，AUC數值的範圍從0到1，數值愈大，代表模型的鑑別力越好。

![image](https://github.com/tddwso/Covid-19-identity/blob/main/ROC.PNG)

實際測試結果(是否感染分類編號{'covid': 0, 'normal': 1})

![image](https://github.com/tddwso/Covid-19-identity/blob/main/test.PNG)


























