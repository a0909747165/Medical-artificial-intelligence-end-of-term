# Medical-artificial-intelligence-end-of-term
心臟病數據分析
關於心臟病
據世界衛生組織統計，每年有 1790 萬人死於心髒病。醫學研究表明，人類的生活方式是導致這種心臟問題的主要原因。除此之外，還有許多可能是心臟病成因的重要因素。我們將從從病理資料集中，以數據分析作為起點搭配創建合適的機器學習技術來更準確地對心臟病進行分類，這對醫療組織和患者都非常有幫助。


下載資料集

認識資料集 - 探索性資料分析
本資料集是結構化的表單資料，提供了與心臟病相關的信息。資料中的每一列代表一個病患的臨床紀錄，有 14 個欄位，其中 13 個欄位是臨床特徵以及 1 個欄位表示該病患是否患有心臟病。這裡的目的是使用探索性資料分析，找出與心臟病有高相關性的關鍵因子。

特徵含意

Age (病患年齡)
Sex (性別 女性:0 男性:1)
CP (胸痛類型 值1: 典型心絞痛 值2:非典型心絞痛 值3:非心絞痛 值4:無症狀)
TRESTBPS (靜息血壓)
CHOL (血清膽固醇)
FBS (空腹血糖 > 120mg/dl) (1 = true; 0 = false)
RESTECH (靜息心電圖 值:0,1,2)
THALACH (達到的最大心率)
EXANG (運動誘發的心絞痛 (值0:沒有 值1:有))
OLDPEAK (由運動引起的 ST 值)
SLOPE (運動高峰時的 ST 值坡度)
CA (螢光染色的血管數量 (0-3))
THAL (地中海貧血症 值3:正常; 值6:固定缺陷 值7:可逆轉缺陷)
TARGET (是否有心臟病 值0:沒有 值1:有)


資料前處理


欄位與型別轉換


哪些特徵有明顯的分布差異嗎？


訓練、驗證集切分與Logistic模型訓練



Logistic 模型擬合與模型評估



Conclusion
1) Extreme Gradient Boost gives the best Accuracy compared to other models.

2) Exercise induced angina,Chest pain is major symptoms of heart attack.

3) Ensembling technique increase the accuracy of the model.

Feel free to ask any question related to this topic. I'm happy to answer. If you like my work please upvote.

HAPPY LEARNING :-)
