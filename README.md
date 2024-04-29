# 張雅雲＿網路輔助學習系統研究

## 作業1：
1. 前測：[pretest.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/pretest.ipynb)
2. 中測：[mid_test.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/mid_test.ipynb)
3. 後測：[End＿test.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/End%EF%BC%BFtest.ipynb)

## 作業2：將影片內容進行文字稿提取。
內容：[video2audio.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/video2audio.ipynb)

## 作業3：串接兩個API
1. 內容：[hk3_github_version.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/hk3_github_version.ipynb)
2. 應用情境：公關部門或是教育訓練單位，可以透過民眾或學員的文字反饋，了解文字中所透漏的情緒與在乎的重點。
3. 功能：
   1. 執行文本總結：提供手寫文字與文本的導入
   2. 進行情意分析：分析正向／負向的占比是多少
   3. 將內容標籤分類：提供手動輸入／文本導入
4. 提取的文字文本：[hk3.txt](https://github.com/YaYunnnnn/net_learning/blob/main/hk3.txt)

## 作業4：串接RAG判斷文本內容
1. 內容：[HK4_github.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/HK4_github.ipynb)
2. 目的:因為內容範圍小且明確，可以先使用該語法就能符合需求
3. 使用場景:
   1. 先前將文本進行彙整，並且執行了情意分析、貼標等動作。(HK3)
   2. 但在這過程中，皆為AI model運算之結果。
   3. 在實際的應用場域中，user可能會希望針對自己想確認的資訊進行檢索，故串聯該RAG。
   如:AI_summary，說他是一個經驗豐富的演說家，但並未揭露有幾年的演說經驗。故此法將針對想進一步了解的資訊進行搜尋。
   4. 協助user不論在要重新編修summary或添加自己看法時，都能快速校對與查閱資料。(並註記資料頁數，協助查閱完整前後文)
4. 來源：https://github.com/pecu/LLM-RAG-Gradio/blob/main/RAG-Student-Success.ipynb

## 作業5：在google news做關鍵字擷取，並將內容彙整出googlesheet。 
1. 內容：[HK5.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/HK5.ipynb)
2. 使用情境：公關每日近期公司網路討論文章，了解外界對於公司的輿論風向與討論要點。

## 期末報告：
#思考步驟
1. 作業5擷取網路聲量，並提煉關鍵字。
2. 將擷取的文本內容導入作業3。
