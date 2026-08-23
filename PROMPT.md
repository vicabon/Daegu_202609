# 2026 大邱旅遊研究與 7 大 AI 景點評鑑統整紀錄 (PROMPT.md)

本文件完整記錄 2026 年大邱自由行（入住 **Eldis Regent Hotel 伊爾迪斯麗晶飯店**）在各大 AI 模型上的研究 Prompt、7 大 AI 共享研究連結、跨平台綜合評鑑數據、景點深度研究分析（三星創造校區、七星綜合市場）、同區地理景點統籌與 18:00 前早晚餐規劃成果。

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

---

## 🔍 二、深入研究：「三星創造校區」與「七星綜合市場」是否值得花時間旅遊？

### 1. 大邱三星創造校區 (대구삼성창조캠퍼스 / Daegu Samsung Creative Economy Campus)
* **景點本質**：2017 年由三星集團出資將 1954 年第一毛織舊廠址活化改建的**「新創企業辦公區＋社區休閒公園＋特色餐廳街」**。
* **主要看點**：
  1. 復原 1938 年三星創辦人李秉喆創立的「三星商會」兩層木造舊建築。
  2. 李秉喆生平與三星創業歷史展示館（約 15~20 分鐘可參觀完畢）。
  3. 復古英倫紅磚廠房與巨大煙囪、中央草坪噴泉。
  4. 進駐之連鎖咖啡館（A Twosome Place 等）與烘焙店。
* **客觀旅遊價值評鑑**：⭐⭐⭐
  * **優點**：免門票、環境清幽乾淨、英倫紅磚建築適合拍照打卡、三星發源歷史具象徵意義。
  * **缺點**：本質非大型國家級博物館或密集觀光區，歷史展示規模偏小，多數空間為一般商辦與在地居民散步場所。
  * **旅遊建議**：若為 5 天 4 夜大邱自由行，若時間緊湊或更想體驗大邱獨特歷史與文創，**建議優先保留市中心「近代文化胡同」與「大邱藝術發電所/壽昌青春曼遜」**；若想找個悠閒安靜喝咖啡拍照的地方，可作為彈性備案。

---

### 2. 七星綜合市場 (칠성종합시장 / Chilseong Traditional Market)
* **景點本質**：緊鄰鐵道與新川河畔的大型**「傳統生鮮、水產批發與民生日常市集」**。
* **主要看點**：
  1. 大邱僅次於西門市場的第二大傳統市場，以生鮮水產、乾貨、烤盲鰻一條街、豬肉湯飯街聞名。
  2. 隱藏美食：白鍾元《三大天王》推薦名店「單骨食堂 (단골식당) 炭火辣醬烤豬肉」。
* **客觀旅遊價值評鑑**：⭐⭐⭐
  * **與西門市場之比較**：
    * **西門市場**：就在住宿飯店門口（步行 6~8 分鐘），全遮雨棚、規模全韓三大、小吃種類（扁餃子、刀削麵、辣年糕）密集且具強烈觀光友善度。
    * **七星市場**：以水產、生鮮、雜貨批發為主，地面較為潮濕原生，觀光體驗感與逛街舒適度不如西門市場。
  * **旅遊建議**：由於行程已住在西門市場旁並安排西門市場巡禮，七星市場體驗性質高度重疊且較不便逛街。若非為了專程品嚐單骨食堂炭火烤肉，**不需特意花時間專程安排日間七星市場旅遊**。

---

## 🗺️ 三、同區景點統籌與 18:00 前早晚餐行程表

全行程落實**「同區景點集中、零往返拉車、晚餐 18:00 前完成入座」**：

| 天數 | 區域主題 | 每日精選景點 (同區統籌) | 晚餐規劃 (18:00前) | 晚間時光 |
|:---:|---|---|---|---|
| **D1 (週三)** | **飯店周邊徒步圈** | 機場巴士直達東大邱 ➔ Eldis Regent Hotel 入住 (青羅丘站) | 20:15 【8號食堂】藍絲帶豬肉湯飯 (步行8分) | 散步【西門夜市】感受熱鬧市井 (步行6分) |
| **D2 (週四)** | **中區文化與文創區** | 飯店門口【青蘿之丘 ➔ 3.1運動路 ➔ 桂山聖堂 ➔ 藥令市足湯】(步行1~5分) ➔ 【大邱藝術發電所 & 壽昌青春曼遜】(地鐵4分) ➔ 【現代百貨空中花園 (淚之女王取景) & 咖啡名家】 | **17:30 入座**<br>【樂榮/벙글벙글辣燉排骨】大邱十味名店 | 東城路商圈夜間流行街區散步購物 |
| **D3 (週五)** | **東南湖畔與文青區** | 【壽城池】(地鐵3號線16分，環湖木棧道 & 藍絲帶咖啡) ➔ 【12 Kitchen】雙藍絲帶Fine Dining ➔ 【金光石再次繪畫路】(地鐵2號線6分) | **17:00 開門入座**<br>【王蜘蛛食堂】藍絲帶生牛肉 Mungtigi | 市中心悠閒夜風漫步，早回飯店休息放鬆 |
| **D4 (週六)** | **中央路古蹟與美食** | 【香村文化館】(1000₩復古學生服) ➔ 【慶尚監營公園】(隔壁，週六朝鮮衛兵交接儀式) ➔ 【釜山安面屋】平壤冷麵 ➔ 東城路購物 | **17:30 入座**<br>【安吉郎烤腸一條街】大邱十味 (地鐵10分) | 飯店旁【西門市場 & 西門夜市】深度二訪 (步行6分) |
| **D5 (週日)** | **伴手禮與返程** | 【三頌麵包總店】(麻藥玉米麵包 步行8分) ➔ 飯店對面【青羅丘晨光漫步】➔ 退房 ➔ 機場巴士直達金海 (70分) ➔ BX791 返台 | 機場免稅店購物 | 15:45 平安抵達桃園機場 T2 |

---

## 💻 四、已更新與推送之 GitHub 狀態

* [`index.html`](file:///home/vicabon/workspace/agy/Daegu_202609/index.html)：每日行程（Tab 1）全面依同區景點統籌、18:00前晚餐重構，移除放假日標籤與七星夜市；Tab 5 增設三星創造校區與七星市場客觀研究評鑑卡片。
* [`PROMPT.md`](file:///home/vicabon/workspace/agy/Daegu_202609/PROMPT.md)：完整收錄 Prompt、深入研究分析、重構邏輯與行程矩陣。
