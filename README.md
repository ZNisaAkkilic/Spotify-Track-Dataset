# Spotify-Track-Dataset
Bu proje, Spotify Track Dataset üzerinde çeşitli makine öğrenmesi ve derin öğrenme algoritmaları kullanarak veri keşfi, modelleme ve değerlendirme aşamalarını içermektedir. Dataset, Spotify'ın müzik parçalarına ait çeşitli özellikleri ve etiketleri içermektedir. Bu veriler, müzik analizi, öneri sistemleri ve şarkı sınıflandırma gibi çeşitli uygulamalar için kullanılabilir.

Dataset Açıklaması
Spotify Track Dataset, şarkılara dair farklı özellikleri içeren bir veri kümesidir. Bu özellikler arasında şarkı adı, sanatçı, albüm, popülerlik, dans edilebilirlik, enerji, tempo, anahtar, şarkı uzunluğu ve daha fazlası yer almaktadır. Verinin amacı, şarkıların özelliklerine dayalı olarak popülerlik tahmini yapmaktır.

Verinin Yapısı
Dataset, aşağıdaki sütunlardan oluşmaktadır:

track_id: Şarkının benzersiz kimliği.

name: Şarkının adı.

artist: Şarkıcının veya grubun adı.

album: Şarkının bulunduğu albüm adı.

popularity: Şarkının Spotify'daki popülerlik skoru (0-100 arasında).

danceability: Şarkının dans edilebilirlik skoru (0-1 arasında).

energy: Şarkının enerjikliği skoru (0-1 arasında).

key: Şarkının tonuna ait bir sayısal temsil.

loudness: Şarkının ses seviyesi (dB).

mode: Müzikal ton (1: majör, 0: minör).

speechiness: Konuşma oranı.

acousticness: Akustiklik oranı.

instrumentalness: Enstrümantal şarkı oranı.

liveness: Canlı performans oranı.

valence: Şarkının ruh halini (pozitif veya negatif) temsil eden bir değer.

tempo: Şarkının temposu (BPM).

duration_ms: Şarkının süresi (milisaniye cinsinden).

time_signature: Zaman ölçüsü (genellikle 4/4).

Kullanım Alanları
Bu veri kümesi, aşağıdaki gibi çeşitli uygulamalar için kullanılabilir:

Müzik öneri sistemleri: Kullanıcılara ilgi alanlarına göre şarkı önerileri yapma.

Müzik türü sınıflandırması: Şarkıların özelliklerine dayanarak müzik türlerini sınıflandırma.

Şarkı popülerliği tahmini: Şarkının gelecekteki popülerliğini tahmin etme.

Veri analizi ve görselleştirme: Farklı özellikler arasındaki ilişkileri inceleme.

Proje Adımları
Veri Keşfi: Verinin genel yapısı incelenecek ve eksik veriler, aykırı değerler belirlenecektir.

Veri Ön İşleme: Veriler, eksik değerler, kategorik verilerin sayısal verilere dönüştürülmesi, veri ölçeklendirme gibi işlemlerle temizlenecektir.

Modelleme: Farklı makine öğrenmesi ve derin öğrenme modelleri (Lojistik Regresyon, Karar Ağaçları, Random Forest, SVC, Gradient Boosting, DNN, CNN, LSTM) kullanılacaktır.

Değerlendirme: Modellerin başarımı, doğruluk, F1 skoru ve ROC-AUC gibi metrikler ile değerlendirilecektir.

Sonuçlar ve Yorumlar: Sonuçlar karşılaştırılacak ve en başarılı model seçilecektir.

Kullanım
Veriyi indirin: Dataset'i indirip projede kullanabilirsiniz.

Gerekli kütüphaneleri yükleyin: Aşağıdaki Python kütüphanelerini yükleyerek projeyi çalıştırabilirsiniz:


pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
Proje dosyasını çalıştırın: main.py dosyasını çalıştırarak projeyi başlatabilirsiniz.

.
