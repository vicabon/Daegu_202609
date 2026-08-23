# 2026 大邱旅遊研究與 7 大 AI 景點評鑑統整紀錄 (PROMPT.md)

本文件完整記錄 2026 年大邱自由行（入住 **Eldis Regent Hotel 伊爾迪斯麗晶飯店**）在各大 AI 模型上的研究 Prompt、7 大 AI 共享研究連結、跨平台綜合評鑑數據、景點深度研究分析（三星創造校區、七星市場、壽昌青春曼遜、藝術發電所）與每日行程短途化融合成果。

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

### 4. 每日行程規劃融入與客製化重構 Prompt (2 & 3)
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

---

## 🔍 二、候選景點深度研究評估報告

### 1. 【研究 1】大邱三星創造校區 (대구삼성창조캠퍼스 / Daegu Samsung Creative Economy Campus)
* **地理位置**：大邱北區浸山洞 (距飯店約 2.8 km，公車 349/706 直達約 18 分鐘 / 計程車 8 分鐘)。
* **門票費用**：**完全免費 (0元)**。
* **歷史與文化價值**：
  * **三星集團發源聖地**：1938 年創辦人李秉喆在大邱成立「三星商會」，經營乾魚與水果出口，此處為 1954 年三星設立第一座現代化工廠「第一毛織」之舊址。
  * **建築特色**：完整保留並復原了 1938 年的三星商會舊建築紀念館、李秉喆故居展示館、1950 年代復古英倫紅磚廠房與巨大煙囪。
  * **文創與休閒氛圍**：綠意盎然的中央草坪公園，進駐眾多文創小店、烘焙咖啡廳與大邱歌劇院附屬空間。
* **評估結論**：⭐⭐⭐⭐½ **極具歷史深度、攝影價值高、免門票且車程不到 20 分鐘，強烈推薦排入 Day 3！**

### 2. 【研究 2】七星綜合市場 & 七星夜市 (칠성종합시장 & 칠성야시장)
* **地理位置**：大邱北區七星洞 (緊鄰地鐵 1 號線「七星市場站」，從半月堂/中央路搭乘**僅 2~3 站，4~6 分鐘直達！**)。
* **門票費用**：**完全免費 (0元)**。
* **在地市井與美食亮點**：
  * **大邱第二大傳統市場**：相較西門市場，七星市場更少觀光客、更具道地市井生活煙火氣，以生鮮水產、烤鰻魚一條街聞名。
  * **白鍾元推薦名店**：市場內藏有獲白鍾元《三大天王》盛讚的「單骨食堂 (단골식당) 炭火辣醬烤豬肉」。
  * **七星夜市 (별별야시장)**：設於新川河畔，緊鄰七星市場站 4 號出口。主打河畔露天餐桌、浪漫燈光、街頭音樂表演 (Busking) 與豐富排檔美食。
* **評估結論**：⭐⭐⭐⭐½ **捷運 4 分鐘極速直達、市井煙火氣極濃、白鍾元炭火烤肉與河畔星光夜市超吸睛，強烈推薦排入 Day 4！**

---

## 🗺️ 三、全新短途化 5 日行程架構 (零長途拉車)

```text
Day 1 (週三) | 抵達大邱 ➔ 飯店 Check-in ➔ 8號食堂豬肉湯飯 (步行8分) ➔ 西門夜市散步初訪 (步行6分)
Day 2 (週四) | 飯店門口近代胡同群 (青蘿之丘/桂山聖堂/藥令市足湯 步行1~5分) ➔ 東仁洞燉排骨 ➔ 【指定必訪】大邱藝術發電所 & 壽昌青春曼遜 (地鐵4分) ➔ 東城路商圈 & 現代百貨9F空中花園 (淚之女王取景) ➔ 咖啡名家
Day 3 (週五) | 【研究入選】三星創造校區 (三星商會發源地/紅磚園區 18分) ➔ 12 Kitchen 雙藍絲帶頂級饗宴 ➔ 壽城池畔漫步 & 藍絲帶咖啡 (地鐵16分) ➔ 金光石民謠壁畫街 (地鐵6分) ➔ 王蜘蛛食堂生牛肉 Mungtigi
Day 4 (週六) | 香村文化館 (1000₩換穿復古學生服) ➔ 慶尚監營公園 朝鮮衛兵交接儀式 ➔ 釜山安面屋平壤冷麵 ➔ 【研究入選】七星綜合市場 (單骨食堂炭火烤肉 地鐵4分) ➔ 安吉郎烤腸街 (地鐵15分) ➔ 七星星光夜市 (新川河畔夜景)
Day 5 (週日) | 三頌麵包總店 (麻藥玉米麵包 步行8分) ➔ 青蘿丘晨光巡禮 ➔ 退房前往東大邱 (15分) ➔ 機場巴士直達金海 (70分) ➔ BX791 (14:15) 賦歸台北
```

---

## 🚫 四、依需求移除之景點清單

1. ❌ **前山展望台 (Apsan Observatory) 纜車夜景**：依需求移除，省去晚間搭公車上山時間。
2. ❌ **大邱美術館 (Daegu Art Museum)**：依需求移除，改訪市中心 4 分鐘直達之當代藝術雙星。
3. ❌ **E-World 主題樂園 & 83塔 景觀台**：門票 4.9 萬韓元昂貴，依需求正式移除。
4. ❌ **大邱樹木園 (대구수목원)**：依需求移除，替換為市區近距之三星創造校區文化園區。
5. ❌ **The ARC (디아크문화관)**：依需求移除，替換為地鐵 4 分鐘直達之七星綜合市場與新川河畔夜市。
6. ❌ **峨洋鐵道橋 (아양기찻길)**：依需求移除，精簡夜間動線。

---

## 💻 五、代碼更新與 GitHub 同步

* [`index.html`](file:///home/vicabon/workspace/agy/Daegu_202609/index.html)：每日行程（Tab 1）與 7 大 AI 景點庫（Tab 5）全面重構。
* [`PROMPT.md`](file:///home/vicabon/workspace/agy/Daegu_202609/PROMPT.md)：完整記錄 Prompt、研究成果、行程變更歷程。
