# Customer Churn Prediction App 📊

Bu proje, **müşteri kaybı (churn)** tahmini yapmak için derin öğrenme modelleri kullanan bir uygulamadır. Streamlit ile geliştirilmiş olan bu uygulama, kullanıcıların müşteri verilerini girerek, müşterinin kayıp olma olasılığını tahmin etmelerini sağlar. Uygulama, TensorFlow ile eğitilmiş bir modelin yanı sıra, veri ön işleme için `LabelEncoder`, `OneHotEncoder` ve `StandardScaler` kullanmaktadır.

## Uygulama Linki 🌐

Uygulamanın web arayüzüne [buradan erişebilirsiniz](https://churnprediction-cty3msuyljutuv4epwwrvb.streamlit.app/).

## Kullanılan Teknolojiler 🛠️

- **Python 3.x**: Projenin temel programlama dili.
- **Streamlit**: Web arayüzü için kullanıldı.
- **TensorFlow**: Derin öğrenme modeli ve tahminler için kullanıldı.
- **Scikit-learn**: Veri ön işleme (özellik mühendisliği) için kullanıldı.
- **Pandas**: Veri işleme ve manipülasyon için kullanıldı.
- **NumPy**: Matematiksel işlemler ve veri manipülasyonu için kullanıldı.
- **Pickle**: Model ve encoder'ların saklanması için kullanıldı.

## Proje Açıklaması 📝

Bu proje, müşteri kaybı (churn) tahminini gerçekleştiren bir makine öğrenmesi modelini barındıran bir uygulamadır. Kullanıcılar, çeşitli müşteri bilgilerini girdikten sonra, uygulama modeli kullanarak müşterinin kayıp olma olasılığını hesaplar. Uygulama, kullanıcı dostu bir arayüz sunarak veri bilimi ve makine öğrenmesi konularına ilgi duyan herkesin kullanabileceği bir platform oluşturur.

## Uygulama Özellikleri 🚀

- **Müşteri Bilgileri Girişi**: Kullanıcılar, müşteri bilgilerini (yaş, cinsiyet, bakiye, kredi puanı, maaş gibi) girer.
- **Churn Tahmini**: Girilen verilere dayalı olarak, model müşteri kaybı olasılığını tahmin eder.
- **Kullanıcı Dostu Arayüz**: Streamlit sayesinde sade ve kullanıcı dostu bir arayüz sunulmuştur.
- **Sonuç Gösterimi**: Tahmin sonuçları, kullanıcıya görsel olarak anlaşılır bir şekilde sunulur.

## Kullanım 📦

### Gereksinimler

Projenin çalışabilmesi için aşağıdaki Python kütüphanelerine ihtiyacınız olacak:

- `streamlit`
- `tensorflow`
- `scikit-learn`
- `pandas`
- `numpy`
- `pickle`
