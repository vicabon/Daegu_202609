# 2026 大邱旅遊研究與 7 大 AI 景點評鑑統整紀錄 (PROMPT.md)

本文件完整記錄 2026 年大邱自由行（入住 **Eldis Regent Hotel 伊爾迪斯麗晶飯店**）在各大 AI 模型上的研究 Prompt、7 大 AI 共享研究連結、跨平台綜合評鑑數據、景點深度研究分析、同區地理統籌、純韓式藍絲帶美食替換與 18:00 前早晚餐規劃成果。

---

## 📌 一、AI 研究與任務 Prompts 原始紀錄

### 1. 跨平台社群熱門景點研究 Prompt（提交至 7 大 AI 模型）
```text
用韓文和日文和中文搜尋Naver Facebook Instagram Threads Twitter上非常著名並極為推薦的20個大邱景點 且依據討論度和評論建議程度排名
```

### 2. 7 大 AI 模型研究成果分享連結
1. **Gemini** : [https://share.gemini.google/ZYOMYbSKV5Mg](https://share.gemini.google/ZYOMYbSKV5Mg)
2. **ChatGPT** : [https://chatgpt.com/share/6a8abbc7-ec94-83e8-a800-b42c1cfcfb70](https://chatgpt.com/share/6a8abbc7-ec94-83e8-a800-b42c1cfcfb70)
3. **Grok** : [https://grok.com/share/bGVnYWN5LWNvcHk_db4e409b-14df-4118-a389-4c5ab2baa749](https://grok.com/share/bGVnYWN5LWNvcHk_db4e409b-14df-4118-a389-4c5ab2baa749)
4. **Claude** : [https://claude.ai/share/dc2cf4c0-5cbe-48a1-94c6-4acbc821b6b5](https://claude.ai/share/dc2cf4c0-5cbe-48a1-94c6-4acbc821b6b5)
5. **Qwen (千問)** : [https://qianwen.my.cn/share/chat/2647c7dac2bf438b9298bfb7382b5043?biz_id=ai_qwen&env=prod&qwcontainer=qk](https://qianwen.my.cn/share/chat/2647c7dac2bf438b9298bfb7382b5043?biz_id=ai_qwen&env=prod&qwcontainer=qk)
6. **DeepSeek (深度求索)** : [https://chat.deepseek.com/share/83rkptbrk63r33unb7](https://chat.deepseek.com/share/83rkptbrk63r33unb7)
7. **Kimi** : [https://www.kimi.ai/share/1a02df39-1dd2-89d5-8000-0000f22d90ef?sharetype=link](https://www.kimi.ai/share/1a02df39-1dd2-89d5-8000-0000f22d90ef?sharetype=link)

### 3. 統整與代碼更新任務 Prompt (1)
```text
git pull https://github.com/vicabon/Daegu_202609.git 下來

大邱景點根據下面7個AI研究的結果 統整必去的大邱景點
住在Eldis Regent Hotel (伊爾迪斯麗晶飯店) 因此主要排除交通超過1.5小時以上的景點和需要門票收費或是門票收費較貴的景點

Gemini : https://share.gemini.google/ZYOMYbSKV5Mg
ChatGPT : https://chatgpt.com/share/6a8abbc7-ec94-83e8-a800-b42c1cfcfb70
Grok : https://grok.com/share/bGVnYWN5LWNvcHk_db4e409b-14df-4118-a389-4c5ab2baa749
Claude : https://claude.ai/share/dc2cf4c0-5cbe-48a1-94c6-4acbc821b6b5
Qwen : https://qianwen.my.cn/share/chat/2647c7dac2bf438b9298bfb7382b5043?biz_id=ai_qwen&env=prod&qwcontainer=qk
Deepseek : https://chat.deepseek.com/share/83rkptbrk63r33unb7
Kimi : https://www.kimi.ai/share/1a02df39-1dd2-89d5-8000-0000f22d90ef?sharetype=link

最後將大邱景點整合並更新到index.html
再git push上github

將以上所有prompts記錄到PROMPT.md
```

### 4. 景點加入與移除調整 Prompt (2)
```text
一定加入下面兩個景點到行程中 
Suchang Youth Mansion 수창청춘맨숀
大邱藝術發電所 대구예술발전소

研究下面兩個景點是否值得加入到行程中
大邱三星創造校區 대구삼성창조캠퍼스
七星綜合市場 칠성종합시장

移除下面六個景點
前山展望台 (Apsan Observatory) 纜車夜景
大邱美術館 (Daegu Art Museum)
E-World 主題樂園 & 83塔 景觀台
大邱樹木園 대구수목원
The ARC 디아크문화관
峨洋鐵道橋 아양기찻길
```

### 5. 同區景點統籌、放假日標籤移除、18:00前晚餐、夜市調整 Prompt (3)
```text
能否將景點統籌 盡量部分區域附近景點規劃在同一次
"公司特別放假日"與"放假日經典文化特輯"拿掉
晚餐規劃在18:00以前
不用規劃晚間的七星星光夜市 (칠성야시장) 
研究"大邱三星創造校區 대구삼성창조캠퍼스"與"七星綜合市場 칠성종합시장"是否值得花時間旅遊
```

### 6. 純韓式料理替換與藍絲帶烤腸名店替換 Prompt (4)
```text
"【12 Kitchen】雙藍絲帶頂級 Fine Dining"非韓式料理 請移除並找替代方案
"安吉郎烤腸一條街 (Anjirang Gopchang)"請移除並用我Google Map上"藍絲帶"內的烤腸店取代
```

---

## 🍽️ 二、美食替換與藍絲帶認證名店深度解析

### 1. 【Day 3 午餐替代方案】龍池峰 (용지봉 Yongjibong)
* **類別**：正宗傳統韓定食 & 炭烤韓牛料理（純韓式料理，取代西式 12 Kitchen）。
* **權威榮譽**：
  * 韓國權威料理節目**《韓食大賽4 (한식대첩4)》全國總冠軍**主廚親自掌勺。
  * 長年榮獲 **Blue Ribbon Survey (블루리본 서베이) 藍絲帶認證**。
* **地理位置**：大邱廣域市壽城區德安路 9（壽城池 Deulan-gil 美食街，壽城池散步後步行即可直達）。
* **招牌菜色**：宮廷御膳韓定食套餐、炭烤特選韓牛排骨 (한우갈비살)、名品水泡菜、傳統旬味小饌。

---

### 2. 【Day 4 晚餐替代方案】Maru 烤腸 (마루막창 Maru Makchang)
* **類別**：大邱第一品牌藍絲帶認證炭烤牛/豬大腸名店（取代安吉郎烤腸街）。
* **權威榮譽**：
  * **Blue Ribbon Survey 藍絲帶評鑑認證**大邱指標性烤腸名店。
  * **Google Maps 與 Naver Map 評分最高**、外國旅客與韓國在地老饕公認大邱烤腸第一名店。
* **地理位置**：大邱壽城區壽城池6街2 (壽城池旗艦店) / 東區東村路 (東村店)。
* **招牌菜色**：炭火烤牛大腸 (소막창)、烤豬大腸 (돼지막창)、靈魂蔥花大醬沾醬 (막장)、現煮烤腸石鍋飯。

---

## 🗺️ 三、最終同區景點統籌與純韓式藍絲帶 5 日行程架構

全行程嚴格落實 **「同區景點集中、零往返折返、純道地韓式美饌、晚餐 18:00 前完成入座」**：

| 天數 | 區域主題 | 每日精選景點 (同區統籌) | 每日午晚餐 (純韓式藍絲帶認證) | 晚間休閒 (18:00後) |
|:---:|---|---|---|---|
| **D1 (週三)** | **飯店周邊徒步圈** | 機場巴士直達東大邱 ➔ Eldis Regent Hotel 入住 (青羅丘站) | 晚餐 20:15<br>【8號食堂】藍絲帶豬肉湯飯與白切肉 (步行8分) | 散步【西門夜市】感受熱鬧市井 (步行6分) |
| **D2 (週四)** | **中區文化與文創區** | 飯店門口【青蘿之丘 ➔ 3.1運動路 ➔ 桂山聖堂 ➔ 藥令市足湯】(步行1~5分) ➔ 【大邱藝術發電所 & 壽昌青春曼遜】(地鐵3號線2站4分) ➔ 【現代百貨空中花園 (淚之女王取景) & 咖啡名家】 | 午餐 12:15：美成堂扁餃子<br>**晚餐 17:30 [18:00前入座]**：<br>【東仁洞辣燉排骨 (樂榮/벙글벙글)】大邱十味 | 東城路商圈夜間流行街區散步購物，早回飯店休息 |
| **D3 (週五)** | **東南湖畔與文青區** | 【壽城池】(地鐵3號線16分，2公里環湖木棧道漫步 & 藍絲帶咖啡) ➔ 【金光石再次繪畫路】(民謠壁畫街，地鐵2號線6分) | 午餐 12:30：【龍池峰】《韓食大賽4》冠軍韓定食 & 韓牛<br>**晚餐 17:00 [18:00前入座]**：<br>【王蜘蛛食堂】藍絲帶生牛肉 Mungtigi (免排隊！) | 市中心悠閒夜風漫步，返回飯店充分放鬆 |
| **D4 (週六)** | **中央路古蹟與美食** | 【香村文化館】(1000₩復古學生服) ➔ 【慶尚監營公園】(隔壁，週六朝鮮衛兵交接儀式) ➔ 東城路商圈流行購物 | 午餐 12:30：【釜山安面屋】藍絲帶平壤水冷麵<br>**晚餐 17:15 [17:30開吃]**：<br>【Maru 烤腸 (마루막창)】藍絲帶認證炭烤牛/豬大腸 | 飯店旁【西門市場 & 西門夜市】深度二訪 (步行6分) |
| **D5 (週日)** | **伴手禮與返程** | 【三頌麵包總店】(麻藥玉米麵包 步行8分) ➔ 飯店對面【青羅丘晨光漫步】➔ 退房 ➔ 機場巴士直達金海 (70分) ➔ BX791 返台 | 早餐：三頌麻藥玉米麵包<br>午餐：金海機場免稅店 | 15:45 平安抵達桃園機場 T2 |

---

## 💻 四、已更新與推送之 GitHub 狀態

* [`index.html`](file:///home/vicabon/workspace/agy/Daegu_202609/index.html)：
  * **Tab 1（每日行程）**：Day 3 午餐全面更新為《韓食大賽4》總冠軍【龍池峰 (용지봉)】純韓式頂級韓定食與炭烤韓牛；Day 4 晚餐全面更新為大邱第一品牌【Maru 烤腸 (마루막창)】藍絲帶認證烤牛/豬大腸。
  * **Tab 3（藍絲帶名單）**：更新【龍池峰】與【Maru 烤腸】專屬藍絲帶評鑑卡片，移除西式 12 Kitchen。
* [`PROMPT.md`](file:///home/vicabon/workspace/agy/Daegu_202609/PROMPT.md)：完整收錄全階段 Prompts、研究報告、同區統籌邏輯與純韓式藍絲帶名饌歷程。
