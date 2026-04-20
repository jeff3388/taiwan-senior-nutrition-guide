# taiwan-senior-nutrition-guide

> 台灣高齡者全面營養指南：微量營養素、咀嚼吞嚥、社區飲食支持

## 與 taiwan-sarcopenia-prevention-guide 的分工

| 資料庫 | 聚焦範圍 |
|--------|---------|
| [`taiwan-sarcopenia-prevention-guide`](../taiwan-sarcopenia-prevention-guide/) | 肌少症診斷、蛋白質需求、阻力運動處方 |
| **本資料庫** | 高齡者**全面微量營養素**、**咀嚼吞嚥困難**、**社區飲食支持系統** |

本資料庫不重複肌少症或蛋白質建議的內容，專注於高齡者飲食的其他關鍵面向。

| 檔案 | 說明 |
|------|------|
| [`data/micronutrient-deficiencies.json`](data/micronutrient-deficiencies.json) | 台灣老年人常見微量營養素缺乏（鈣、維生素 D、B12、鋅）|
| [`data/dysphagia-diet-guide.json`](data/dysphagia-diet-guide.json) | 吞嚥困難（失能老人）的飲食質地調整與營養維持 |
| [`data/community-nutrition-resources.json`](data/community-nutrition-resources.json) | 台灣社區老人飲食支持（長照 2.0、關懷據點、送餐服務）|
| [`data/supplement-evidence-elderly.json`](data/supplement-evidence-elderly.json) | 高齡者補充劑使用建議（有 RCT 依據）|

## 台灣老年人常見微量營養素缺乏

| 營養素 | 台灣老年人缺乏率 | 主要後果 |
|--------|--------------|--------|
| 維生素 D | **60–70%**（< 20 ng/mL）| 骨質疏鬆、肌少症、免疫下降 |
| 鈣質 | **超過 50%** 未達 DRI | 骨密度下降、骨折風險 |
| 維生素 B12 | **15–30%**（> 65 歲）| 神經病變、大球性貧血、認知退化 |
| 鋅 | **20–40%** 不足 | 傷口癒合慢、免疫功能下降 |
| 葉酸 | **20–35%** 不足 | 大球性貧血、心血管風險 |

## 維生素 D 的台灣困境

台灣位於亞熱帶（北緯 22–25°），日照充足，但老年人維生素 D 缺乏率反而偏高：

1. 過度防曬（遮陽傘、袖套、高 SPF 防曬乳）
2. 戶外活動少（城市化、高溫避免出門）
3. 皮膚老化使維生素 D 合成效率降低約 75%（70 歲 vs 20 歲）
4. 飲食中維生素 D 食物來源有限（台灣傳統飲食低維生素 D）

**建議**：每日戶外日曬 15–20 分鐘（上午 10 點前或下午 3 點後），或補充維生素 D3 1,000–2,000 IU/day。

## 吞嚥困難的台灣現況

台灣 65 歲以上老年人吞嚥困難（dysphagia）盛行率約 **15–22%**；長照機構老年人可達 **50%**。吞嚥困難導致：
- 飲食攝取量下降 → 蛋白質與熱量不足
- 吸入性肺炎（最嚴重後果，台灣老年人第 3–5 大死因）
- 脫水（害怕嗆咳而減少飲水）

## 資料來源

- **台灣 DRI 第八版（2023）**：衛福部國民健康署，70 歲以上各營養素建議量
- **維生素 D 缺乏率**：Pan WH et al. (2013) Asia Pac J Clin Nutr. PMID: 23736897
- **吞嚥困難指引**：台灣老年醫學暨老年學學會（2021）吞嚥困難照護指引
- **長照 2.0**：衛福部長期照顧十年計畫 2.0（2017–2026）
- **Holick MF (2011) PMID: 22206119**：維生素 D 缺乏系統性回顧

## License

MIT © taiwan-senior-nutrition-guide contributors
