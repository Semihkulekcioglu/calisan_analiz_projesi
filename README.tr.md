# 📊 Çalışan Performans ve Maaş Analizi Projesi

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-purple.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

**[🇹🇷 Türkçe](#) • [🇬🇧 English](README.en.md)**

</div>

---

## 📖 Proje Hakkında

Bu proje, veri bilimi ve istatistiksel analiz becerilerimi geliştirmek amacıyla oluşturduğum kapsamlı bir **veri analizi çalışmasıdır**. 500 çalışana ait sentetik bir veri seti üzerinde, şirket çalışanlarının performans, maaş, deneyim ve diğer özelliklerini analiz ederek anlamlı içgörüler elde etmeyi hedefledim.

Projeyi, Udemy'deki **Makine Öğrenmesi ve Veri Bilimi** kursunda öğrendiğim konuları pekiştirmek ve gerçek dünya problemlerine uygulamak için geliştirdim.

## ✨ Özellikler

- 📊 **500 çalışanlı** sentetik veri seti oluşturma
- 🔍 **İstatistiksel analizler**: Ortalama, medyan, standart sapma, korelasyon
- 🧹 **Veri temizleme**: Eksik değer yönetimi ve feature engineering
- 📈 **15+ görselleştirme**: Histogram, scatter, box plot, violin plot, heatmap, pair plot
- 🎯 **Departman bazlı** karşılaştırmalar ve performans analizleri
- 🔎 **Outlier tespiti**: IQR yöntemi ile aykırı değer analizi
- 📉 **Korelasyon matrisi**: Değişkenler arası ilişki analizi
- 💼 **İş dünyası önerileri** ve yorumlamalar

## 🛠️ Kullanılan Teknolojiler

```
Python 3.8+
├── Pandas 2.0+          # Veri manipülasyonu ve analiz
├── NumPy 1.24+          # Matematiksel işlemler
├── Matplotlib 3.7+      # Veri görselleştirme
├── Seaborn 0.12+        # İleri seviye görselleştirme
└── SciPy 1.10+          # İstatistiksel hesaplamalar
```

## 📚 Öğrenilen ve Uygulanan Konular

### 1. İstatistiksel Analiz
- ✅ Merkezi eğilim ölçüleri (ortalama, medyan, mod)
- ✅ Yayılım ölçüleri (standart sapma, varyans, range)
- ✅ Korelasyon ve kovaryans analizi
- ✅ Çarpıklık (skewness) ve basıklık (kurtosis)
- ✅ Yüzdelikler (percentiles) ve çeyrekler (quartiles)

### 2. Veri Manipülasyonu (Pandas)
- ✅ DataFrame oluşturma ve yönetimi
- ✅ Eksik değer tespiti ve doldurma teknikleri
- ✅ GroupBy ile gruplama ve aggregation
- ✅ Pivot table oluşturma
- ✅ Veri filtreleme ve seçme işlemleri
- ✅ CSV okuma/yazma işlemleri

### 3. Matematiksel İşlemler (NumPy)
- ✅ Array işlemleri ve vektörizasyon
- ✅ İstatistiksel fonksiyonlar
- ✅ Veri normalizasyonu ve standardizasyonu
- ✅ Rastgele sayı üretimi

### 4. Veri Görselleştirme (Matplotlib & Seaborn)
- ✅ Histogram ve dağılım grafikleri
- ✅ Scatter plot (nokta grafikleri)
- ✅ Bar chart (çubuk grafikleri)
- ✅ Box plot (kutu grafikleri) ve outlier tespiti
- ✅ Violin plot
- ✅ Heatmap (ısı haritaları)
- ✅ Pair plot (çoklu değişken ilişkileri)
- ✅ Çoklu subplot panelleri

## 🚀 Kurulum

### 1. Repoyu Klonlayın
```bash
git clone https://github.com/Semihkulekcioglu/calisan-analiz-projesi.git
cd calisan-analiz-projesi
```

### 2. Gerekli Kütüphaneleri Yükleyin
```bash
pip install -r requirements.txt
```

### 3. Jupyter Notebook'u Başlatın
```bash
jupyter notebook
```

### 4. Notebook'u Açın ve Çalıştırın
`Calisan_Analiz_Projesi.ipynb` dosyasını açın ve hücreleri sırayla çalıştırın!

## 📊 Proje Yapısı

```
calisan-analiz-projesi/
│
├── 📓 Calisan_Analiz_Projesi.ipynb    # Ana analiz notebook'u (48 hücre)
├── 📋 requirements.txt                 # Gerekli Python kütüphaneleri
├── 📄 README.md                        # Ana dokümantasyon (dil seçimi)
├── 📄 README.tr.md                     # Türkçe dokümantasyon
├── 📄 README.en.md                     # İngilizce dokümantasyon
│
└── 📁 Çıktı Dosyaları (notebook çalıştırıldığında oluşur)
    ├── calisan_analiz_data.csv        # Analiz edilen veri seti (500 kayıt)
    ├── departman_ozet.csv              # Departman özet raporu
    └── grafik_ciktilar/                # Kaydedilen grafikler (PNG, PDF, SVG)
```

## 🎯 Analiz Adımları

### Bölüm 1: Veri Hazırlığı
1. Kütüphaneleri içe aktarma
2. 500 çalışanlı sentetik veri seti oluşturma
3. Veri setini keşfetme ve genel bilgilere ulaşma

### Bölüm 2: Veri Temizleme ve Ön İşleme
4. Eksik değerlerin tespiti ve yönetimi
5. Feature engineering (yeni değişkenler oluşturma)
6. Kategorik değişken dönüşümleri

### Bölüm 3: İstatistiksel Analizler
7. Merkezi eğilim ölçüleri hesaplama
8. Departman bazlı karşılaştırmalar
9. Korelasyon matrisi oluşturma

### Bölüm 4: Görselleştirmeler
10. Matplotlib ile temel grafikler (histogram, scatter, bar)
11. Seaborn ile ileri seviye grafikler (box, violin, heatmap)
12. Çoklu grafik panelleri oluşturma

### Bölüm 5: Outlier Analizi
13. IQR yöntemi ile aykırı değer tespiti
14. Aykırı değerlerin görselleştirilmesi

### Bölüm 6: İleri Seviye Pandas İşlemleri
15. Pivot table analizleri
16. GroupBy ile detaylı agregasyon
17. Karmaşık filtreleme örnekleri

### Bölüm 7: Numpy ile Matematiksel Dönüşümler
18. Normalizasyon ve standardizasyon
19. İstatistiksel hesaplamalar

### Bölüm 8: Sonuç ve Öneriler
20. Bulguların yorumlanması
21. İş dünyası önerileri

## 📈 Örnek Görselleştirmeler

Proje kapsamında oluşturulan grafik türleri:

| Grafik Türü | Kullanım Amacı | Kütüphane |
|-------------|----------------|-----------|
| 📊 Histogram | Dağılım analizi | Matplotlib |
| 📍 Scatter Plot | İki değişken ilişkisi | Matplotlib |
| 📊 Bar Chart | Kategori karşılaştırma | Matplotlib |
| 📦 Box Plot | Outlier tespiti | Seaborn |
| 🎻 Violin Plot | Detaylı dağılım | Seaborn |
| 🔥 Heatmap | Korelasyon matrisi | Seaborn |
| 🎨 Pair Plot | Çoklu değişken ilişkisi | Seaborn |
| 🥧 Pie Chart | Oran gösterimi | Matplotlib |

## 💡 Önemli Bulgular

### 1. Maaş Analizi
- ✅ Ortalama maaş: **~65,000 TL**
- ✅ Maaş dağılımı **sağa çarpık** (çoğu çalışan ortalamanın altında)
- ✅ Standart sapma yüksek → **Maaş eşitsizliği var**

### 2. Departman Karşılaştırmaları
- ✅ **IT departmanı** en yüksek ortalama maaşa sahip
- ✅ Departmanlar arası performans farkları **istatistiksel olarak anlamlı**
- ✅ Bazı departmanlarda **outlier oranı yüksek**

### 3. Korelasyon Bulguları
- ✅ Deneyim ve maaş arasında **güçlü pozitif korelasyon** (r > 0.8)
- ✅ Performans puanı ile maaş **orta düzeyde ilişkili**
- ✅ Eğitim saati performansı **pozitif etkiliyor**

### 4. Outlier Analizi
- ⚠️ Toplam veri setinin **%5-7'si** outlier
- ⚠️ Yüksek maaşlı pozisyonlar genellikle **senior/expert seviye**
- ⚠️ Bazı düşük performanslı çalışanlar **yüksek maaş** alıyor (inceleme gerekli)

## 🎓 Öğrenme Kaynağı

Bu proje, **Udemy - Makine Öğrenmesi ve Veri Bilimi Kursu** kapsamında öğrendiğim aşağıdaki konuları pekiştirmek için geliştirilmiştir:

- 📊 **Bölüm 4 - İstatistik Temelleri**: Merkezi eğilim, yayılım ölçüleri
- 🐼 **Bölüm 4 - Pandas**: DataFrame, GroupBy, Pivot Tables
- 🔢 **Bölüm 4 - NumPy**: Array işlemleri, matematiksel fonksiyonlar
- 📈 **Bölüm 4 - Matplotlib**: Temel görselleştirmeler
- 🎨 **Bölüm 4 - Seaborn**: İleri seviye grafikler, heatmap, pair plot
- 📦 **Bölüm 4 - Box Plot**: Outlier tespiti, IQR yöntemi

## 🔧 Gereksinimler

### Minimum Gereksinimler
- Python 3.8 veya üzeri
- pip (Python paket yöneticisi)
- Jupyter Notebook veya JupyterLab

### Python Kütüphaneleri
```
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
scipy>=1.10.0
jupyter>=1.0.0
```

## 📝 Kullanım Örnekleri

### Basit Kullanım
```python
# Jupyter Notebook'u açın ve hücreleri sırayla çalıştırın
jupyter notebook Calisan_Analiz_Projesi.ipynb
```

### Grafikleriri Kaydetme
```python
# Grafikleri otomatik kaydetmek için
import matplotlib.pyplot as plt

plt.savefig('grafik_ciktilar/grafik_adi.png', dpi=300, bbox_inches='tight')
```

### Veri Setini Okuma
```python
import pandas as pd

# Analiz sonucu oluşan veri setini okuma
df = pd.read_csv('calisan_analiz_data.csv')
print(df.head())
```

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyorum! Lütfen şu adımları izleyin:

1. Projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/YeniOzellik`)
5. Pull Request açın

## 📝 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

Kısacası: Projeyi özgürce kullanabilir, değiştirebilir ve dağıtabilirsiniz!

## 🌟 Projeyi Beğendiyseniz

Eğer bu projeyi faydalı bulduysanız:
- ⭐ **Yıldız** verin
- 🔄 **Fork** edin
- 📢 **Paylaşın**

Bu beni motive eder ve daha fazla proje geliştirmemi sağlar! 🚀

## 🙏 Teşekkürler

- **Udemy** - Kaliteli eğitim içerikleri için
- **Pandas Ekibi** - Harika bir veri analiz kütüphanesi için
- **Matplotlib & Seaborn** - Güzel görselleştirmeler için
- **GitHub** - Açık kaynak topluluğu için
  
<div align="center">

**Python ve ❤️ ile yapıldı**

![Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=Jupyter)

**[⬆ Başa Dön](#-çalışan-performans-ve-maaş-analizi-projesi)**

**[🇬🇧 Switch to English](README.en.md)**

</div>

