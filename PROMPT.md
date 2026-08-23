# 2026 大邱旅遊研究與 7 大 AI 景點評鑑統整紀錄 (PROMPT.md)

本文件完整記錄 2026 年大邱自由行（入住 **Eldis Regent Hotel 伊爾迪斯麗晶飯店**）在各大 AI 模型上的研究 Prompt、7 大 AI 共享研究連結、跨平台綜合評鑑數據、景點深度研究分析、同區地理統籌、純韓式藍絲帶美食替換、18:00 前早晚餐規劃與色彩模式（淺色/暗色/系統預設）設計升級成果。

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

### 8. 夜市取消、日間西門市場文創統整、名店精確替換與時段化標記 Prompt (6)
```text
取消夜晚西門市場/西門夜市
但安排其他天日間西門市場與大邱藝術發電所 & 壽昌青春曼遜一起  早午餐安排西門市場內美城堂薄餃子 미성당납작만두 본점、烤肉串、五花肉飯捲與各式創意甜品
第一天晚餐不吃 去LOTTE超市 南山店 롯데슈퍼 남산점採買
第二天午餐改成巨松燉排骨 거송갈비찜一開門去排隊 再安排原本其他觀光行程
現代百貨觀光那天晚餐改成泰山餃子 태산만두
壽城池觀光那天午餐改成萬壽炸雞 만수통닭 수성못본점
Maru 烤腸 (마루막창 Maru Makchang)】改成格利佛烤腸 걸리버막창 동성로점
還要安排一餐為8號食堂 本店 8번식당 본점  原本安排的Wanggeomi Restaurant 왕거미식당 韓式牛肉料理也必須有
不刻意安排時間 僅表示早上 下午 晚上
```

---

## 🎨 二、系統主要色彩模式（淺色 / 暗色 / 系統預設）設計架構

* **自動偵測系統色彩模式**：
  * 採用標準 CSS 媒體查詢 `@media (prefers-color-scheme: light)` 與 `@media (prefers-color-scheme: dark)`，無須額外設定即自動符合使用者裝置與作業系統（iOS / Android / macOS / Windows / Linux）之預設外觀。
* **深淺色自定義變數系統 (CSS Variables)**：
  * **暗色模式 (Dark)**：深邃星空藍底色 (`#0b0f19`)、深灰藍卡片 (`#1c273e`)、高可讀性柔白文字 (`#f3f4f6`)、微光邊框與毛玻璃導航。
  * **淺色模式 (Light)**：清爽現代 Slate-50 底色 (`#f8fafc`)、純白卡片 (`#ffffff`)、高對比深藍灰文字 (`#0f172a` / `#475569`)、細緻陰影與明亮漸層。
* **手動切換與記憶持久化**：
  * 網頁頂部新增「色彩模式切換按鈕」(`themeToggleBtn`)，支援三段循環切換：`系統預設 (Auto)` ➔ `淺色模式 (Light)` ➔ `暗色模式 (Dark)`。
  * 透過 `localStorage` 記憶使用者偏好，並透過 `matchMedia.addEventListener(change)` 實現系統主題變更時之即時響應。

---

## 🍽️ 三、純韓式藍絲帶名店與同區統籌 5 日行程架構 (最新調整版)

全行程落實 **「取消夜市、日間西門市場文創統整、純道地經典美饌、不刻意標註精確鐘點僅標示【早上 / 下午 / 晚上】」**：

| 天數 | 區域主題 | 每日精選景點 (同區統籌) | 每日午晚餐 (名店精確替換) | 晚間休閒 |
|:---:|---|---|---|---|
| **D1 (週三)** | **抵達與生活採買** | 金海機場 (BX794 17:05抵達) ➔ 機場巴士直達東大邱 ➔ Eldis Regent Hotel 入住 (青羅丘站) | **第一天晚餐不吃**<br>前往【LOTTE 超市 南山店 (롯데슈퍼 남산점)】採買水果、飲品與零食補給 | 整理行李，飯店充分放鬆休息 |
| **D2 (週四)** | **中區文化與現代百貨** | 飯店門口【青蘿之丘 ➔ 3.1運動路 ➔ 桂山聖堂 ➔ 藥令市足湯】➔ 【The Hyundai Daegu 現代百貨 (9F空中花園取景) & 咖啡名家 桂山店】 | **午餐**：【巨松燉排骨 (거송갈비찜 本店)】11:00 一開門排隊入座<br>**晚餐**：【泰山餃子 (태산만두 本店)】50年手工炸煎餃與辣拌餃子 | 東城路商圈流行街區夜間散步購物，早回飯店休息 |
| **D3 (週五)** | **湖畔休閒與音樂壁畫** | 【壽城池】(地鐵3號線16分，2公里環湖棧道漫步 & 藍絲帶【咖啡味稍微懂點的男人】) ➔ 【金光石再次繪畫路】(民謠壁畫街) | **午餐**：【萬壽炸雞 壽城池本店 (만수통닭 수성못본점)】1970年傳奇辣椒醬油炸雞<br>**晚餐**：【Wanggeomi 王蜘蛛食堂 (왕거미식당)】藍絲帶生牛肉 (뭉티기) & 炭烤牛筋 | 市中心悠閒夜風漫步，返回飯店放鬆 |
| **D4 (週六)** | **日間西門市場與文創雙星** | 【日間西門市場】深度巡禮 ➔ 【大邱藝術發電所 & 壽昌青春曼遜】(同區文創雙星) ➔ 【香村文化館】(1000₩復古學生服) ➔ 【慶尚監營公園】(週六朝鮮衛兵交接) | **早午餐**：西門市場內【美城堂薄餃子 本店 (미성당납작만두)】、烤肉串、五花肉飯捲與各式創意甜品<br>**晚餐**：【格利佛烤腸 東城路店 (걸리버막창 동성로점)】在地第一炭烤豬大腸 | 東城路商圈流行漫步、採買伴手禮，回飯店整理行李 |
| **D5 (週日)** | **傳奇早餐與返程** | 【三頌麵包 總店】(麻藥玉米麵包伴手禮) ➔ 飯店對面【青蘿丘晨光漫步】➔ 退房 ➔ 機場巴士直達金海 (70分) ➔ BX791 返台 | **早餐**：【8號食堂 本店 (8번식당 본점)】藍絲帶豬肉湯飯與厚切白切肉 (수육)<br>**下午**：金海機場免稅店 | 15:45 平安抵達桃園機場 T2 |

---

## 💻 四、已更新與推送之 GitHub 狀態

* [`index.html`](file:///home/vicabon/workspace/agy/Daegu_202609/index.html)：全面更新 5 日行程時間軸與時段表示（僅標示早上/下午/晚上），取消夜間西門夜市，整合日間西門市場與大邱藝術發電所、壽昌青春曼遜；完整落實 LOTTE超市南山店採買、巨松燉排骨開門排隊、泰山餃子、萬壽炸雞、格利佛烤腸、8號食堂本店、王蜘蛛食堂與美城堂薄餃子等全數美饌名單。
* [`PROMPT.md`](file:///home/vicabon/workspace/agy/Daegu_202609/PROMPT.md)：完整收錄全階段 Prompts、研究報告、同區統籌邏輯、純韓式藍絲帶名店與色彩模式設計。
