# Trafik İşaretlerinin Evrişimli Sinir Ağları (CNN) ile Sınıflandırılması 🚦

Bu proje, **İstanbul Topkapı Üniversitesi - FET312 Derin Öğrenme** dersi kapsamında, **GTSRB (German Traffic Sign Recognition Benchmark)** veri seti kullanılarak trafik işaretlerini tanıyan özgün CNN modelleri geliştirmek amacıyla hazırlanmıştır.

## 👥 Proje Ekibi
* **Ramazan Bozkurt** - Base Model A (Batch Norm CNN)
* **Ömer Utku Aktemur** - Base Model B (Simple CNN)

## 🎯 Proje Özeti
Proje kapsamında, hazır (pre-trained) modeller yerine kendi tasarladığımız sığ (shallow) CNN mimarileri kullanılmıştır. İki farklı yaklaşım test edilmiştir:
1. **Model A:** Batch Normalization ve Dropout katmanları içeren 3 katmanlı CNN yapısı. (**%98 Doğruluk**)
2. **Model B:** Daha hafif (lightweight), hesaplama maliyeti düşük 2 katmanlı CNN yapısı. (**%94 Doğruluk**)

## 🛠️ Kullanılan Teknolojiler
* **Dil:** Python 3.8+
* **Framework:** PyTorch
* **Kütüphaneler:** Pandas, NumPy, OpenCV, Matplotlib, Seaborn, Scikit-learn

## 📊 Sonuçlar
Modellerimiz test veri seti üzerinde yüksek başarı oranlarına ulaşmıştır. Detaylı performans metrikleri ve karmaşıklık matrisleri (confusion matrix) rapor dosyasında mevcuttur.
