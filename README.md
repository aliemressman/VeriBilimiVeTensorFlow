# 🚀 Python ile Veri Bilimi ve Yapay Zeka (TensorFlow) Rehberi

Bu depo (repository), sıfırdan başlayıp ileri seviye Derin Öğrenme (Deep Learning) uygulamalarına kadar uzanan kapsamlı bir **Veri Bilimi ve Yapay Zeka** eğitim setidir.

Proje, temel Python programlamadan başlayarak, veri manipülasyonu, veri görselleştirme ve TensorFlow ile gerçek hayat problemlerini çözen yapay zeka modelleri geliştirmeyi hedefler.

## 📚 Müfredat ve İçerik

Bu rehber 3 ana modülden oluşmaktadır:

### 1. Modül: Python Programlama Temelleri
Yazılım geliştirmenin temelleri ve Python dilinin incelikleri:
* **Temel Yapılar:** Değişkenler, Listeler, Sözlükler (Dictionaries), Setler ve Tuple'lar.
* **Akış Kontrolü:** Döngüler (For/While), Koşullu İfadeler (If/Else).
* **Fonksiyonel Programlama:** Methodlar, Fonksiyonlar, Lambda ifadeleri ve Kapsam (Scope) yönetimi.
* **Nesne Yönelimli Programlama (OOP):** Sınıflar (Class), Miras Alma (Inheritance), Modüller ve Paket yönetimi.
* **Hata Yönetimi:** Try-Except blokları ile hata yakalama.

### 2. Modül: Veri Analizi ve Görselleştirme
Ham veriyi anlamlı bilgiye dönüştürmek için kullanılan kütüphaneler:
* **NumPy:** Çok boyutlu diziler, matris operasyonları ve bilimsel hesaplamalar.
* **Pandas:**
    * DataFrame ve Series yapıları.
    * Veri filtreleme, gruplama ve birleştirme.
    * Excel (`.xlsx`) ve CSV dosyalarından veri okuma/yazma.
    * Eksik veri (Missing Data) analizi ve temizleme.
* **Matplotlib:** Veri görselleştirme, grafik çizdirme ve özelleştirme teknikleri.

### 3. Modül: TensorFlow ile Derin Öğrenme (Deep Learning)
Yapay Sinir Ağları (ANN) mimarisi ve model geliştirme süreçleri:
* **Teori:** Nöronlar, Katmanlar (Layers), Aktivasyon Fonksiyonları (ReLU, Sigmoid vb.).
* **Model Eğitimi:** Loss fonksiyonları, Optimizerlar (Adam, RMSprop) ve Epoch kavramı.
* **Değerlendirme:** Doğruluk (Accuracy) ve Kayıp (Loss) grafiklerinin analizi, Overfitting (Aşırı Öğrenme) tespiti ve çözümleri (Dropout, EarlyStopping).

---

## 🧠 Öne Çıkan Projeler

Repo içerisinde teorik bilgilerin uygulandığı gerçek hayat projeleri yer almaktadır:

### 🚗 1. Araba Fiyat Tahmini (Regression)
* **Amaç:** İkinci el araçların özelliklerine (yıl, kilometre, motor hacmi vb.) bakarak piyasa fiyatını tahmin eden bir model geliştirmek.
* **Veri Seti:** `merc.xlsx` (Mercedes-Benz araç verileri).
* **Yöntem:** Veri temizliği yapıldıktan sonra Yapay Sinir Ağı (ANN) regresyon modeli kuruldu.
* **Sonuç:** Model, araç fiyatlarını yüksek bir doğrulukla tahmin edebilmektedir.

### 🛡️ 2. Zararlı Yazılım Tespiti (Classification)
* **Amaç:** Bir ağ trafiği veya yazılımın davranışsal verilerine bakarak "Zararlı" veya "Güvenli" olduğunu sınıflandırmak.
* **Veri Seti:** `maliciousornot.xlsx`
* **Yöntem:** Binary Classification (İkili Sınıflandırma) yapısı kullanıldı. Modelin aşırı öğrenmesini engellemek için **Dropout** ve **EarlyStopping** teknikleri uygulandı.

### 🚲 3. Bisiklet Fiyat Analizi
* **Amaç:** Bisiklet özelliklerine göre fiyat dağılımını analiz etmek.
* **Dosya:** `bisiklet_fiyatlari.xlsx`
* **Yöntem:** Pandas ve Matplotlib kullanılarak Keşifçi Veri Analizi (EDA) yapıldı.

---

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler

* **Dil:** Python 3.x
* **IDE:** Jupyter Notebook / Google Colab
* **Derin Öğrenme:** TensorFlow, Keras
* **Veri İşleme:** Pandas, NumPy
* **Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi:** Scikit-Learn (Veri ölçeklendirme ve split işlemleri için)

## 🚀 Kurulum ve Kullanım

1. Projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/kullaniciadi/VeriBilimiVeTensorFlow.git](https://github.com/kullaniciadi/VeriBilimiVeTensorFlow.git)
