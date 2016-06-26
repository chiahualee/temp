數據科學與大數據分析學期計畫
=====

###### 指導老師: 胡毓忠
###### 第八組_組員:
###### 104753032資科碩一張逸
###### 105753013資科碩一姚德謙
###### 100401048新聞四李家華


### 選擇主題:手機廣告點擊率預測<br/>
### 資料集來源: <https://www.kaggle.com/c/avazu-ctr-prediction/data> <br/>





<br/>
### 報告摘要



> 本學期計畫目的在於以團隊的方式體驗整個大數據分析的流程，組員以課堂所學習到的機器學習演算法為基礎，從網路上搜索感興趣的資料集，並利用現今最流行的大數據運算框架Spark以及內建的MLlib進行巨量資料運算，去實作分類或分群的預測。
<br/>
> 本組實際參與了於知名數據競賽平台kaggle上的一個已結案的手機廣告點擊率比賽(Click-Through Rate Prediction, CTR Prediction)，在經過特徵值挑選、各種模型的試驗、參數調整後，最終所選擇的分類器是隨機森林，我們擷取的是它善於處理高維度的特性，以及不會過度擬合(overfitting)的兩大優點來進行建模。在預測階段，於本機端執行交叉驗證(cross-validation)後實驗的最佳結果AUC為0.68，而在kaggle平台上經test-data 驗證後的準確率，本組的機器學習模型所獲得的最低損失函數log-loss的數值則約為0.76。
