# Top_50_Hotels_World
# Otel Fiyat Tahmin Projesi / Hotel Price Prediction Project

Bu proje, en iyi 50 otelin başlangıç fiyatlarını tahmin etmek için makine öğrenmesi yöntemlerini kullanmaktadır. Çalışmada lineer regresyon modeli kullanılmış ve veri setindeki özellikler analiz edilmiştir.

## Proje İçeriği / Project Overview

Bu proje, dünya çapında en iyi 50 otelin başlangıç fiyatlarını etkileyen faktörleri analiz etmek ve fiyat tahmininde bulunmak amacıyla yapılmıştır. Çalışmada `Rank`, `Location`, `Total Rooms`, `Hotel Amenities` gibi otel özellikleri kullanılarak lineer regresyon modeli eğitilmiş ve model performansı çeşitli metriklerle değerlendirilmiştir.

This project aims to analyze the factors affecting the starting prices of the top 50 hotels worldwide and predict prices using machine learning. The study employs features such as `Rank`, `Location`, `Total Rooms`, and `Hotel Amenities` to train a linear regression model, and model performance is evaluated using various metrics.

## Veri Seti Hakkında / About the Dataset

Veri seti, dünyanın en iyi 50 oteline ait sıralama, konum, oda sayısı, başlangıç fiyatı ve diğer olanakları içermektedir. Bu veri seti, makine öğrenmesi modeli geliştirmek ve otellerin sunduğu özelliklerin fiyat üzerindeki etkisini anlamak için kullanılmıştır.

The dataset contains information about the top 50 hotels worldwide, including ranking, location, total rooms, starting price, and other amenities. It is used to build a machine learning model to understand the impact of hotel features on price.

## Kullanılan Yöntemler ve Analiz Süreci / Methods and Analysis Process

1. **Veri Ön İşleme / Data Preprocessing**: Eksik verilerin doldurulması (`Drinking Area` sütunundaki eksik veriler 'Bar' olarak doldurulmuştur), kategorik değişkenlerin one-hot encoding yöntemiyle sayısal hale getirilmesi.

   - Missing values were filled (e.g., missing values in the `Drinking Area` column were replaced with 'Bar'), and categorical variables were converted to numerical form using one-hot encoding.

2. **Veri Setini Ayırma / Splitting the Dataset**: Eğitim ve test seti olarak veri ikiye ayrıldı.

   - The dataset was split into training and testing sets.

3. **Model Eğitimi / Model Training**: Lineer regresyon modeli `Total Rooms`, `Rank` ve diğer özelliklerle eğitildi.

   - A linear regression model was trained using features like `Total Rooms`, `Rank`, and other attributes.

4. **Model Performansını Değerlendirme / Model Performance Evaluation**: Modelin tahmin performansı, MAE, MSE, RMSE ve R² metrikleri ile değerlendirildi. Görselleştirmeler ile gerçek fiyatlara karşı tahmin edilen fiyatlar ve hata dağılımı incelendi.

   - Model performance was evaluated using metrics such as MAE, MSE, RMSE, and R². Visualizations showed actual vs. predicted prices and error distribution.

5. **Özellik Önemini Analiz Etme / Feature Importance Analysis**: Modeldeki özelliklerin fiyat tahminine etkisini analiz etmek için özellik önemi görselleştirildi.

   - Feature importance was visualized to analyze the impact of features on price predictions.

![indir](https://github.com/user-attachments/assets/68f04519-0563-4685-ae08-1e8ff552810b)
![otel2](https://github.com/user-attachments/assets/9c698188-2c6d-4cba-b17d-aadc03c5643f)
![indir (1)](https://github.com/user-attachments/assets/589e5bd7-0750-4782-8d4a-f5bb272de73a)
![otel1](https://github.com/user-attachments/assets/8f8a2c85-272e-4345-bb19-9d0537a78d96)




