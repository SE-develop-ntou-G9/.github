# NTOUber 軟體需求文件(SRD)

## 專案資訊
- **專案名稱**：<span style="color:orange">海大機車共乘系統</span>  
- **撰寫日期**：<span style="color:orange">2025/10/11</span>  
- **發展者**：<span style="color:orange">王鈞宇、劉長諺、郭家齊、郭晉佑、翁世華</span>  

---

## 版次變更記錄

| 版次 |   變更項目   | 變更日期   |
| ---- |:------------:| ---------- |
| 0.1  |     初版     | 2025/10/11 |
| 0.2  | 操作概念修改 | 2025/10/16 |
| 1.0  |              |            |
 

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
- 系統目標：設計一個機車共乘平台，使用者可以上軟體尋一起共乘的使用者、尋找有無使用者可以共乘去目的地
- 系統特色：使用者可以<span style="color:orange">即時尋找</span>何時有共乘的使用者一起搭乘、<span style="color:orange">現代化</span>的介面、<span style="color:orange">客製化</span>的使用體驗、使用<span style="color:orange">及時地圖</span>顯示位置。
- (可附情境圖或架構圖，並搭配文字描述。)
- 預計的實作方案：
    - 前端語言/框架：HTML、CSS、JavaScript / React、Tailwind CSS
    - 後端語言/框架：Python / FastAPI 
    - 資料庫系統 ： MySQL
    - 部屬方式 ： 待實作
    

![螢幕擷取畫面 2025-10-16 213948](https://hackmd.io/_uploads/HyQCSdCTee.png)
![螢幕擷取畫面 2025-10-16 214010](https://hackmd.io/_uploads/BJoCH_Aalg.png)





---
## <span id="section3">操作概念 (Operational Concepts)</span>
- ### 系統管理員
    華華曾經在FB經營機車共乘粉絲專頁，因為FB的詐騙帳號太多、系統AI又有著一堆問題，加上沒有開啟審查機制，導致社團詐騙廣告、廢文滿天飛。這次他決定一切重來，寫一個網站並擔任管理員，在必要時對平台貼文進行刪除或調整 
    - #### A. 登入
        華華打開機車共乘系統，點擊登入並選擇管理員登入，接著輸入帳密登入系統。
    - #### B. 管理員主頁
        可以如同一般使用者一樣查看所有使用者的貼文，也可以查看到各貼文申請狀態並刪除異常貼文，也可對指定帳號進行警告與停權。
- ### 車主
    諺諺打算騎機車下去高雄，因為他不想讓他寶貝的<span style="color:orange">小橘</span>(FZX檔車)獨自在基隆淋雨，所以想要尋找可以陪他回高雄的好夥伴，但朋友都要坐火車回去，於是他找到了NTOUber這個平台。
    - #### A. 註冊/登入
        諺諺想找到一個夥伴一起回高雄，他碰巧發現了NTOUber並打開註冊了自己的帳號並登入。
    - #### B. 發布貼文
        諺諺點下新增貼文、輸入起點與目的地、集合時間、備註，並且允許中途下車。
    - #### C. 拒絕請求
        一開始阿瓜請求加入這趟返鄉行程，但諺諺發現這位仁兄家在南投深山中的部落中，他實在是一點都不想繞超長山路過去，瓜瓜的評分又超低，感覺超難搞，只好拒絕了他的請求。
    - #### D. 接受請求
        後來佑佑也發送了請求，希望可以在鹿港中途下車，諺諺看到了很高興，因為它可以順路去彰化看當地人狩獵肉圓，於是乎他同意了這項請求。
    - #### E. 評分 
        在約好的日子到來後，諺諺載著佑佑騎著他寶貝的小橘一路往南，在彰化佑佑表演了拿手的狩獵肉圓，諺諺十分享受這趟回家之旅，給佑佑一個五星好評。
        
- ### 乘客
    佑佑好窮，火車漲價之後又好貴好貴，想要蹭一下好心人的車回家，於是上網搜尋共乘平台。
    
    - #### A. 註冊/登入
        佑佑上網找到了NTOUber，進入首頁後發現就是他們在找的共乘app，於是註冊了帳號。
    - #### B. 尋找貼文
        佑佑打開搜尋欄，輸入起點與目的地、找到了幾個符合需求的行程並發送請求。
    - #### C. 收取通知
        佑佑打開網頁後，看到諺諺同意了他的請求，準備和諺諺一起共乘回家。
    - #### D. 評分
        和諺諺的旅程相當有趣，佑佑決定給他一個五星好評。
        
    
    

| 圖片                                                  | 功能     |
| ---------------------------------------------------    | ------------ |
| ![image](https://hackmd.io/_uploads/rkm_GFRpeg.png) | 未登入使用者：|
| ![image](https://hackmd.io/_uploads/H1DUMYCagx.png)| 已登入使用者：|
|![image](https://hackmd.io/_uploads/ByPIeK0Teg.png)|登入畫面：|
| ![image](https://hackmd.io/_uploads/H1vrbF0plg.png)|SideBar：|
|![image](https://hackmd.io/_uploads/Bk4_gKRTgg.png)| 身分選擇：|
|![image](https://hackmd.io/_uploads/ByC0gKA6lg.png)  |車主發布貼文畫面：|
|![image](https://hackmd.io/_uploads/SyIgbtRplg.png) | 評分畫面 ：|
|![image](https://hackmd.io/_uploads/SkmolYApll.png)  | 管理員主頁：|
|![image](https://hackmd.io/_uploads/r153xK0Tlg.png) | 管理員管理貼文：|

    
---

## <span id="section4">使用者故事地圖 (User Story Map)</span>

[miro](https://miro.com/welcomeonboard/Q2VNWDkwRlVGNWRqTlp2T1FTTmRhVkF3SkpBdU5oekdoWVA1bkVmUWI1OGwwTnEzNUxNb2ZnSkdwaHMzNjQvYXNJb01HOGgxUXYydkhYa255c1NMd0l0Sy9IV1BFMXRjbWNsVWVTaEJDaWJ1Zy9nTnN2cSsxRFRjMi9nRzZUV053VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=35878332944)


- 故事一 ： 諺諺想要上傳行程貼文到app
    - **代號**：<span style="color:">NTOU-Uber-01 Driver pose route</span>  
    - **故事**：<span style="color:">諺諺作為一位車主，能將即將發生的行程貼文，上傳到網站，以便尋找乘客。</span>  
    - **註記**：  
      - <span style="color:">車主能輕鬆將行程貼文，上傳到網站。</span>  
      - <span style="color:">確保後續能被潛在顧客搜尋到。</span>  
    - **測試方法**：  
      - <span style="color:">確認「上傳行程」按鈕明顯可見。</span>  
      - <span style="color:">驗證系統是否正確新增行程至網站上並清楚顯示。</span>  
      - <span style="color">確認系統有提示新增行程成功訊息。</span>  

- 故事二 ： 喜華想要尋求司機載他一起去目的地
    - **代號**：<span style="color:">NTOU-Uber-02 Client finding driver</span>  
    - **故事**：<span style="color:">喜華作為一位乘客，他能上平台尋求車主載他一起前往目的地</span>  
    - **註記**：  
      - <span style="color:">乘客能輕鬆將徵求貼文，上傳到網站，或在網站上請求車主一起共乘去目的地。</span>  
      - <span style="color:">確保徵求貼文能讓車主發現且乘客請求車主接受時能知道車主是否接受。</span>  
    - **測試方法**：  
      - <span style="color:">確認「發送請求」按鈕明顯可見跟「上傳行程」按鈕明顯可見。</span>  
      - <span style="color:">驗證請求、徵求貼文是否正確發送至司機的介面。</span>  
      - <span style="color">確認系統有提示請求、徵求貼文成功訊息。</span>  

---

## <span id="section5">使用者介面分析 (User Interface Analysis)</span>

- 首頁
- 登入
- 註冊
- 忘記密碼
- 主畫面
- 更新/新增行程
- 檢視歷史紀錄


---

## <span id="section6">功能需求 (Functional Requirements)</span>

### 基本使用者需求
1. 系統使用者分為車主與乘客兩種。  
2. 註冊需提供基本資料、聯絡方式與身分驗證。  
3. 車主可發布個人資訊（如姓名、聯絡方式、機車照片等）。  
4. 車主可設定共乘邀請（包含時間、地點、目的地等）。  
5. 乘客可搜尋符合條件的車主。  
6. 乘客可向車主發送搭乘請求。  
7. 車主可接受或拒絕乘客請求，並提供原因。  
8. 系統提供即時通知功能，更新請求狀態。  

### 進階使用者需求
1. 提供乘客查看請求狀態與歷史紀錄。  
2. 支援週期性共乘設定（如每週固定時段）。  
3. 整合地圖API，提供基本路線規劃。  
4. 系統提醒潛在時間衝突。  
5. 整合電子點數進行費用結算。  


###  系統應達到的功能：
- 系統應提供：
    -  NU-FC-RG 註冊使用者帳號
    -  NU-FC-LG 登入使用者帳號
    -  NU-FC-FB 帳號尋回功能
    -  NU-FC-ST 提供使用者查看請求狀態
    -  NU-FC-HS 提供使用者查看請求紀錄
    -  NU-FC-RM 提醒使用者潛在時間衝突
- 使用者可做：
    -  NU-US-DV 使用者能夠選擇車主的身分，並發送共乘貼文給乘客下單
    -  NU-US-PS 使用者能夠選擇乘客的身分，並發送共乘請求給司機確認是否答應請求
    -  NU-US-SR 使用者能夠透過目的地搜尋共乘貼文
---

## <span id="section7">非功能需求 (Non-functional Requirements)</span>


- 效能需求：
    - NU-NFR-T1 搜尋貼文需在3秒內回傳
    - NU-NFR-P1 是台電腦都要能用(手機：>= IPhone 6 ;電腦：>= Win10)
    - NU-NFR-T2 及時刷新 不要能夠重複點選
    - NU-NFR-U1 IQ > 0 的人都能使用 
    - NU-NFR-P2 及時反映貼文狀態

---