---
# System prepended metadata

title: 軟體需求文件(SRD)

---

# 軟體需求文件(SRD)

> 📌 本文件為範本，需依實際專案調整。  
> - <span style="color:red">紅字為說明，請刪除</span>  
> - <span style="color:blue">藍字為範例，除「接受準則」外皆應修改，並改為黑字(去掉span標籤即可)</span>  

---

## 專案資訊
- **專案名稱**：<span style="color:lightblue">海大機車共乘系統</span>  
- **撰寫日期**：<span style="color:lightblue">2025/10/11</span>  
- **發展者**：<span style="color:lightblue">王鈞宇、劉長諺、郭家齊、郭晉佑、翁世華</span>  

---

## 版次變更記錄

| 版次 | 變更項目 | 變更日期 |
|------|----------|----------|
| 0.1  | 初版 | 2025/10/11 |
| 0.3  |          |          |
| 0.4  |          |          |
| 0.5  |          |          |
| 0.6  |          |          |
| 1.0  |          |          |

> ℹ️ <span style="color:red">版本紀錄對文件非常重要，請務必於每次改版時修正。</span>  

---

## 目錄
1. [接受準則 (Acceptance Criteria)](#section1)  
2. [系統概述 (System Description)](#section2)  
3. [操作概念 (Operational Concepts)](#section3)  
4. [使用者故事地圖 (User Story Map)](#section4)  
5. [使用者介面分析 (User Interface Analysis)](#section5)  
6. [功能需求 (Functional Requirements)](#section6)  
7. [非功能需求 (Non-functional Requirements)](#section7)  

---

## <span id="section1">接受準則 (Acceptance Criteria of this document)</span>
- Clearly and properly stated（需求需清楚且適當的陳述）  
- Complete（需求需完整）  
- Consistent with each other（需求之間需維持一致性）  
- Uniquely identified（每項需求有明確之識別）  
- Appropriate to implement（需求需可被實作）  
- Verifiable（需求需可被驗證）  

---

## <span id="section2">系統概述 (System Description)</span>
- <span style="color:red">簡要說明系統之目標與特色。</span>  
- <span style="color:red">可附情境圖或架構圖，並搭配文字描述。</span>  
- <span style="color:red">概述預計的實作方案（如前後端語言/框架、部署方式）。</span> 
- 目標：設計一個機車共乘平台，使用者可以上軟體尋一起共乘的使用者、尋找有無使用者可以共乘去目的地
- 特色：使用者可以<span style="color:lightblue">即時尋找</span>何時有共乘的使用者一起搭乘、<span style="color:lightblue">現代化</span>的介面、<span style="background-color:blue">客製化</span>的使用體驗、使用<span style="color:lightblue">及時地圖</span>顯示位置。
- 預計的實作方案：
    - 前端語言/框架：HTML、CSS、JavaScript / React、Tailwind CSS
    - 後端語言/框架：你媽 FastAPI / 
    - 部屬方式：

---

## <span id="section3">操作概念 (Operational Concepts)</span>
- <span style="color:red">以故事性方式描述系統的運作與特性。</span>  
- <span style="color:red">可將使用者故事整理成圖文並陳述。</span>  
- <span style="color:red">針對特定情境、角色說明使用方式。</span>  
- <span style="color:red">可適當加入 Wireframe。</span>  
- 

| 系統管理員 |
| -------- |
| 曉華曾經在FB經營機車共乘粉絲專頁，因為FB的詐騙帳號太多、系統AI又有著一堆問題，加上沒有開啟審查機制，導致社團詐騙廣告、廢文滿天飛。這次他決定一切重來，寫一個網站並擔任管理員，在 |


---

## <span id="section4">使用者故事地圖 (User Story Map)</span>
- <span style="color:red">建立完整的使用者故事地圖（User Story Map），以簡短名稱標記。</span>  
- <span style="color:red">對 **MVP** 的使用者故事進行細部分析，並加上註記與測試方式。</span>  

### 範例使用者故事卡片
- **代號**：<span style="color:blue">MS-US-01 Add to basket</span>  
- **故事**：<span style="color:blue">作為一位購物者，我能將欲購買的商品加入購物車，以便稍後購買。</span>  
- **註記**：  
  - <span style="color:blue">使用者能輕鬆將商品加入購物車。</span>  
  - <span style="color:blue">確保後續能進行結帳。</span>  
- **測試方法**：  
  - <span style="color:blue">確認「加入購物車」按鈕明顯可見。</span>  
  - <span style="color:blue">驗證商品是否正確新增至購物車並清楚顯示。</span>  
  - <span style="color:blue">確認系統有提示新增成功訊息。</span>  

---

## <span id="section5">使用者介面分析 (User Interface Analysis)</span>
- <span style="color:red">UI 說明與分析可使需求更清楚。</span>  
- <span style="color:red">搭配操作概念與使用者故事，說明核心介面設計。</span>  
- <span style="color:red">應補充必要文字說明。</span>  

---

## <span id="section6">功能需求 (Functional Requirements)</span>
- <span style="color:red">根據操作概念，分析系統應達成的功能。</span>  
- <span style="color:red">建議撰寫方式：</span>  
  - 「<span style="color:blue">系統應提供……</span>」  
  - 「<span style="color:blue">使用者可……</span>」  
- <span style="color:red">每一項需求需有唯一編號（介面需求、效能需求亦同）。</span>  

---

## <span id="section7">非功能需求 (Non-functional Requirements)</span>
- <span style="color:red">至少應包含效能需求。</span>  
- <span style="color:red">效能需求描述應具體、可量化，方便驗證。</span>  

### 範例：
- <span style="color:blue">關鍵字搜尋需於 **7 秒內** 回傳結果，並呈現完整搜尋頁面。</span>  

---