## Principal components analysis
單位不一致 用相關係數分析 單位被去掉

stat> mulvivate>principle components>選國文到經濟

相關係數(預設) 或共變異矩正(少用)

![image](https://user-images.githubusercontent.com/66659394/191564395-7e3ee4f0-8a5f-481d-a5ca-4843395aa926.png)


3.14/5(五個變異數) = 0.63

用一個變異數取代五個變數63%資訊量

![image](https://user-images.githubusercontent.com/66659394/191564508-1cb6f1bd-c4a1-4551-b14f-f607bfdce3d4.png)

陡坡圖 principle components>gragh>scree plot

eigenvalue 每個主成分的變異數

如何選幾個? 變異數1以上保留，pc要取代至少要比一個原來的單變數的資訊量多(假設元變異數為1) 

![image](https://user-images.githubusercontent.com/66659394/191564587-6bfe93e6-8879-461e-99fa-222014397183.png)

--

principle components>gragh>scree plot>Score plot for first two component

pc1 pc2 沒有相關 主成分一二獨立

add> data labels>use label from column c1 ID

![image](https://user-images.githubusercontent.com/66659394/191564737-67a534d9-0c89-450c-9b09-9114aa51919e.png)

主成分分析>選國文到經濟>Storage>Score 放c8-c9

![image](https://user-images.githubusercontent.com/66659394/191564805-0c66c049-d0a5-47e2-8d7d-5f8e05293cb5.png)

Stat>basic>correlation>選國文-經濟 PC1-PC2

![image](https://user-images.githubusercontent.com/66659394/191564858-1d8be5c0-b954-4df9-b881-1b97985c73c0.png)

一號和三號組成分的得分最大 兩位的平均得分最高分

九號和十四號每科較低分

PC1 數字不清楚意思 但大小可以表示 

大的人平均學科能力好

小的人總學科不理想

PC2高的人 統計經濟的成績好 國文英文成績弱

誰會在2上得高分 統計經濟比國文英文好的

2 高分 數理優於語言能力 (對比大的)

2 低分 語言優於數理

Loading 相關係數

Loading plot

![image](https://user-images.githubusercontent.com/66659394/191564927-359e02c5-a5b1-4907-b6ec-7c712f3b14ca.png)

![image](https://user-images.githubusercontent.com/66659394/191564981-6330897d-a7ed-40c4-832b-8ca9ec81897f.png)

M式距離

![image](https://user-images.githubusercontent.com/66659394/191565026-18bad6af-dcc3-4871-9bea-0b73cca0b6fe.png)


原本有許多變數 對資料做應用 太多複雜

用主成分分析 

管制圖 >監控主成分 兩個變數 幾乎代表所有變數
