# 1.6-million-UK-traffic-accidents_KizBasina

Bu proje, İngiltere, İskoçya ve Galler’deki 2000–2016 yılları arasındaki yıllık ortalama günlük trafik (AADF) verilerini analiz eder. Proje kapsamında veri ön işleme, analiz ve görselleştirme adımları gerçekleştirilmiştir.

## Kullanılan Veri Seti

- Dataset: [2000–16-traffic-flow-england-scotland-wales](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales)
- Dosya: `ukTrafficAADF.csv`
- İçerik: Araç türlerine, yolların konumuna ve bölgelere göre trafik akışı bilgileri

---

## Adımlar

### Veri Ön İşleme

- Veri kümesi pandas ile yüklendi
- Eksik değer analizi yapıldı
- `Estimation_method`, `StartJunction`, `EndJunction` gibi boş veriler içeren sütunlar temizlendi

---

## Veri Görselleştirme

Farklı araç türlerine göre yıllar içinde ortalama trafik yoğunluğu:

Bölgelere Göre Ortalama Araç Yoğunluğu

Yıllara Göre Araç Türlerinin Ortalama Günlük Trafik Değişimi

İngiltere, İskoçya ve Galler'de Trafik Yoğunluğu (AADF)

Yol Türüne Göre Ortalama Günlük Araç Sayısı (AADF)
