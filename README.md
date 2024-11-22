
# Global Hub AI - Aygaz Veri Analizi Projesi  


Bu proje, **Global Hub AI** ve **Aygaz** iş birliğiyle gerçekleştirilen  bootcamp kapsamında hazırlanmıştır.

## 🌐 Kaggle Linki  
Projeye ait veri setine ve detaylara aşağıdaki bağlantıdan ulaşabilirsiniz:  
[Kaggle Proje Sayfası](https://www.kaggle.com/code/burakkse17/m-teri-analizi)  

## 📂 Veri Seti  
Veri seti toplamda **29 sütun** ve **336,006 satır** içermektedir. İçerdiği bazı değişkenler:  
- **Doğum yılı**  
- **Medeni durum**  
- **Eğitim durumu**  
- **Gelir**  
- **Çocuk sayısı**  
- **Kategori bazlı harcama tutarı**  
- **Kampanyaya katılma durumu**  

## 🔧 Kullanılan Kütüphaneler  
- **Pandas**: Veri manipülasyonu  
- **Seaborn**: Veri görselleştirme  
- **Matplotlib**: Grafik oluşturma  
- **Stats**: İstatistiksel analiz  

## 📑 Proje Yapısı  
Proje 5 ana bölümden oluşmaktadır:  

### 1️⃣ Veriyi Yükleme ve Veriye Ön Bakış  
- Gerekli kütüphaneler import edilmiştir.  
- Veri seti yüklenmiş ve ilk 10 ile son 10 gözlem incelenmiştir.  
- Tekrar eden satırlar kontrol edilmiştir.  
- Veri tipi yanlış olan sütunlar düzeltilmiştir.  
- Analize katkı sağlamayan sütunlar veri setinden çıkarılmıştır.  
- Proje istemi gereği eksik değerler üretilmiştir.  

### 2️⃣ Eksik Değer Analizi  
- **Sayısal sütunlar**: Eksik değerler, medyan ile doldurulmuştur.  
- **Kategorik sütunlar**: Eksik değerler, mod ile doldurulmuştur.  

### 3️⃣ İstatistiksel Analiz  
- **Temel istatistiksel metrikler**: Mod, medyan, ortalama, standart sapma hesaplanmıştır.  
- **Aykırı değer analizi**: Box-plot kullanılarak görselleştirilmiştir.  
- **Normallik testi** yapılmıştır.  
- **Çarpıklık ve basıklık değerleri** hesaplanmıştır.  

### 4️⃣ Veri Görselleştirme  
- Müşterilerin demografik özellikleri ve harcama alışkanlıkları detaylı grafiklerle görselleştirilmiştir.  

### 5️⃣ Sonuç ve Öneriler  
- Proje çıktıları değerlendirilmiştir.  
- Proje istemi gereği, kullanılabilecek makine öğrenimi algoritmaları hakkında yorumlar yapılmıştır.  

## 🎯 Projenin Amacı  
Bu proje, müşterilerin özelliklerini ve harcama davranışlarını analiz ederek iş süreçlerine yönelik içgörüler oluşturmayı amaçlamaktadır.  

