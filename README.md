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
2. 將擷取的文本內容導入作業3，幫忙撰寫總結、情意分析、標籤等。
3. 最後，串聯作業4，提供給公關人員原文，讓她可以查找相關資訊。
#UI初稿
1. [Google Sites](https://sites.google.com/view/net-learning-yayun/首頁)
#實作步驟
1. 擷取網路聲量，並提煉關鍵字。
2. 將擷取的描述內容，新增摘要、情意分析分數與正負向標籤。
3. 新增歷史關鍵字查詢功能、全文搜尋功能。
#UI成品code：[FinalReport_clean.ipynb](https://github.com/YaYunnnnn/net_learning/blob/main/FinalReport_clean.ipynb)
#應用情境：
公關人員可透過一站式介面，進行網路文章搜尋，
並且快速了解該對應文章的正負向情感標籤。
也可以針對該搜尋結果，請AI自動生成摘要，以了解本次搜尋的討論重點。
而他若是想要針對每篇文章的關鍵字，也可以在第一頁搜尋。
兩個功能分開之目的在於讓user能快速了解每篇文章之重點，若需要簡略摘要，則可在新畫面中搜尋。
雖然資料有串聯後台進行保存，但讓user另外開啟檔案進行檢所又會是多一個步驟。
故在本介面也新增該功能，使其可以快速檢索過去有查詢過的關鍵字，並能直解檢閱該內容。
更提供他能進行全文搜尋，讓其能方便的找到自己所需的資料。
