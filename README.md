
VALORANT VCT 2024: DATA SCIENCE & MVP PREDICTOR
"İyi bir aim seni en fazla platine çıkarır, ama veriyi iyi okuyan bir analitik model takımını şampiyon yapar."

Bu proje, e-spor arenasını sadece izlemekle kalmayıp, arka planda dönen matematiği ve veriyi anlamak için geliştirildi. Rekabetçi oyunların dinamiklerini Veri Bilimi (Data Science) süzgecinden geçiriyoruz. Valorant Champions Tour (VCT) 2024 verilerini kullanarak; sadece skor tablosuna bakmak yerine istatistikleri okuyup MVP (En Değerli Oyuncu) potansiyelini tahmin eden bir makine öğrenmesi sistemi kurduk.

---

CANLI PROJE BAĞLANTISI
Yazdığım tüm kodları, veri setini, temizleme süreçlerini ve modelin çalışma anını direkt Kaggle üzerinden canlı olarak inceleyebilirsiniz:

Kaggle: Valorant Pro Match Analysis & ML Model

---

KULLANILAN TEKNOLOJİLER (TECH STACK)
Bu analiz sürecinde standart bir kopyala-yapıştır mantığıyla ilerlemedik. Veri mimarisini ve tahminleme modelini şu araçlarla sıfırdan inşa ettik:

| Kategori | Teknoloji / Kütüphane | Projedeki Görevi |
| :--- | :--- | :--- |
| Geliştirme Dili | Python 3.12 | Sistemin ana omurgası ve mantık katmanı |
| Veri Manipülasyonu | Pandas, NumPy | İnatçı e-spor verilerini temizleme ve matematiksel matris işlemleri |
| Görselleştirme | Seaborn, Matplotlib | Veriyi anlamlı grafiklere dökme (Bar Chart, Scatter Plot) |
| Makine Öğrenmesi | Scikit-Learn | Random Forest Classifier ile performans sınıflandırma tahmini |
| Çalışma Ortamı | Kaggle Notebook | Bulut tabanlı derleme, test ve sunum |

---

GELİŞTİRME AŞAMALARI (OYUN PLANI)
Veri Temizliği (Lag'ı Ortadan Kaldırmak)
E-spor verileri Kaggle'dan veya API'lerden her zaman tertemiz gelmiyor. Sayı olması gereken yerlerde yüzdelik dilimler, virgüller veya boş bırakılmış (NaN) hücreler bulunuyordu. Verilerdeki bu tip uyuşmazlıkları özel fonksiyonlarla ayıkladık ve tüm istatistikleri (ACS, KDR, KAST vb.) float (sayısal) formatlara zorlayarak algoritmanın anlayacağı, hatasız bir yapıya getirdik.

Keşifsel Veri Analizi (Insight Avı)
Veriyi sadece alt alta listelemedik, "Bu rakamlar bize maç hakkında ne söylüyor?" sorusuna odaklandık. 
Bir oyuncunun skor katkısının sadece adam öldürmek (Kill) olmadığını; hayatta kalma (Survive), asist yapma (Assist) ve takas (Trade) gibi KAST oranlarının takım başarısına ve ACS (Average Combat Score) puanına doğrudan etkilerini inceledik.
Turnuvanın istatistiksel olarak en iyi oyuncularını, ortalama ACS puanlarına göre gruplayarak detaylı bir skor tablosu ile görselleştirdik.

Model Eğitimi (AI ile MVP Tahmini)
Sadece geçmişi analiz etmekle kalmayıp geleceği de tahmin etmek istedik. Hedef değişken (Target Variable) olarak belirli bir performans barajı belirledik ve bu barajın üstünde kalan oyuncuları "Elit" olarak sınıflandırdık. Random Forest algoritmasını kullanarak; oyuncuların KDR, ADR ve HS oranlarına bakıp, o oyuncunun "takım taşıyıcısı" olup olmadığını tahmin eden bir model eğittik.

---

SONUÇ VE VİZYON
Bu proje; makine öğrenmesinin ve veri analizinin sadece finans veya sağlık gibi geleneksel sektörlerde değil, e-spor ve oyun ekosisteminde de ne kadar kritik bir güç olduğunu kanıtlamak için hazırlandı. Bilgisayar Programcılığı perspektifiyle, verinin ham ve kirli halinden, tahmin üreten bir yapay zeka modeline kadar tüm yaşam döngüsü başarıyla tamamlanmıştır.

<br>

Geliştirici: Muhammed Emin Erdem
Geliştirici Mahlası: M.Emin Erdem
Eğitim: İnönü Üniversitesi - Bilgisayar Programcılığı
Platform: (https://github.com/muhammederdem69)
