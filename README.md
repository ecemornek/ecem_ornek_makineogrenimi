Bu proje, New York City'deki Airbnb kiralık evlerinin fiyatlarını tahmin etmeye yönelik bir makine öğrenmesi uygulamasıdır. Dolayısıyla 2019 yılına ait New York şehrindeki Airbnb ilanlarını içeren bir veri seti kullanılmıştır. 

Pandas, Matplotlib, Seaborn ve Scikit-learn gibi Python kütüphaneleri kullanılarak EDA (Keşifsel Veri Analizi) yapılmış, ardından Linear Regression modeli geliştirilmiştir.

Airbnb kullanıcıları için kiralık ev fiyatlarının belirlenmesi genellikle deneyime dayalı bir süreçtir. Bu projede amaç,fiyat tahmin modeli oluşturmaktır.

Kullanılan Yöntemler ve Teknikler:

EDA (Exploratory Data Analysis): 
  - Kayıp veriler analiz edildi ve dolduruldu.
  - Aykırı değerler (outliers) temizlendi.
  
Veri Ön İşleme:
  - Kategorik veriler one-hot encoding ile dönüştürüldü.
  - `price` değişkeninin aralığı düşürüldü.
  - Gerekli sütunlar çıkarıldı.
  - Özellik ölçekleme (StandardScaler) uygulandı.
  - LinearRegression modeli geliştirildi.
  - Değerlendirme Metriği olarak R², RMSE kullanıldı.


Bu tarz bir model; Ev sahiplerinin doğru fiyat belirlemesini sağlar. Airbnb platformlarının otomatik fiyat önerisi yapabilmesini mümkün kılar.

Kaggle Linki:https://www.kaggle.com/code/ecemrnek/akbankmakine-renmesibootcamp
