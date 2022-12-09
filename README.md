**:smiley:AICUP2022_無人機飛行載具之智慧計數競賽:smiley:**
=
[無人機飛行載具之智慧計數競賽](https://tbrain.trendmicro.com.tw/Competitions/Details/25)
-

**指導教授: 劉宗榮**

**隊伍名稱:Team_2059**

**隊長:陳語嫣，組員:方峻梃、廖浩翔、謝東格、張祐嘉**

Implementation of paper - [YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors](https://arxiv.org/abs/2207.02696)



```
├── README.md    

主要訓練程式碼
├── runs
│   ├── train               存放訓練權重資料夾
│   ├── detect              存放 public 跟 private 輸出資料夾 
│   └── save                存放 public 跟 private .csv 輸出資料夾 
├── make_txt.py             把主辦單位給的csv轉成相關格式
├── 目標數據集
│   ├── train.txt           轉檔後的訓練標籤檔
│   ├── val.txt             轉檔後的驗證標籤檔 
│   ├── train               存放 train 的 image 跟 labels 資料夾
│   └── save                存放 val 的 image 跟 labels 資料夾
├── train.py                執行訓練及其他參數調整
├── runs
│   ├── train               存放訓練權重資料夾
│   ├── detect              存放 public跟private 輸出資料夾 
│   └── save                存放 public跟private .csv 輸出資料夾 
├── data_arg
│   ├── ENSEMBLE            不同模型跟csv結合
│   ├── AUGMENTATION_       資料擴增、翻轉、旋轉       
│   
│
├── log                     訓練loss可視化(tensorboard)
├── wandb                   訓練loss可視化(wandb)
├── yolov7.pt               YOLOv7 pretrained model
├── yolov7_w6.pt            YOLOv7_w6 pretrained model   

主要測試程式碼

├── detect.py               輸出 public 跟 private 資料集
├── csv_output.py             將 public 跟 private 資料集結果轉為.csv  

```





**Training**
-



