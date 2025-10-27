# 研究專題討論 - 參考文獻完整整理

## Meeting01
**類型:** 碩士論文研究 (NHANES資料分析)
**中文標題:** 腎功能預測研究 (使用NHANES 2005-2016資料)
**資料來源:** 美國National Center for Health Statistics (NCHS) - NHANES
**研究主題:** 慢性腎臟病預測與危險因子分析
**機器學習方法:** CART (Classification and Regression Tree), 決策樹, 下採樣 (Undersampling)
**主要貢獻:** 處理不平衡資料並發展高敏感度預測模型,識別尿素氮為關鍵危險因子

---

## Meeting02
**類型:** 碩士論文
**中文標題:** 疾病預測於保險上之應用:以機器學習的方法建立疾病預測模型
**英文標題:** Application of the Disease Prediction in Insurance: Disease Prediction Model by Machine Learning
**學校:** 國立清華大學計量財務金融學系
**年份:** 2020年7月 (中華民國一○九年七月)
**研究主題:** 心臟病短期與中期疾病預測
**資料集:**
- 短期: UCI Cleveland Clinic Foundation (303筆)
- 中期: Framingham Heart Study (4,240筆)
**機器學習方法:** Logistic Regression, Random Forest, XGBoost, Decision Tree, SVM, ANN, SMOTE
**主要成果:**
- 短期模型: Logistic Regression 召回率88.09%
- 中期模型: SMOTE + Random Forest 召回率70.86%

---

## Meeting03
**類型:** 碩士論文
**中文標題:** 運用機器學習和臨床醫療數據以預測腎病症候群患者之病理分類研究
**英文標題:** Using Medical Data and Machine Learning Algorithms to Predict Pathologic Classification in Patients with Nephrotic Syndrome
**學校:** 臺北醫學大學醫學院人工智慧醫療碩士在職專班
**年份:** 2023年7月 (中華民國一一二年七月)
**研究主題:** 腎病症候群病理分類預測
**資料來源:** 臺北醫學大學附設醫院、萬芳醫院、雙和醫院、馬偕醫院 (2011/01-2021/06)
**機器學習方法:** Random Forest, XGBoost, Logistic Regression, SVM, K-NN, SMOTE, K-NN Imputer
**評估指標:** Accuracy, AUC, 5-fold Cross-Validation
**主要貢獻:** 使用常規抽血檢驗項目提供非侵入性腎病症候群分型預測

---

## Meeting04
**英文標題:** Disease Prediction by Machine Learning Over Big Data From Healthcare Communities
**作者:**
- Min Chen (陳敏) - 華中科技大學教授
- Kai Hwang (黃凱) - 南加州大學教授, IEEE Life Fellow
- Lin Wang (王琳), Yixue Hao (郝奕學), Lu Wang (王路) - 華中科技大學
**期刊:** IEEE Access
**年份:** 2017
**發表日期:** Received March 23, 2017; Accepted April 5, 2017; Published April 26, 2017; Current version June 28, 2017
**DOI:** 10.1109/ACCESS.2017.2694446
**被引用次數:** 1,419次
**研究主題:** 慢性病風險預測 (腦梗塞 Cerebral Infarction)
**資料來源:** 中國中部某醫院EHR (2013-2015), 31,919位病患, 20,320,848條記錄
**機器學習方法:**
- CNN-MDRP (CNN-Based Multimodal Disease Risk Prediction)
- CNN-UDRP (CNN-Based Unimodal Disease Risk Prediction)
- Latent Factor Model (LFM) for data imputation
- Naive Bayes, KNN, Decision Tree
**主要成果:** CNN-MDRP準確率94.8%, 召回率99.923%
**創新點:** 首個同時整合結構化與非結構化醫療數據的深度學習疾病預測模型

---

## Meeting05
**英文標題:** MISSIM: An Incremental Learning-Based Model With Applications to the Prediction of miRNA-Disease Association
**作者:** Kai Zheng, Zhu-Hong You, Lei Wang, Yi-Ran Li, Ji-Ren Zhou, Hai-Tao Zeng
**期刊:** IEEE/ACM Transactions on Computational Biology and Bioinformatics
**卷期:** Volume 18, Issue 5
**頁碼:** 1733-1742
**發表日期:** 04 August 2020 (印刷版: 01 Sept.-Oct. 2021)
**DOI:** 10.1109/TCBB.2020.3013837
**出版商:** IEEE
**研究主題:** miRNA-疾病關聯預測
**資料來源:** HMDD v3.0 (32,226條miRNA-疾病關聯, 1,057個miRNA, 850種疾病)
**機器學習方法:**
- BLS (Broad Learning System)
- Chaos Game Representation (CGR) for sequence similarity
- SVM (比較用)
**評估指標:** AUC 0.9400 ± 0.0041, Accuracy 0.8685, Sensitivity 0.8871, Precision 0.8556, F1-score 0.8708
**主要貢獻:** 首次在生物關聯預測領域引入增量學習,解決災難性遺忘問題
**案例驗證:** 乳腺癌34/40, 肺癌36/40, 食道癌35/40預測miRNA被證實

---

## Meeting06
**英文標題:** Prediction for the Risk of Multiple Chronic Conditions Among Working Population in the United States With Machine Learning Models
**作者:** Jingmei Yang, Xinglong Ju, Feng Liu, Onur Asan, Timothy S. Church, Jeff O. Smith
**期刊:** IEEE Open Journal of Engineering in Medicine and Biology
**卷期:** Volume 2
**頁碼:** 291-298
**發表日期:** 06 October 2021
**Electronic ISSN:** 2644-1276
**PubMed ID:** 35402965
**DOI:** 10.1109/OJEMB.2021.3117872
**出版商:** IEEE
**研究主題:** 美國工作人口多重慢性疾病 (MCC) 風險預測
**資料來源:** Catapult Health資料庫, 2010-2017年, 451,425筆健檢資料, 301,631位參與者
**特徵數量:** 39個變數 (經篩選後15個主要特徵)
**機器學習方法:** k-NN, Decision Tree, Random Forest, Gradient Boosting Tree, Logistic Regression, SVM, Naive Bayes
**資料處理:** Undersampling (1:1比例)
**評估指標:** AUC 0.809-0.8307
**最佳模型:** Gradient Boosting Tree
**主要貢獻:** 首個針對工作年齡人口的多重慢性疾病預測工具

---

## Meeting07
**英文標題:** Blood Uric Acid Prediction With Machine Learning: Model Development and Performance Comparison
**作者:**
- Masuda Begum Sampa (PhD) - Kyushu University
- Md Nazmul Hossain (PhD) - University of Dhaka
- Md Rakibul Hoque (PhD), Rafiqul Islam (PhD)
- Fumihiko Yokota (PhD), Mariko Nishikitani (MPH, PhD)
- Ashir Ahmed (PhD) - Kyushu University
**期刊:** JMIR Med Inform
**卷期:** 2020;8(10):e18331
**DOI:** 10.2196/18331
**PMID:** 33030442
**PMCID:** 7582147
**年份:** 2020
**研究主題:** 血中尿酸值預測 (預防非傳染性疾病NCDs)
**資料來源:** 孟加拉達卡Grameen Bank大樓員工健檢 (N=271)
**特徵數量:** 17個變數 (臨床測量 + 飲食 + 社經背景)
**機器學習方法:**
- Boosted Decision Tree Regression (BDT) - 最佳
- Decision Forest Regression (Random Forest)
- Neural Network
- Bayesian Linear Regression
- Linear Regression
**平台:** Azure Machine Learning Studio
**評估指標:** RMSE = 0.03 (BDT最佳)
**資料切分:** 70% training / 30% testing (Holdout method)
**主要貢獻:** 首個孟加拉預測健檢數值的ML應用,適用於資源不足地區

---

## Meeting08
**英文標題:** A comparative study of explainable machine learning models with Shapley values for diabetes prediction
**作者:** Keona Pang - McMaster University, Faculty of Health Sciences
**期刊:** Healthcare Analytics
**卷期:** Volume 7
**發表日期:** June 2025
**DOI:** 10.1016/j.health.2025.100390
**關鍵字:** Artificial intelligence, Machine learning, Diabetes prediction, CDC data, Predictive analytics
**研究主題:** 糖尿病預測與可解釋AI (XAI)
**資料來源:** 美國CDC健康調查資料集, 70,692筆, 21個特徵
**機器學習方法:**
- Logistic Regression, Decision Tree, Random Forest
- Support Vector Machine, K-Nearest Neighbors
- Gradient Boosting Machine (GBM)
- MARS (Multivariate Adaptive Regression Splines) - 可解釋模型
**可解釋性方法:** SHAP (Shapley Additive exPlanations)
**評估結果:** 準確率65-75%
**主要貢獻:** 整合MARS模型與SHAP分析,提供What-if分析能力,提升臨床可解釋性

---

## Meeting09
**類型:** 研究方向探討
**研究主題:** Genetic Programming (GP) 在疾病預測與檢驗數值建模中的應用
**目標疾病:** CKD, 糖尿病, 異常檢驗數值補值
**比較方法:** GP vs SVM, RF, LR
**主要資料集:** CKD, BUPA, WDBC (UCI Repository)
**重點論文參考:**
- Kumar (2020) - Unbalanced Classification
- Joedicke (2020) - Blood Glucose Prediction Challenge

---

## Meeting10
**英文標題:** A novel fitness function in genetic programming for medical data classification
**期刊:** Journal of Biomedical Informatics
**卷期:** Volume 112
**發表日期:** December 2020
**文章編號:** 103623
**DOI:** 10.1016/j.jbi.2020.103623
**作者單位:**
- Department of Computer Science Engineering, Bennett University, Greater Noida, India
- Pitney Bowes Software, Noida, India
**研究主題:** 不平衡醫療資料分類 (Genetic Programming改良fitness function)
**資料集:** UCI Machine Learning Repository
- CKD (Chronic Kidney Disease)
- Fertility
- WDBC (Wisconsin Diagnostic Breast Cancer)
- BUPA (Liver Disorders)
**機器學習方法:** Genetic Programming (Proposed GP with novel fitness function), GP with Fave, SVM
**訓練策略:** 族群數1000, 最多100代, 80%訓練/20%測試, 重複30次
**主要成果:**
- CKD: AUC 1.00, F1-score 1.00
- WDBC: AUC 0.96
- Fertility: Recall提升至0.47 (vs SVM為0)
**主要貢獻:** 提出考慮預測誤差距離的新fitness function,有效處理類別不平衡問題

---

## Meeting11
**類型:** 論文討論與研究問題探討
**主題:** Genetic Programming在醫療資料分類的應用
**討論重點:**
- 模型實作vs文獻引用比較的公平性
- 預測誤差距離 (Prediction Error Distance) 概念
- 預測尿酸的臨床價值
- 特徵數量與Overfitting問題
- 缺失值補值後再預測的策略

---

## Meeting12
**英文標題:** Analysis of the performance of Genetic Programming on the Blood Glucose Level Prediction Challenge 2020
**作者:**
- David Joedicke, Gabriel Kronberger, Stephan Winkler - Josef Ressel Center for Symbolic Regression, Upper Austria University of Applied Sciences
- Oscar Garnica, J. Manuel Velasco, Sergio Contador, J. Ignacio Hidalgo - Universidad Complutense de Madrid
- J. Manuel Colmenar - Rey Juan Carlos University
**年份:** 2020
**研究主題:** 血糖預測 (Blood Glucose Level Prediction Challenge)
**資料集:** Ohio2020 dataset (6位T1DM患者的CGM + 胰島素幫浦 + 穿戴式感測器)
**預測目標:** 未來30分鐘與60分鐘的血糖值
**機器學習方法:**
- GP (Genetic Programming - 標準版)
- GP-OS (GP with Offspring Selection)
- GE (Grammatical Evolution - 單目標)
- MOGE (Multi-objective GE with NSGA-II)
- RF (Random Forest), LR, ARIMA
**評估指標:** RMSE, MAE, Clarke Error Grid (CEG)
**主要成果:**
- GP在30分鐘與60分鐘預測的RMSE、MAE整體最佳
- MOGE在30分鐘RMSE略優於GP
- CEG分析顯示GP與MOGE在A+B區比例高,臨床安全性佳
**創新點:** 引入可控未來資訊 (basal, bolus) 提升預測準確度

---

## Meeting13
**資料集:** DRYAD國際開放研究數據平台
**標題:** Associations of serum uric acid with cardiovascular disease risk factors: a retrospective cohort study in Southeastern China
**DOI:** 10.5061/dryad.z08kprrk1
**發表日期:** 2023/08/28 (更新 2023/08/31)
**研究主題:** 血清尿酸(SUA)與心血管疾病風險因子關聯 (三高:高血壓、高血糖、高血脂)
**資料來源:** 2010-2018杭州社區調查
**樣本:** 6,119位≥40歲參與者, 每人至少3次健康檢查, 共25,744筆記錄
**欄位數:** 15
**檢測頻率:** 3-8次
**三高比例:** 高血壓14.6%, 高血糖4.2%, 高血脂6.1%
**性別比例:** 66.9% : 33.1%
**機器學習方法 (規劃):** LR, RF, SVM, KNN, XGBoost, LightGBM, MLP, Genetic Programming

---

## Meeting14
**類型:** 文獻回顧與研究規劃
**研究主題:** 三高 (高血壓、高血糖、高血脂) 與慢性病預測
**研究重點:**
- 三高診斷標準整理
- 尿酸與慢性病的關係
- 全球與台灣三高趨勢分析
- 性別與年齡差異
- 共同危險因子與共病現象
**國際公開資料集:**
- NCD-RisC: 全球1975-2020三高趨勢
- Framingham Heart Study: 經典心血管風險隊列
- NHANES: 美國全國代表性健康數據
- MIMIC: ICU臨床資料
**研究方向:** 可解釋模型與黑盒模型在三高風險預測的實證比較

---

## Meeting15
**英文標題:** Use of Machine Learning to Predict the Incidence of Type 2 Diabetes Among Relatively Healthy Adults: A 10-Year Longitudinal Study in Taiwan
**研究設計:** 10年縱向研究 (2011-2021)
**研究機構:** 台中榮總臨床資料中心
**樣本數:** 6,687位相對健康的成人
**納入標準:**
- 10年內至少2次自費健檢
- 間隔<4年
- 無糖尿病病史
- 無缺失值
**預測特徵:** 33項 (人口學、生理測量、血液檢驗)
**重要發現:** 甲狀腺功能 (TSH, fT4) 為重要預測因子
**糖尿病診斷標準:** HbA1c > 6.5% 或 FBG > 126 mg/dL
**資料分類:**
- Class 0 (正常): 6,967人
- Class 1 (潛在糖尿病): 76人
**資料分割:** 訓練集60% / 測試集40%
**機器學習方法:** Random Forest, Logistic Regression, XGBoost
**研究主題:** 第二型糖尿病早期預測
**主要貢獻:** 亞太地區使用ML預測糖尿病的研究,針對台灣人口

---

## 總結統計

- **總會議數:** 15場
- **期刊論文:** 7篇 (IEEE期刊5篇, 其他期刊2篇)
- **碩士論文:** 3篇 (清華大學1篇, 台北醫學大學1篇, 腎功能研究1篇)
- **研究方向討論:** 5場

### 研究主題分布
- 慢性腎臟病預測: 2篇
- 心臟病預測: 1篇
- 糖尿病預測: 3篇
- 多重慢性疾病預測: 1篇
- miRNA-疾病關聯: 1篇
- 尿酸預測: 1篇
- 血糖預測: 1篇
- 三高預測: 2篇
- Genetic Programming應用: 3篇

### 主要機器學習方法
- Random Forest: 9次
- Support Vector Machine (SVM): 8次
- Logistic Regression: 7次
- XGBoost/Gradient Boosting: 7次
- Decision Tree: 6次
- CNN (Convolutional Neural Network): 1次
- Genetic Programming: 3次
- K-NN: 4次
- Naive Bayes: 3次
- SMOTE: 4次
- Neural Network/Deep Learning: 3次

### 可解釋性方法
- SHAP (Shapley values): 2次
- MARS (Multivariate Adaptive Regression Splines): 1次
- Genetic Programming (白箱模型): 3次

### 主要資料來源
- UCI Machine Learning Repository: 5次
- 醫院EHR系統: 4次
- CDC/NHANES: 2次
- Framingham Heart Study: 1次
- 台灣醫療機構: 2次
