
# Mahsul-neri
# Mahsul Önerisi Projesi

## Giriş
Bu proje, toprak türü, sıcaklık, nem ve pH seviyesi gibi faktörlere dayalı olarak en uygun mahsulü sınıflandırmayı amaçlamaktadır. Amaç, çiftçilere daha iyi kararlar almalarında yardımcı olmaktır.

## Veri Seti
[Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) veri seti kullanılmıştır.

## Veri Keşfi ve Analizi (EDA)
Numpy, Pandas, matplotlib ve seaborn kütüphaneleri kullanılarak veri analizi yapılmıştır. Görselleştirme ve grafiklerle veri seti analiz edilmiştir.

## Veri Ön İşleme
- Verilerin temizlenmesi
- Değişkenlerin normalize edilmesi ve kategorik değişkenlerin kodlanması
- Verilerin eğitim ve test kümelerine bölünmesi

## Model Seçimi ve Eğitimi
- KNN, SVM, Lojistik Regresyon, Karar Ağacı ve Random Forest gibi modeller eğitildi ve değerlendirildi.
- Modellerin performansı Accuracy, Recall, F1 Skoru, Precision, AUC ve ROC gibi metriklerle değerlendirildi.

## Hiperparametre Optimizasyonu
- Grid Search ve Randomized Search kullanılarak modellerin hiperparametreleri optimize edildi.

## Sonuçlar
- Geliştirilmiş Model Doğruluğu: 98.64%
- Random Forest Model Doğruluğu: 99.32%

## Sonuç ve Gelecek Çalışmalar
Bu proje, makine öğrenimi ile tarımda daha iyi kararlar almanın nasıl mümkün olduğunu göstermektedir. Gelecek çalışmalarda, XGBoost veya LightGBM gibi diğer modelleri denemek ve daha büyük veri setleri kullanmak önerilmektedir.
