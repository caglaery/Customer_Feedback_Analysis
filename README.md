# **AI Python Zero-to-Hero: Müşteri Geri Bildirim Analiz Aracı**

## **1. Giriş**
Bu proje, bir konaklama işletmesine ait müşteri geri bildirimlerini analiz etmek için AI destekli bir sistem geliştirmeyi amaçlamaktadır.

## **2. Veri Seti**
- `guest_data_with_reviews.xlsx` dosyası, müşteri geri bildirimlerini içerir.
- Anahtar sütunlar:
  - `How likely are you to recommend us to a friend or colleague?`: Net Promoter Score (NPS) hesaplamaları için kullanılır.
  - `Review`: Metinsel geri bildirimler, duygu analizi ve konu modelleme için kullanılır.

## **3. Temel Kavramlar**
### **3.1 Net Promoter Score (NPS)**
Müşteri sadakatini ölçen bir metriktir.

- **Puanlama Sistemi:**
  - 9–10: Promoters (Destekleyenler)
  - 7–8: Passives (Tarafsızlar)
  - 0–6: Detractors (Olumsuz Yorumcular)
- **Formül:**
  \[NPS = (% Promoters) - (% Detractors)\]

### **3.2 Duygu Analizi**
Müşteri yorumlarının duygusal tonunu belirler. (Olumlu, olumsuz veya tarafsız)

### **3.3 Konu Modelleme**
Kelime gömme (word embeddings) teknikleri ile yorumlarda tekrar eden temaları belirler.

## **4. Kullanılacak Araçlar ve Kütüphaneler**
- **Python** (Ana programlama dili)
- **DataLab** (Veri analizi için)
- **Pandas** (Veri işleme için)
- **NLTK / spaCy** (Doğal dil işleme için)
- **Matplotlib / Seaborn** (Veri görselleştirme için)

## **5. Kurulum**
Projeyi çalıştırmak için şu adımları takip edin:
1. Gerekli kütüphaneleri yükleyin:
   ```sh
   pip install pandas nltk spacy matplotlib seaborn datalab
   ```
2. `guest_data_with_reviews.xlsx` dosyasını proje klasörünün içine ekleyin.
3. Python betiğini çalıştırın.

## **6. Kullanım**
1. Veriyi içe aktarın ve temizleyin.
2. NPS hesaplayın ve görselleştirin.
3. Duygu analizi yapın.
4. Konu modelleme ile öne çıkan temaları belirleyin.

## **7. Sonuç**
Bu proje ile müşteri yorumlarından anlamlı bilgiler çıkarabilir, işletme kararlarını iyileştirebilirsiniz.

