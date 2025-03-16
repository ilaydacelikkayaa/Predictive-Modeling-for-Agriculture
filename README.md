# 🌱 Makine Öğrenimi ile Toprak Analizi ve Mahsul Tahmini

Bu proje, toprak ölçüm verilerini kullanarak en uygun mahsulü tahmin etmeye yönelik bir makine öğrenimi modelini kapsar. Çiftçiler için en verimli mahsul seçimini yapmak önemlidir, ancak toprağın azot (N), fosfor (P), potasyum (K) seviyeleri ve pH değeri gibi temel özelliklerini ölçmek zaman alıcı ve maliyetli olabilir. Bu proje, bu analizleri otomatize ederek çiftçilere karar süreçlerinde destek olacaktır.

## 📊 Veri Seti

Projede kullanılan **soil_measures.csv** veri seti şu sütunlardan oluşmaktadır:
- **N**: Topraktaki azot oranı
- **P**: Topraktaki fosfor oranı
- **K**: Topraktaki potasyum oranı
- **pH**: Toprak pH değeri
- **crop**: Optimum mahsul (Hedef değişken)

Her satır, belirli bir tarladaki toprak ölçüm verilerini temsil eder ve "crop" sütunu, o toprağın en uygun ürününü gösterir.

## 🔢 Amaç
Bu projede:
1. **Makine öğrenmesi tabanlı** bir **multi-class sınıflandırma modeli** geliştirilecek.
2. Toprak verileri kullanılarak **en uygun mahsulü tahmin eden** bir sistem kurulacak.
3. Modelin performansını belirleyen **en önemli özelliğini (feature importance)** belirlemek amaçlanacak.

## 🛠️ Kullanılan Teknolojiler
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Makine Öğrenimi Algoritmaları** (Lojistik Regresyon, Karar Ağaçları, Random Forest vb.)
- **Veri Görselleştirme Araçları**

## ⚡ Kurulum
Bu projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. **Gereksinimleri Yükleyin**
```bash
pip install -r requirements.txt
```

2. **Veri Setini Yükleyin**
- `soil_measures.csv` dosyasını proje dizinine ekleyin.

3. **Ana Python Dosyasını Çalıştırın**
```bash
python main.py
```

## 🎯 Model Performansı
Eğitilen modelin performansı **doğruluk (accuracy), precision, recall** gibi metriklerle değerlendirilecektir. Ayrıca, **en önemli özellik** belirlenerek modelin tahmin gücü analiz edilecektir.

---
**📢 Not:** Bu proje, tarım sektöründe karar destek sistemleri geliştirmek için bir makine öğrenimi uygulaması olarak hazırlanmıştır.
