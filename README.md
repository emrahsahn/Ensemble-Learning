# 🎯 Ensemble Learning - Makine Öğrenmesi Algoritmaları Karşılaştırması

Bu proje, çeşitli makine öğrenmesi algoritmalarının farklı veri setleri üzerinde performanslarını karşılaştırmak ve **Ensemble Learning** (Topluluk Öğrenmesi) yöntemlerinin etkinliğini göstermek amacıyla geliştirilmiştir.

## 📋 İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Kullanılan Algoritmalar](#kullanılan-algoritmalar)
- [Veri Setleri](#veri-setleri)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Sonuçlar](#sonuçlar)
- [Gereksinimler](#gereksinimler)
- [Katkıda Bulunma](#katkıda-bulunma)

## 🎓 Proje Hakkında

Bu proje, makine öğrenmesi algoritmalarını öğrenmek ve pratik yapmak için sentetik veri setleri üzerinde çeşitli sınıflandırma algoritmalarını uygular.  Özellikle **ensemble learning** tekniklerinin tek başına çalışan algoritmalara kıyasla nasıl daha iyi performans gösterdiğini görselleştirir.

### Özellikler

- ✅ 6 farklı sınıflandırma algoritmasının karşılaştırması
- ✅ 3 farklı sentetik veri seti üzerinde test
- ✅ Karar sınırlarının görselleştirilmesi
- ✅ Train/Test skorlarının karşılaştırılması
- ✅ Ensemble yöntemlerinin performans analizi

## 🤖 Kullanılan Algoritmalar

### Temel Algoritmalar
1. **Support Vector Machine (SVC)** - Doğrusal olmayan karar sınırları için güçlü
2. **K-Nearest Neighbors (KNN)** - 15 komşu ile sınıflandırma
3. **Decision Tree** - Maksimum derinlik 2 ile basit karar ağacı

### Ensemble Yöntemleri
4. **Random Forest** - 10 karar ağacının topluluğu
5. **AdaBoost** - Adaptif artırma algoritması
6. **Voting Classifier (VL)** - Tüm algoritmaların birleşimi

## 📊 Veri Setleri

Projede kullanılan sentetik veri setleri: 

### 1. Moon Dataset
- **Örneklem Sayısı:** 2000
- **Gürültü Seviyesi:** 0.3
- **Açıklama:** Ay şeklinde iki sınıflı veri
- **Zorluk:** Doğrusal olmayan ayrım

### 2. Circle Dataset
- **Örneklem Sayısı:** 2000
- **Gürültü Seviyesi:** 0.3
- **Açıklama:** İç içe daireler
- **Zorluk:** Yüksek derecede doğrusal olmayan

### 3. Classification Dataset
- **Örneklem Sayısı:** 2000
- **Özellik Sayısı:** 10
- **Sınıf Sayısı:** 2
- **Gürültü Seviyesi:** 0.3

## 🔧 Kurulum

### Gereksinimler

- Python 3.8+
- pip paket yöneticisi

### Adımlar

1. **Projeyi klonlayın:**
```bash
git clone https://github.com/emrahsahn/Ensemble-Learning.git
cd Ensemble-Learning
```

2. **Gerekli paketleri yükleyin:**
```bash
pip install -r requirements.txt
```

## 🚀 Kullanım

Projeyi çalıştırmak için:

```bash
python src/src_code.py
```

### Çıktılar

Program çalıştığında:
- Her veri seti için algoritmaların train/test skorları konsola yazdırılır
- Karar sınırları ve sınıflandırma sonuçları görselleştirilir
- Her algoritmanın doğruluk oranı grafik üzerinde gösterilir

## 📈 Sonuçlar

Proje şu sonuçları gösterir:

- **Ensemble yöntemler** (Random Forest, AdaBoost, Voting Classifier) genellikle tek başına çalışan algoritmalara göre daha iyi performans gösterir
- **Doğrusal olmayan** veri setlerinde (Moon, Circle) SVM ve ensemble yöntemleri öne çıkar
- **Voting Classifier**, farklı algoritmaların güçlü yönlerini birleştirerek dengeli sonuçlar üretir

### Örnek Çıktı
```
Dataset # 0
SVC: test set score: 0.95
KNN: test set score:  0.92
Decision Tree: test set score: 0.88
Random Forest: test set score:  0.94
AdaBoost: test set score: 0.93
VL: test set score:  0.96
```

## 📦 Gereksinimler

Proje aşağıdaki ana kütüphaneleri kullanır:

```
numpy==2.3.3
pandas==2.3.3
matplotlib==3.10.6
seaborn==0.13.2
scikit-learn==1.7.2
scipy==1.16.2
```

Tüm gereksinimler için [requirements.txt](requirements.txt) dosyasına bakın.

## 🎯 Öğrenme Hedefleri

Bu proje ile şunları öğrenebilirsiniz:

- Scikit-learn ile makine öğrenmesi modelleri oluşturma
- Sentetik veri setleri üretme ve manipüle etme
- Model performanslarını karşılaştırma
- Karar sınırlarını görselleştirme
- Ensemble learning prensipleri
- Train/Test split ve model değerlendirme

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyorum!  Lütfen: 

1. Projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/YeniOzellik`)
5. Pull Request oluşturun

## 📝 Lisans

Bu proje açık kaynak olarak paylaşılmıştır ve eğitim amaçlı kullanıma açıktır. 

## 👨‍💻 Yazar

**Emrah Şahin** - [@emrahsahn](https://github.com/emrahsahn)
