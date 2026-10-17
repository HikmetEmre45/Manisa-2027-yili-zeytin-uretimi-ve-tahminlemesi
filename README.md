# 🫒 Manisa İli Zeytin Üretimi ve 2027 Yılı Tahminleme Modeli

Bu proje; Türkiye'nin ve Ege Bölgesi'nin en önemli zeytin üretim merkezlerinden biri olan **Manisa** ilinin ilçe bazlı geçmiş zeytin üretim verilerini analiz etmek, yıllık trendleri keşfetmek ve makine öğrenimi / zaman serisi regresyon modelleri kullanarak **2027 yılı üretim projeksiyonunu** tahmin etmek amacıyla geliştirilmiştir.

---

## 📊 Proje Özeti ve Kapsam

- **Çalışma Alanı:** Manisa İli ve İlçeleri (Akhisar, Salihli, Saruhanlı, Turgutlu, Kırkağaç, Soma, Şehzadeler, Yunusemre vb.)
- **Amaç:** Geçmiş yıllara ait üretim hacimleri, meyve veren/vermeyen ağaç sayıları ve verim dalgalanmalarını (var yılı / yok yılı döngüleri) inceleyerek 2027 yılı için il geneli ve ilçe düzeyinde güvenilir rekolte tahminleri oluşturmak.
- **Hedef Kitle:** Veri analistleri, tarım ekonomisi araştırmacıları ve bölgesel tarım planlamacıları.

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

- **Programlama Dili:** Python 3.x
- **Veri Manipülasyonu & Analiz:** `pandas`, `numpy`
- **Veri Görselleştirme:** `matplotlib`, `seaborn`
- **Makine Öğrenimi & Modelleme:** `scikit-learn` (Lineer Regresyon, Polinomal Regresyon, Trend Modellemesi)
- **Geliştirme Ortamı:** Google Colab / Jupyter Notebook

---

## 🔬 Metodoloji ve İş Akışı

1. **Veri Toplama ve Ön İşleme (Data Preprocessing):**
   - İlçe bazlı yıllık zeytin üretim verilerinin entegrasyonu.
   - Eksik (null) ve aykırı değerlerin tespiti ve temizlenmesi.
   - Sayısal veri tiplerinin dönüştürülmesi ve standartlaştırılması.

2. **Keşifçi Veri Analizi (Exploratory Data Analysis - EDA):**
   - İl genelindeki toplam üretimde en yüksek paya sahip ilçelerin tespiti (başta Akhisar ve çevresi olmak üzere).
   - Zeytin tarımındaki periyodisite (var yılı / yok yılı periyotları) etkisinin zaman serisi grafikleriyle görselleştirilmesi.
   - Yıllık büyüme ve azalış oranlarının hesaplanması.

3. **Modelleme ve Tahminleme (Predictive Modeling):**
   - Geçmiş yılların trend analizi ve regresyon katsayılarının çıkarılması.
   - Zaman parametresi bağımsız değişken olarak ele alınarak 2027 yılı rekolte projeksiyonunun modellenmesi.
   - Model başarı metriklerinin ($R^2$, MAE, RMSE) değerlendirilmesi.

---

## 📈 Öne Çıkan Bulgular

- **Lider İlçeler:** Akhisar, Saruhanlı ve Salihli ilçeleri Manisa'nın toplam zeytin üretiminin büyük bir çoğunluğunu sırtlamaktadır.
- **Dönemsel Dalgalanma:** Üretim grafikleri incelendiğinde iklim koşulları ve ağaç fizyolojisine bağlı belirgin periyotlar gözlemlenmiştir.
- **2027 Projeksiyonu:** Model çıktıları, modern tarım uygulamaları ve ağaç varlığı trendiyle birlikte 2027 yılı için dengeli bir üretim artışı potansiyeline işaret etmektedir.

---

## 💻 Kurulum ve Çalıştırma

Projeyi yerel makinenizde veya Google Colab üzerinde çalıştırmak için:

```bash
# Repoyu klonlayın
git clone [https://github.com/HikmetEmre45/Manisa-2027-yili-zeytin-uretimi-ve-tahminlemesi.git](https://github.com/HikmetEmre45/Manisa-2027-yili-zeytin-uretimi-ve-tahminlemesi.git)

# Gerekli Python kütüphanelerini yükleyin
pip install pandas numpy matplotlib seaborn scikit-learn
