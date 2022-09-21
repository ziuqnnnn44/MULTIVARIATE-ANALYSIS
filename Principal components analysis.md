## Principal components analysis
單位不一致 用相關係數分析 單位被去掉

stat> mulvivate>principle components>選國文到經濟

相關係數(預設) 或共變異矩正(少用)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8e07ea2f-3641-4022-8803-599e9243c009/Untitled.png)

3.14/5(五個變異數) = 0.63

用一個變異數取代五個變數63%資訊量

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b0f73167-fc05-49be-b0e3-a6b0a02fe94e/Untitled.png)

陡坡圖 principle components>gragh>scree plot

eigenvalue 每個主成分的變異數

如何選幾個? 變異數1以上保留，pc要取代至少要比一個原來的單變數的資訊量多(假設元變異數為1) 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6a4877e3-7c56-4faf-adb4-247dbf64b2d8/Untitled.png)

---

principle components>gragh>scree plot>Score plot for first two component

pc1 pc2 沒有相關 主成分一二獨立

add> data labels>use label from column c1 ID

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fd4caa7a-e5b2-4a75-a7f8-2606a055d5c0/Untitled.png)

主成分分析>選國文到經濟>Storage>Score 放c8-c9

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0d2a911b-073e-4511-8632-299ec565891a/Untitled.png)

Stat>basic>correlation>選國文-經濟 PC1-PC2

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6288d33b-eb18-486a-99ae-e1a5d0b87503/Untitled.png)

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

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6ec51f7a-85b6-4ae5-8fa3-14a58ed48084/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9b423caf-2306-481d-9214-f92a4d7b1e35/Untitled.png)

M式距離

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9e1d9f50-1a38-42df-aff7-e6327c1a77e6/Untitled.png)

原本有許多變數 對資料做應用 太多複雜

用主成分分析 

管制圖 >監控主成分 兩個變數 幾乎代表所有變數
