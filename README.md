<div align="center">

VALORANT VCT 2024: DATA SCIENCE & MVP PREDICTOR
[![Python](https://img.shields.io/badge/Python-3.12-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Data-Pandas%20%7C%20NumPy-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/AI-Scikit--Learn-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Kaggle](https://img.shields.io/badge/Live-Kaggle%20Notebook-20BEFF.svg?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/muhammederdem69/valorant-pro-match)

"İyi bir aim seni en fazla platine çıkarır, ama veriyi iyi okuyan bir analitik model takımını şampiyon yapar."

</div>

---

Bu proje, e-spor dünyasını sadece bir oyun olarak değil, devasa bir veri havuzu olarak ele alıyor. Rekabetçi oyunların dinamiklerini Veri Bilimi (Data Science) süzgecinden geçirerek, profesyonel oyuncuların istatistiklerini analiz ettik. Amacımız; ham verileri işleyerek MVP (En Değerli Oyuncu) potansiyelini tahmin eden bir makine öğrenmesi sistemi kurmaktır.

---

CANLI PROJE BAĞLANTISI
Yazdığım tüm kodları, veri setini, temizleme süreçlerini ve modelin çalışma anını direkt Kaggle üzerinden canlı olarak inceleyebilirsiniz:

Kaggle: Valorant Pro Match Analysis & ML Model

---

KULLANILAN TEKNOLOJİLER (TECH STACK)
Bu projede kopyala-yapıştır mantığıyla değil, sektör standartlarında Veri Bilimi araçlarıyla ilerledik:

| Kategori | Araçlar | Projedeki Görevi |
| :--- | :--- | :--- |
| Geliştirme Dili | Python 3.12 | Sistemin ana omurgası ve algoritma yönetimi. |
| Veri Manipülasyonu | Pandas & NumPy | İnatçı e-spor verilerini temizleme ve matematiksel işlemler. |
| Görselleştirme | Seaborn & Matplotlib | Veriyi göze hitap eden profesyonel grafiklere dökme. |
| Yapay Zeka | Scikit-Learn | Random Forest Classifier ile oyuncu performans sınıflandırması. |
| Ortam | Kaggle Notebook | Bulut tabanlı derleme, test ve global sunum. |

---

GELİŞTİRME AŞAMALARI (OYUN PLANI)
Veri Temizliği (Lag'ı Bitirme Seansı)
E-spor verileri Kaggle'dan her zaman oyuna hazır gelmez. Sayı olması gereken yerlerde yüzdelik dilimler, virgüller veya boş bırakılmış (NaN) hücreler vardı. Bu kirli verileri özel Python fonksiyonlarıyla ayıkladık. Tüm istatistikleri (ACS, KDR, KAST vb.) sayısal formatlara zorlayarak algoritmanın hata yapmasını engelledik.

Keşifsel Veri Analizi (Insight Avı)
Sadece rakamlara bakmadık, "Bu rakam bize maç hakkında ne anlatıyor?" dedik. 
Bir oyuncunun skor katkısının sadece adam öldürmek (Kill) olmadığını gördük.
Hayatta kalma (Survive) ve asist (Assist) gibi oranların (KAST) toplam skora (ACS) olan etkisini detaylı bar ve scatter grafiklerle kanıtladık.

Model Eğitimi (AI ile MVP Tahmini)
Projenin en can alıcı noktası burasıydı. Belirli bir ACS barajı belirledik ve bu barajın üstünde kalan oyuncuları "Elit" olarak sınıflandırdık. Random Forest algoritmasını kullanarak; oyuncuların KDR, ADR ve HS oranlarına bakıp, o oyuncunun "takım taşıyıcısı" olup olmadığını tahmin eden bir makine öğrenmesi modeli eğittik.

---

SON SÖZ VE VİZYON
Bu çalışma, Bilgisayar Programcılığı eğitiminde edindiğimiz analitik düşünme yapısının e-spor dünyasındaki reel bir uygulamasıdır. Verinin ham halinden, anlamlı bir tahmin üreten yapay zeka modeline kadar tüm yaşam döngüsü başarıyla tamamlanmıştır.

<br>

Geliştirici: Muhammed Emin Erdem
Eğitim: İnönü Üniversitesi - Bilgisayar Programcılığı
Platform: GitHub Profili
