# Kredi Kartı Dolandırıcılığı Tespiti
Bu proje, kredi kartı dolandırıcılığı tespiti için lojistik regresyon modeli kullanan bir Python kodunu içermektedir. Kodun veri seti, [Kaggle] sitesinden alınmıştır. Veri seti, 2013 yılında iki günlük Avrupa kredi kartı işlemlerini içermektedir. Veri setinde 284807 satır ve 31 sütun bulunmaktadır. Sütunlardan 28 tanesi, PCA ile anonimleştirilmiş özellikleri temsil etmektedir. Diğer iki sütun ise işlem tutarı (Amount) ve işlem zamanı (Time) olarak adlandırılmıştır. Son sütun ise dolandırıcılık sınıfını (Class) göstermektedir. Sınıf sütunu, 0 veya 1 değerleri alabilir. 0 değeri normal işlemi, 1 değeri ise dolandırıcılık işlemini ifade eder.

## Projenin Amacı
Bu projenin amacı, veri setindeki özellikleri kullanarak dolandırıcılık işlemlerini tespit etmek ve lojistik regresyon modelinin performansını değerlendirmektir.

## Projenin Yapısı
Bu proje, iki ana bölümden oluşmaktadır:

### Veri Setinin İncelenmesi: 
Bu bölümde, veri setinin incelenmesi, görselleştirilmesi ve ön işleme adımları gerçekleştirilmiştir.

### Model Oluşturma ve Değerlendirme: 
Bu bölümde, veri setini eğitim ve test kümelerine ayırmak, lojistik regresyon modeli oluşturmak ve modelin performansını ölçmek için gerekli adımlar atılmıştır.

## Projenin Sonuçları
- Bu projede, lojistik regresyon modelinin eğitim ve test kümelerinde yüksek doğruluk, hassasiyet, duyarlılık ve F1 skoru elde ettiği görülmüştür. Ancak modelin dolandırıcılık sınıfını tahmin etmede zorlandığı da fark edilmiştir. Dolandırıcılık sınıfının çok az örnek içermesi ve veri setinin dengesiz olması bu durumun nedenleri arasında sayılabilir.

- Bu projede, modelin performansını artırmak için veri setinin dengelenmesi, farklı özellik seçimi veya çıkarımı yöntemleri, farklı sınıflandırma algoritmaları veya hiperparametre optimizasyonu gibi yöntemler denenmelidir. Ayrıca modelin gerçek hayattaki verilerle de test edilmesi gerekmektedir.

## Projenin Kaynakları
Bu proje için kullanılan [Veri Seti] : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
