# Data_Mining_2019_HW4
1.讀入資料集後檢查資料集是否有空值，假如資料有空值，利用 dropna()去掉空值。
2.將最後一個屬性值”target”切分成Label，其餘屬型切分為Feature
3.將Feature用sklearn.preprocessing的StandardScaler進行標準化
4.切分資料集與測試集，設 test_size=0.33，random_state=1 
5.最後，使用sklearn.svm裡的SVC進行分析，kernel設為'linear'，模型最終的準確度約為 0.89
