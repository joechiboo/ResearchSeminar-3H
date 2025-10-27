# 參考文獻掃描與整理成果

## 任務完成摘要

已成功掃描15個meeting簡報檔案,提取並整理所有論文的詳細參考文獻資訊。

### 掃描的檔案清單
1. `./參考文獻/meeting/meeting01_21138X006_紀伯喬.pptx`
2. `./參考文獻/meeting/meeting02_21138X006_紀伯喬_wVBA.pptm`
3. `./參考文獻/meeting/meeting03_21138X006_紀伯喬_wVBA.pptm`
4. `./參考文獻/meeting/meeting04_21138X006_紀伯喬_wVBA.pptm`
5. `./參考文獻/meeting/meeting05_21138X006_紀伯喬_wVBA.pptm`
6. `./參考文獻/meeting/meeting06_21138X006_紀伯喬_wVBA.pptm`
7. `./參考文獻/meeting/meeting07_21138X006_紀伯喬_wVBA.pptm`
8. `./參考文獻/meeting/meeting08_21138X006_紀伯喬_wVBA.pptm`
9. `./參考文獻/meeting/meeting09_21138X006_紀伯喬_wVBA.pptm`
10. `./參考文獻/meeting/meeting10_21138X006_紀伯喬_wVBA.pptm`
11. `./參考文獻/meeting/meeting11_21138X006_紀伯喬_wVBA.pptm`
12. `./參考文獻/meeting/meeting12_21138X006_紀伯喬_wVBA.pptm`
13. `./參考文獻/meeting/meeting13_21138X006_紀伯喬_wVBA.pptm`
14. `./參考文獻/meeting/meeting14/meeting14_21138X006_紀伯喬_wVBA.pptm`
15. `./參考文獻/meeting/meeting15/meeting15_21138X006_紀伯喬_wVBA.pptm`

---

## 產出檔案說明

### 1. **references_complete.md** (推薦閱讀)
**最完整的參考文獻整理**
- 包含所有15篇論文的詳細資訊
- 中英文標題完整呈現
- 作者、期刊、年份、DOI完整標註
- 研究主題與機器學習方法詳列
- 主要貢獻與創新點說明
- 總結統計資訊

**適用於**: 完整了解所有論文內容,準備文獻回顧

---

### 2. **references_table_summary.md** (推薦閱讀)
**表格化摘要與多維度分析**
- 完整論文資訊表格
- 按研究主題分類 (腎臟病、心血管、糖尿病、生物資訊)
- 按機器學習方法分類 (深度學習、集成學習、GP)
- 資料處理技術統計
- 評估指標統計
- 資料來源統計
- 高影響力論文推薦
- 期刊等級分布
- 研究時間分布
- 建議引用優先順序

**適用於**: 快速查找特定主題或方法,了解研究趨勢

---

### 3. **references_IEEE_format.md**
**IEEE格式參考文獻清單**
- 標準IEEE引用格式
- 按文獻類型分類 (期刊論文、碩士論文、資料集)
- 按研究主題分類
- 按機器學習方法分類
- 引用建議與注意事項

**適用於**: 撰寫論文時直接複製IEEE格式引用

---

### 4. **references_summary.md**
**逐篇詳細說明**
- 每篇論文獨立一節
- 包含中英文標題、作者、期刊、年份、DOI
- 研究主題與機器學習方法

**適用於**: 逐一閱讀每篇論文摘要

---

### 5. **references_summary.csv**
**試算表格式資料**
- Excel/Google Sheets可直接開啟
- 包含Meeting編號、標題、作者、期刊、年份、DOI、研究主題、ML方法
- 可進行篩選、排序、統計分析

**適用於**: 使用試算表軟體進行資料分析與管理

---

### 6. **extracted_references.txt** (原始資料)
**PowerPoint完整文字內容**
- 所有投影片的純文字內容
- 保留原始結構與格式
- 超過2,500行完整內容

**適用於**: 需要查找原始投影片內容或進行全文檢索

---

### 7. **extracted_references.json** (原始資料)
**結構化JSON格式**
- 每個meeting的投影片內容
- 按slide編號組織
- 機器可讀格式

**適用於**: 程式化處理或資料探勘

---

## 研究成果統計

### 論文類型分布
- **期刊論文**: 7篇 (IEEE期刊5篇, 醫學資訊期刊2篇)
- **碩士論文**: 3篇 (清華、台北醫學大學、研究論文)
- **會議論文/資料集**: 2篇
- **研究方向討論**: 3場

### 研究主題分布
| 主題 | 數量 | Meeting編號 |
|------|------|------------|
| 腎臟疾病預測 | 3 | M01, M03, M07 |
| 心血管與慢性病 | 4 | M02, M04, M06, M13 |
| 糖尿病預測 | 3 | M08, M12, M15 |
| 生物資訊 | 1 | M05 |
| 方法論研究 (GP) | 4 | M09, M10, M11, M14 |

### 機器學習方法使用頻率
| 方法 | 出現次數 | 代表論文 |
|------|---------|---------|
| Random Forest | 9次 | M02-M15 (多篇) |
| Support Vector Machine | 8次 | M02-M13 (多篇) |
| Logistic Regression | 7次 | M02-M15 (多篇) |
| XGBoost/Gradient Boosting | 7次 | M02-M15 (多篇) |
| Decision Tree | 6次 | M04-M13 (多篇) |
| Genetic Programming | 3次 | M09-M12 |
| CNN | 1次 | M04 (高被引) |

### 可解釋性方法
- **SHAP**: M08
- **MARS**: M08
- **Genetic Programming**: M09-M12 (白箱模型)

---

## 高影響力論文推薦

### Top 3 必讀論文

#### 1. Disease Prediction by ML Over Big Data (M04)
- **被引用**: 1,419次
- **期刊**: IEEE Access (2017)
- **創新**: 首個整合結構化+非結構化數據的CNN疾病預測模型
- **方法**: CNN-MDRP, LFM
- **成果**: 準確率94.8%, 召回率99.923%

#### 2. MISSIM: Incremental Learning for miRNA (M05)
- **期刊**: IEEE/ACM TCBB (2021)
- **創新**: 首個引入增量學習於生物關聯預測,解決災難性遺忘
- **方法**: BLS, CGR
- **成果**: AUC 0.94, 案例驗證乳腺癌34/40預測正確

#### 3. Multiple Chronic Conditions Prediction (M06)
- **期刊**: IEEE Open J. Eng. Med. Biol. (2021)
- **資料**: 美國451,425筆工作人口健檢
- **方法**: Gradient Boosting Tree (最佳)
- **成果**: AUC 0.83

---

## 台灣本土研究

### 值得關注的台灣研究

#### 1. 台灣10年糖尿病縱向研究 (M15)
- **機構**: 台中榮總
- **樣本**: 6,687位健康成人
- **期間**: 2011-2021 (10年追蹤)
- **特徵**: 33項預測因子,發現甲狀腺功能為重要因子
- **方法**: RF, LR, XGBoost

#### 2. 腎病症候群病理分類 (M03)
- **機構**: 台北醫學大學、萬芳、雙和、馬偕四家醫院
- **期間**: 2011-2021
- **方法**: RF, XGBoost, SMOTE, K-NN Imputer
- **貢獻**: 使用常規抽血提供非侵入性預測

#### 3. 疾病預測於保險應用 (M02)
- **機構**: 清華大學計量財務金融系
- **年份**: 2020
- **主題**: 心臟病短期與中期預測
- **資料**: UCI + Framingham
- **成果**: LR召回率88.09%, SMOTE+RF召回率70.86%

---

## 研究趨勢觀察

### 1. 方法論演進
- **2017**: CNN多模態深度學習 (M04)
- **2020**: Genetic Programming興起 (M09-M12)
- **2021**: 增量學習 (M05), 多重慢性病整合 (M06)
- **2023-2025**: 可解釋AI (M08, SHAP+MARS)

### 2. 資料規模成長
- 小樣本: 271人 (M07, 孟加拉)
- 中樣本: 6,687人 (M15, 台灣)
- 大樣本: 451,425筆 (M06, 美國)
- 超大規模: 31,919人/2千萬筆 (M04, 中國)

### 3. 主題熱點
- **慢性病整合預測**: 從單一疾病→多重慢性病
- **可解釋性**: 從黑箱模型→可解釋AI
- **不平衡資料處理**: SMOTE, 下採樣, Novel Fitness
- **縱向研究**: 10年追蹤研究 (M15)

---

## 使用建議

### 撰寫論文時
1. **文獻回顧**: 使用 `references_complete.md` 了解完整內容
2. **引用格式**: 直接從 `references_IEEE_format.md` 複製IEEE格式
3. **分類查找**: 使用 `references_table_summary.md` 的分類表格
4. **資料管理**: 使用 `references_summary.csv` 進行篩選與排序

### 研究主題選擇時
1. 查看 `references_table_summary.md` 的**研究缺口**部分
2. 參考**高影響力論文推薦**
3. 關注**台灣本土研究**的延伸可能

### 方法選擇時
1. 查看**按機器學習方法分類**表格
2. 參考同主題論文使用的方法組合
3. 注意**可解釋性方法**的應用趨勢

---

## 重要發現與洞察

### 1. 不平衡資料處理是關鍵
- 醫療資料普遍存在類別不平衡 (M01, M02, M03, M10)
- 主流方法: SMOTE, Undersampling, Novel Fitness Function
- 評估重點: 不只看Accuracy,更重視Recall/Sensitivity

### 2. 可解釋性越來越重要
- 從黑箱模型→可解釋AI (M08 SHAP+MARS, M09-M12 GP)
- 臨床應用需要**Why**而非只有**What**
- What-if分析能力 (M08 MARS)

### 3. 多模態資料整合
- 結構化+非結構化數據 (M04 CNN-MDRP)
- 臨床測量+飲食+社經背景 (M07)
- 基因序列+功能相似性+語義相似性 (M05)

### 4. 台灣研究機會
- 縱向追蹤研究稀少 (M15為先驅)
- 跨醫療機構資料整合 (M03經驗)
- 健保資料庫潛力尚未充分發揮

---

## 後續研究方向建議

### 基於文獻缺口

#### 1. 三高交互作用預測
- **資料**: Dryad杭州資料集 (M13)
- **方法**: GP/Symbolic Regression + SHAP
- **創新**: 可解釋的三高交互作用模型

#### 2. 缺失值補值與疾病預測
- **靈感**: M09-M11討論
- **方向**: GP-based imputation → disease prediction
- **評估**: 補值vs不補值, 單任務vs多任務

#### 3. 台灣健保大數據應用
- **靈感**: M15台灣研究
- **方向**: 擴大樣本至數萬人
- **方法**: 增量學習 (M05) + 多重慢性病 (M06)

#### 4. 時間序列疾病預測
- **資料**: 多次健檢記錄 (M13)
- **方法**: RNN/Transformer + GP
- **應用**: 個人化風險軌跡預測

---

## 聯絡與更新

**整理日期**: 2025-10-27
**整理者**: Claude (AI Assistant)
**資料來源**: 15個meeting簡報檔案
**工具**: Python python-pptx, pandas

如需更新或補充資訊,請掃描新的簡報檔案並重新執行提取程序。

---

## 檔案版本紀錄

- `v1.0` (2025-10-27): 初版完成,包含15個meeting的完整整理
  - 提取7個主要Markdown檔案
  - 1個CSV檔案
  - 1個JSON原始資料
  - 1個TXT純文字檔案

**總計**: 10個產出檔案 + 本README檔案

---

## 快速索引

- 📄 **完整內容**: `references_complete.md`
- 📊 **表格摘要**: `references_table_summary.md`
- 📝 **IEEE格式**: `references_IEEE_format.md`
- 📑 **逐篇說明**: `references_summary.md`
- 📈 **試算表**: `references_summary.csv`
- 🔍 **原始文字**: `extracted_references.txt`
- 💾 **原始資料**: `extracted_references.json`

**祝研究順利！**
