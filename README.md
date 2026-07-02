# Nurullah Clinic — Site Dosyaları

## Yapı

```
index.html              → Tüm sayfa içeriği (tek sayfa, çapa linkleriyle bölümler)
style.css                → Tasarım sistemi + tüm bileşen stilleri
main.js                   → Etkileşimler (menü, animasyonlar, form, video, SSS...)
assets/images/            → Tüm görseller (şu an placeholder — bkz. README.md)
assets/videos/            → Hasta hikayesi videoları (şu an boş — bkz. README.md)
scripts/generate\_placeholders.py → Placeholder görselleri yeniden üretmek için
```

## İçerik doldurma sırası (önerilen)

1. **assets/images/** klasöründeki placeholder'ları gerçek fotoğraflarınızla
değiştirin (dosya adları aynı kalmalı — detaylar için o klasördeki
README'ye bakın).
2. **assets/videos/** klasörüne hasta videolarınızı ekleyip `index.html`
içindeki ilgili `data-video-src` alanlarını doldurun.
3. **index.html** içinde şu yer tutucu metinleri kendi bilgilerinizle
değiştirin:

   * `info@nurullahclinic.com`, telefon numaraları, WhatsApp linkleri
   * Doktor isimleri / unvanları (`Dr. Placeholder Bir` vb.)
   * Otel adları ve açıklamaları
   * Dubai ofisi adresi
   * Fiyat aralığı (`pricing-range` içindeki "Fiyat aralığı buraya gelecek")
   * Footer'daki sosyal medya linkleri (`#` olan `href`'ler)
4. Blog yazıları ve "Devamını Oku" linkleri şu an `#`'e gidiyor — ileride
ayrı sayfalar oluşturursanız bu linkleri o sayfalara yönlendirin.

## Not

Bu sürüm, örnek aldığınız "Hair of Istanbul" sitesinin **sayfa mimarisini**
(mega menü, tedavi kartları, video hikayeler, klinik turu, doktor kadrosu,
otel ortaklıkları, blog, fiyatlandırma, SSS, Dubai ofisi) referans alarak
Nurullah Clinic'in altın/siyah lüks tasarımına uyarlanmıştır. Tüm metinler
özgün olarak yazılmıştır; hiçbir görsel veya metin doğrudan kopyalanmamıştır.

