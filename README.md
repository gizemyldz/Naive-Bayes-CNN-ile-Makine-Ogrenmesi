# Naive-Bayes-CNN-ile-Makine-Ogrenmesi
Skin  Segmentation veri setinde Naive Bayes ve CNN  algoritmalarıyla duygu analizi
Bu projenin amacı Skin  Segmentation veri setini Naive Bayes ve CNN  algoritmalarıyla çalıştırarak duygu analizi  yapmaktır.Projede verileri işlemeye hazır hale  getirerek NB ve CNN modellerine eğitim ve test  verisi halinde sokarak çıktıları gözlemlendi.
II.	SKIN SEGMENTATION/CİLT SEGMENTASYONU VERİ KÜMESİ  
Bu veri seti, çeşitli yaş gruplarının (genç, orta ve yaşlı), ırk gruplarının (beyaz, siyah ve asyalı) yüz görüntülerinden ve FERET+PAL veritabanlarından elde edilen cinsiyetlerden rastgele B, G, R değerleri örnekleyerek toplanmıştır. Toplam örnek büyüklüğü 245.057'dir; bunların 50.859'u cilt örnekleri ve 194198'i cilt dışı numunelerdir.
Bu veri kümesi, ilk üç sütunun B, G, R (x1, x2 ve x3 özellikleri) değerleri ve dördüncü sütunun sınıf etiketlerinden (karar değişkeni y) oluşur.245.057 * 4 boyutundadır.
B=Blue,R=Red,G=Green
Veri kümesinin sınıf anahtarının(1-2) oranı:
![image](https://user-images.githubusercontent.com/49057258/151405168-ab348c68-94fe-49a6-8941-8894e55b716a.png)

B,R ve G sütunlarındaki özellikler satırda bir araya gelince kişinin cildi hakkında doğru bir tahmin yapıyorsa 1,yapmıyorsa 2 verir.
