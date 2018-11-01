# Medikal Araştırmalar İçin Derin Öğrenmeye Giriş
Bu yazı dizisi, bir dizi sunum,Google koLab ve destekleyici kodlarını içeriyor.Makine öğrenimi ve derin öğrenme tekniklerini tanıtıyor.
Bu yazı dizisi İstinye Üniversitesi Mühendislik bölümü dekanı Prof.Dr.Çetin Kaya KOÇ işbirliği ile hazırlanmıştır.Bu ders model oluşturma ve doğrulama temel ve ileri tekniklerini tanıtmaktadır.
<a href="http://cetinkoc.net/">Prof. Çetin Kaya Koç</a>
Tüm kurs 11 adet 1 saatlik modüllere ayrılmıştır. Tüm bu uygulamalar Google CoLab,ücretsiz açık kaynak yazılımları PyTorch,Python kullanılarak bir bulutta yapılır. Ve içindekiler aşağıdaki gibidir.
1. Tanıtım
* Son medikal uygulamaların incelenmesi.  
* Yapay Zeka, Makine Öğrenimi, Derin Öğrenme : Terminolojisi ve Tarihi.
* Sınıfın durumunu gözden geçirme.
* Goodle CoLab ve Python'a Giriş

2. Denetimli ve denetimsiz öğrenmeye giriş.
* Intro to sci-kit learn /Python ile makine öğrenimi manasına geliyor./
* Intro to Matplotlib /Veri Görselleştirmeye Giriş/
* İlkelleme
* Sınıflandırma
* Kümelenme

3. Denetimli Teknikler
* Doğrusal İlkelleme
* Linear disciminant analysis /Koordinat dönüşüm tekniği/
* Random forests / Birçok Decision Tree Algoritmasını N defa kullanarak daha iyi tahminler yapmamızı sağlayan bir modeldir.

4. Denetimsiz Teknikler ve Güvenilirlik Oranı #1
* K-Nearest Neighbors / Sınıflandırmada kullanılan bu algoritmaya göre sınıflandırma sırasında çıkarılan özelliklerden, sınıflandırılmak istenen yeni bireyin daha önceki bireylerden K tanesine yakınlığına bakılmasıdır.
* Precision, accuracy, recall: F-Score / İkili sınıflandırmada istatistiklerin analizi.
* Güven Aralığı
* Cross-validation /Bu yazının amacı, literatürde k-fold cross validation (k katlamalı çarpraz doğrulama) yöntemi olarak geçen yöntemi anlatmaktır. Veri madenciliği çalışmalarında, uygulanan yöntemin başarınının sınanması için, veri kümesini eğitim ve test kümeleri olarak ayırılmaktadır/

5. Güven Tahmini #2
* Confusion matrices / Sınıflandırma algoritmasının performansının özetlenmesi./
* ROC curves /Sinyal algılama teorisinde, alıcı işletim karakteristiği ya da sade biçimde ROC eğrisi olarak tanımlanmaktadır. ROC eğrisi, ikili sınıflandırma sistemlerinde ayrım eşik değerinin farklılık gösterdiği durumlarda, hassasiyetin kesinliliğe olan oranıyla ortaya çıkmaktadır./
* Interpolation and extrapolation/?/
* Curse of dimensionality /Yüksek Boyut Laneti/

6. Snirsel hafızaya giriş
* Doğrusal vs Doğrusal Olmayan Fonksiyonlar
* The perceptron /Sinirsel Hafıza Modeli/
* Multi-Layer Perceptron (MLP)/Çok katmanlı algılayıcı
* Review of Gradient Descent /Dereceli Azalmanın İncelenmesi

7. PyTorch ile Derin Öğrenme 
* Implement MLP with PyTorch/Katmanın bütün girişleri ve bütün çıkışları birbirine bağlı ve her birinin ayrı bir weighti var. Burada oluşturacağımız ağımız sadece bu tip katmanlardan oluşacak. Bu tip bir ağ mimarisine Multi Layer Perceptron (MLP) deniyor.
* PyTorch Nasıl ayıklanır?
* Eğitim sürecinin durumu nasıl izlenir?
* Sinirsel hafızaların popüler diğer tipleri.

8. Sinirsel Hafızların Evrimi
* Teori
* PyTorch Uygulamaları
* Veri Toplama Ve Büyük Veri Kümeleri(HDF5)

9. CNNs ile görüntü sınıflandırma
* Examples where CNNs surpass humans/ Sinirsel hafıza evriminin insana üstün geldiği örnekler/
* CNN'leri aşabilen fakat insanlar için muazzam örnekler.
* Mevcut CNN modellerinin örnekleri
* PyTorch üzerinden model oluşturmak konuunda daha fazla detay.

10. CNNs ile görüntü ayrıştırma
* Kullanılabilecek mevcut model örnekleri.
* PyTorch Üzerinden kendi modelimizi kurma ve eğitme.

11. İleri düzey hafıza eğitimi ve doğrulaması
* dev-train-test sets /Makine öğreniminde veri üzerinden öğrenebilen ve tahminlerde bulunabilen algoritmaların çalışması ve inşası./
* How to design a custom network and prevent over-fitting / Rasgele hafızanın kendini tekrarlamısını önlemek./
* t-SNE visualization /Çok boyutlu veri kümelerini 2 veya 3 boyuta indirgeyerek görselleştirme./
* Attribution visualization /Algoritma Özelliklerini görselleştirme/
