# 參考文獻表格摘要

## 完整論文資訊表格

| Meeting | 論文標題 (中/英) | 作者/機構 | 期刊/來源 | 年份 | DOI | 研究主題 | ML方法 |
|---------|-----------------|----------|----------|------|-----|---------|--------|
| **M01** | 腎功能預測研究 (NHANES 2005-2016) | 研究者 | 碩士論文研究 | 2024 | - | 慢性腎臟病預測 | CART, 下採樣 |
| **M02** | 疾病預測於保險上之應用 / Application of Disease Prediction in Insurance | 清華大學計量財務金融系 | 碩士論文 | 2020 | - | 心臟病預測 | RF, XGBoost, LR, SVM, SMOTE |
| **M03** | 運用機器學習預測腎病症候群病理分類 / Predict Pathologic Classification in Nephrotic Syndrome | 台北醫學大學AI醫療碩專班 | 碩士論文 | 2023 | - | 腎病症候群分類 | RF, XGBoost, LR, SVM, K-NN, SMOTE |
| **M04** | Disease Prediction by ML Over Big Data From Healthcare Communities | Chen M, Hwang K, et al. | IEEE Access | 2017 | 10.1109/ACCESS.2017.2694446 | 慢性病預測 (腦梗塞) | CNN-MDRP, LFM, NB, KNN, DT |
| **M05** | MISSIM: Incremental Learning for miRNA-Disease Association | Zheng K, You ZH, et al. | IEEE/ACM TCBB Vol.18(5) | 2021 | 10.1109/TCBB.2020.3013837 | miRNA-疾病關聯 | BLS, CGR, SVM |
| **M06** | Prediction for Risk of Multiple Chronic Conditions | Yang J, Ju X, et al. | IEEE Open J. Eng. Med. Biol. Vol.2 | 2021 | 10.1109/OJEMB.2021.3117872 | 多重慢性疾病 | GBT, RF, DT, LR, SVM, K-NN, NB |
| **M07** | Blood Uric Acid Prediction With Machine Learning | Sampa MB, Hossain MN, et al. | JMIR Med Inform 8(10) | 2020 | 10.2196/18331 | 尿酸預測 | BDT, DF(RF), NN, BLR, LR |
| **M08** | Explainable ML Models with Shapley Values for Diabetes Prediction | Pang K | Healthcare Analytics Vol.7 | 2025 | 10.1016/j.health.2025.100390 | 糖尿病預測 | LR, DT, RF, SVM, KNN, GBM, MARS+SHAP |
| **M09** | GP在疾病預測與檢驗數值建模應用 | 研究方向探討 | - | 2020 | - | CKD, 糖尿病, 補值 | GP vs SVM, RF, LR |
| **M10** | Novel Fitness Function in GP for Medical Data Classification | Bennett Univ., India | J. Biomed. Inform. Vol.112 | 2020 | 10.1016/j.jbi.2020.103623 | 不平衡分類 | GP (Novel Fitness), SVM |
| **M11** | GP醫療資料分類應用討論 | 論文討論 | - | - | - | 方法論探討 | GP, SVM |
| **M12** | Analysis of GP on Blood Glucose Level Prediction Challenge 2020 | Joedicke D, Garnica O, et al. | Conference Paper | 2020 | - | 血糖預測 | GP, GP-OS, GE, MOGE, RF, LR, ARIMA |
| **M13** | Serum Uric Acid with CVD Risk Factors (China Dataset) | 杭州社區調查 | Dryad Dataset | 2023 | 10.5061/dryad.z08kprrk1 | 三高與尿酸關聯 | LR, RF, SVM, KNN, XGBoost |
| **M14** | 三高與慢性病文獻回顧 | 研究規劃 | - | 2020 | - | 三高預測 | RF, SVM, NN |
| **M15** | ML to Predict Type 2 Diabetes in Taiwan (10-Year Study) | 台中榮總 | - | 2011-2021 | - | 第二型糖尿病 | RF, LR, XGBoost |

---

## 按研究主題分類

### 腎臟疾病 (Kidney Disease) - 3篇
- **M01**: 慢性腎臟病預測 (NHANES, CART)
- **M03**: 腎病症候群病理分類 (台北醫學大學, RF/XGBoost)
- **M07**: 血中尿酸預測 (孟加拉研究, BDT)

### 心血管與慢性病 (Cardiovascular & Chronic Diseases) - 4篇
- **M02**: 心臟病預測於保險應用 (清華大學, RF/XGBoost)
- **M04**: 大數據疾病預測 (華中科技大學, CNN-MDRP, 1419次引用)
- **M06**: 美國工作人口多重慢性病 (IEEE, GBT)
- **M13**: 中國東南地區尿酸與心血管風險 (Dryad公開資料集)

### 糖尿病 (Diabetes) - 3篇
- **M08**: 可解釋AI糖尿病預測 (McMaster Univ., MARS+SHAP)
- **M12**: 血糖預測挑戰賽 (Ohio2020 dataset, GP)
- **M15**: 台灣10年糖尿病縱向研究 (台中榮總)

### 生物資訊 (Bioinformatics) - 1篇
- **M05**: miRNA-疾病關聯增量學習 (IEEE/ACM TCBB, BLS)

### 方法論研究 (Methodology) - 4篇
- **M09**: GP方法論探討
- **M10**: GP不平衡分類新fitness function (JBI)
- **M11**: GP方法討論
- **M14**: 三高預測文獻回顧

---

## 按機器學習方法分類

### 深度學習 (Deep Learning)
| Method | Papers | Applications |
|--------|--------|--------------|
| CNN | M04 | 多模態疾病預測 (CNN-MDRP) |
| Neural Network | M07, M08, M14 | 尿酸預測, 糖尿病預測 |
| BLS | M05 | miRNA增量學習 |

### 集成學習 (Ensemble Learning)
| Method | Frequency | Papers |
|--------|-----------|--------|
| Random Forest | 9次 | M02, M03, M06, M07, M08, M09, M12, M13, M15 |
| XGBoost/Gradient Boosting | 7次 | M02, M03, M06, M07, M08, M13, M15 |
| Decision Tree | 6次 | M04, M06, M07, M08, M09, M13 |

### 傳統ML (Traditional ML)
| Method | Frequency | Papers |
|--------|-----------|--------|
| Logistic Regression | 7次 | M02, M03, M06, M08, M12, M13, M15 |
| SVM | 8次 | M02, M03, M05, M06, M08, M09, M10, M13 |
| K-NN | 4次 | M03, M06, M08, M13 |
| Naive Bayes | 3次 | M04, M06, M08 |

### Genetic Programming (GP)
| Type | Papers | Application |
|------|--------|-------------|
| Standard GP | M09, M10, M12 | 分類, 回歸, 血糖預測 |
| GP-OS | M12 | 子代選擇血糖預測 |
| GE/MOGE | M12 | 文法演化 |
| Novel Fitness | M10 | 不平衡分類 |

### 可解釋性方法 (Explainable AI)
| Method | Papers | Description |
|--------|--------|-------------|
| SHAP | M08 | Shapley values特徵重要性 |
| MARS | M08 | 可解釋回歸模型 |
| GP | M09-M12 | 白箱符號回歸 |

---

## 資料處理技術統計

### 不平衡資料處理
| Technique | Papers | Description |
|-----------|--------|-------------|
| SMOTE | M02, M03 | 合成少數類過採樣 |
| Undersampling | M01, M06 | 下採樣 |
| Novel Fitness | M10 | GP改良適應函數 |

### 缺失值處理
| Technique | Papers | Description |
|-----------|--------|-------------|
| K-NN Imputer | M03 | K近鄰補值 |
| LFM | M04 | 潛在因子模型 |
| Linear Interpolation | M12 | 線性插值 |

---

## 評估指標統計

### 常用指標
- **Accuracy**: 12篇
- **AUC/ROC**: 10篇
- **Sensitivity/Recall**: 8篇
- **Precision**: 6篇
- **F1-Score**: 6篇
- **RMSE/MAE**: 3篇 (回歸任務)

### 特殊指標
- **Clarke Error Grid**: M12 (血糖預測臨床安全性)
- **AUPR**: M05 (不平衡資料)

---

## 資料來源統計

### 國際公開資料集
| Dataset | Papers | Size | Description |
|---------|--------|------|-------------|
| UCI Repository | M09, M10 | 多個 | CKD, WDBC, BUPA, Fertility |
| NHANES | M01 | 38,447筆 | 美國健康營養調查 |
| Framingham | M02 | 4,240筆 | 經典心血管研究 |
| Cleveland Clinic | M02 | 303筆 | 心臟病資料 |
| Ohio2020 | M12 | 6位患者 | 血糖監測 |
| HMDD v3.0 | M05 | 32,226條 | miRNA-疾病關聯 |
| CDC | M08 | 70,692筆 | 美國疾病管制中心 |
| Dryad | M13 | 25,744筆 | 杭州社區調查 |

### 台灣本土資料
| Source | Papers | Size | Period |
|--------|--------|------|--------|
| 台中榮總 | M15 | 6,687人 | 2011-2021 (10年) |
| 北醫/萬芳/雙和/馬偕 | M03 | - | 2011-2021 |

### 國際醫院EHR
| Source | Papers | Size | Period |
|--------|--------|------|--------|
| 中國中部醫院 | M04 | 31,919人, 2千萬筆 | 2013-2015 |
| 孟加拉Grameen Bank | M07 | 271人 | 單次調查 |

---

## 高影響力論文 (被引用/重要性)

### 高被引論文
1. **M04**: Chen et al. (2017) - **1,419次引用** - CNN-MDRP多模態疾病預測
2. **M05**: Zheng et al. (2021) - IEEE/ACM TCBB - miRNA增量學習

### 方法創新論文
1. **M04**: 首個整合結構化+非結構化數據的深度學習模型
2. **M05**: 首個引入增量學習於生物關聯預測
3. **M10**: 新穎GP fitness function處理不平衡分類
4. **M08**: MARS+SHAP提供What-if分析

### 台灣重要研究
1. **M15**: 首個台灣10年糖尿病縱向ML研究
2. **M03**: 跨四家醫院腎病症候群預測
3. **M02**: 保險應用心臟病預測

---

## 期刊等級分布

### IEEE系列 (4篇)
- IEEE Access (M04)
- IEEE/ACM TCBB (M05)
- IEEE Open J. Eng. Med. Biol. (M06)

### 醫學資訊期刊 (3篇)
- JMIR Med Inform (M07)
- Healthcare Analytics (M08)
- J. Biomed. Inform. (M10)

### 碩士論文 (3篇)
- 清華大學 (M02)
- 台北醫學大學 (M03)
- 研究論文 (M01)

### 會議論文與資料集 (2篇)
- Conference Paper (M12)
- Dryad Dataset (M13)

---

## 研究時間分布

| Year | Count | Papers |
|------|-------|--------|
| 2017 | 1 | M04 |
| 2020 | 5 | M02, M07, M09, M10, M12 |
| 2021 | 3 | M05, M06, M15 (2011-2021) |
| 2023 | 2 | M03, M13 |
| 2024 | 1 | M01 |
| 2025 | 1 | M08 |

**研究集中期**: 2020-2021年 (8篇)
**最新研究**: 2023-2025年 (4篇)

---

## 建議引用優先順序

### 必讀論文 (高影響力)
1. M04 - Chen et al. (2017) - CNN多模態疾病預測 [1,419引用]
2. M05 - Zheng et al. (2021) - miRNA增量學習 [IEEE/ACM]
3. M06 - Yang et al. (2021) - 多重慢性病預測 [IEEE]

### 方法論重點
4. M10 - Novel GP Fitness Function [JBI 2020]
5. M08 - MARS + SHAP可解釋AI [2025]
6. M12 - GP血糖預測挑戰賽 [2020]

### 台灣本土研究
7. M15 - 台灣10年糖尿病研究 [2021]
8. M03 - 腎病症候群分類 [北醫 2023]
9. M02 - 保險疾病預測 [清華 2020]

### 特定主題
- **腎臟病**: M01, M03, M07
- **糖尿病**: M08, M12, M15
- **心血管**: M02, M04, M13
- **可解釋AI**: M08, M09-M12
- **不平衡資料**: M01, M02, M03, M10
