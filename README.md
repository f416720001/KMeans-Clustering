# KMeans-Clustering

##使用工具
`from sklearn.cluster import KMeans`

##此次分析項目
`X = dataset.iloc[:,[3,4]].values`
也就是針對csv檔中的年收入(Annual Income)和消費分數(Spending Score)

##整體流程
1. 先用elbow method找出適當的分群數
說明:設定一個1-11群的迴圈，找出其WCSS(組內平方和)，在從圖片中找到肘點

2. 接著把分群數n_clusters = 5後，繪出圖形

thank you github:mahesh147
