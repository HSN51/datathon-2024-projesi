# datathon-2024-projesi
# Datathon 2024 - Değerlendirme Puanı Tahmini
Bu proje, Datathon 2024 kapsamında verilen girişimcilik başvuru verilerini kullanarak, başvuranların değerlendirme puanlarını tahmin etmek amacıyla geliştirilmiştir. Projede veri ön işleme, eksik veri doldurma, kategorik verilerin sayısal hale getirilmesi ve bir regresyon modeli kullanarak puan tahmini yapılmıştır.

## Proje Amacı
Bu projede, 11.049 başvuranın anonimleştirilmiş verileri (test verisi) kullanılarak, değerlendirme puanı kolonunu tahmin etmek hedeflenmiştir. Eğitim verisi (train verisi), 2014'ten itibaren yapılan başvurulara ait kişisel ve aile bilgilerini içermektedir. Bu veri üzerinden bir tahmin modeli oluşturulmuş ve test verisi ile doğrulama yapılmıştır.

## Kullanılan Teknolojiler
Python: Projenin temel programlama dili.
Pandas: Veri yükleme ve manipülasyon işlemleri için.
Seaborn ve Matplotlib: Veri görselleştirme için.
Scikit-learn (sklearn): Model eğitimi, verilerin işlenmesi ve performans değerlendirilmesi için.
NumPy: Sayısal işlemler için.
