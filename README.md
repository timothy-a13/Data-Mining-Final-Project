# Data-Mining-Final-Project (MOSR)

## 環境架設

我們是用anaconda環境進行實作，於是我們將環境匯出成environment.yml
<br/>
可以透過以下指令載入環境：
```
conda env create -f environment.yml
```
而後的程式皆使用這個環境運行

## 程式執行

在報告中的最終數據複現，首先要先cd到code資料夾後，接著可利用該指令：
```
python model_new.py -model_load True
```
這個指令會從model資料夾中載入模型，並且從data資料夾載入已經愈處理過的2002 erone dataset，並輸出最終的error，前幾項為不同的OWA單獨的error，最後一項為模型結合所有OWA後最終的error。

## 重新訓練

若是要重新訓練，請先至<br/>
1. https://www.cs.cmu.edu/~enron/
2. https://www.kaggle.com/datasets/wcukierski/enron-email-dataset
<br/>
這兩處下載資料
<br/>
而後通過執行check_data.py和check_data_distance_2.py來完成資料的前處理
