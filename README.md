# Miuul-Data-Science-and-Machine-Learning-Bootcamp

Yaklaşık 4 ay süren Miuul Data Science and machine learning bootcamp sürecinde 9 farklı data science proje yapılmıştır her bir projenin içeriği aşağıdaki gibidir:



## Task 1-2-3
## ✅ Temel Python, List Comprehension ve Pandas Alıştırmaları

Bu bölümde Python programlama diline yeni başlayanlar için hazırlanmış temel seviye uygulamalar gerçekleştirilmiştir.

### 🎯 Kapsam:
- **Python Temelleri:** `int`, `float`, `complex`, `list`, `dict`, `tuple`, `set` gibi veri yapıları üzerinde `type()`, `append()`, `pop()` gibi temel işlemler.
- **String İşlemleri:** Küçük-büyük harf dönüşümleri, `replace()`, `split()` gibi metin temizleme teknikleri.
- **List Comprehension:** Koşullu ifade yapılarıyla kolon isimlendirme, string manipülasyon ve dataframe kolon filtreleme uygulamaları.
- **Pandas ile Tanışma:** `titanic` ve `tips` veri setleri üzerinde veri tipi dönüştürme, filtreleme, gruplama (`groupby`), eksik veri doldurma ve temel veri analizi.

---
## Task 4
## ✅ Lead Calculation with Level-Based Classification

### 🎯 Amaç:
Bir oyun şirketinin müşterilerini demografik bilgilere göre segmente etmesi ve bu segmentlere ortalama gelir tahminleri oluşturması.

### 🔧 İşlemler:
- `COUNTRY`, `SOURCE`, `SEX`, `AGE` bilgilerine göre ortalama gelir hesaplama
- Yaş kategorileri oluşturma (ör: 0_18, 19_23, ...)
- Yeni müşteri tanımı: `TUR_ANDROID_MALE_24_30`
- Segmentlere (`A`, `B`, `C`, `D`) ayrım ve analiz

---
## Task 5
## ✅ Diabetes Feature Engineering

### 🎯 Amaç:
Pima Indian kadınlarına ait medikal verilerle kişilerin diyabet hastası olup olmadığını tahmin etmek.

### 🔧 İşlemler:
- Keşifsel veri analizi (EDA)
- Eksik değer işlemleri (glukoz, insülin gibi sıfır olamayacak değerleri `NaN` yapma)
- Yeni değişkenler üretme
- Encoding (`LabelEncoder`) ve standardizasyon (`StandardScaler`)
- Modelleme: `RandomForestClassifier`
- Model değerlendirme metrikleri: Accuracy, Precision, Recall, F1, ROC AUC

---
## Task 6
## ✅ Hitters Salary Prediction with Linear Regression

### 🎯 Amaç:
Beyzbol oyuncularının performans istatistiklerine göre maaş tahmini yapmak.

### 🔧 İşlemler:
- Eksik ve aykırı değer analizleri
- Yeni özellik çıkarımı: kariyer oranları, sezon verimlilikleri
- `RobustScaler` ile ölçekleme
- Lineer regresyon modeli (`LinearRegression`)
- Model değerlendirme: MSE, RMSE, MAE, R²

---
## Task 7
## ✅ House Price Prediction

### 🎯 Amaç:
Ev özelliklerine göre satış fiyatlarını tahmin etmek.

### 🔧 İşlemler:
- Sayısal ve kategorik değişken analizi
- Aykırı değer baskılama
- Eksik değerlerin median, mode ve `"No"` ile doldurulması
- Çoklu regresyon modelleri: `XGBoost`, `LGBM`, `CatBoost`, `Ridge`, `SVR` vs.
- Log dönüşümü ile hedef değişken normalleştirme

---
## Task 8
## ✅ Telco Churn Prediction

### 🎯 Amaç:
Bir telekom firmasındaki müşteri kayıplarını (`Churn`) tahmin edebilmek.

### 🔧 İşlemler:
- `TotalCharges` kolonunun tipi dönüşümü
- Kategorik ve sayısal değişken analizi
- Eksik değerler ve aykırı değer işlemleri
- Yeni değişken oluşturma (örneğin: sözleşme türlerine göre tenure analizi)
- Encoding ve standardizasyon
- Ensemble modeller: `XGBoost`, `CatBoost`, `LGBM`, `RandomForest` ile karşılaştırmalı modelleme

---
## Task 9
## ✅ Customer Segmentation with RFM and K-Means Clustering

### 🎯 Amaç:
Müşteri davranışlarına göre segmentasyon yaparak pazarlama stratejileri oluşturmak.

### 🔧 İşlemler:
- RFM metriklerinin (`Recency`, `Frequency`, `Monetary`) hesaplanması
- Aykırı değerlerin baskılanması
- Log dönüşümü ve `StandardScaler` ile ölçekleme
- Kümeleme: `KMeans` ve `Agglomerative Clustering`
- Optimum küme sayısının belirlenmesi: `KElbowVisualizer`

---

📁 Her bir ödevin kodlarına ilgili klasörler üzerinden erişebilirsiniz.


