---
name: "extract-key-terms"
description: "Yüklenen belgelerden temel hukuki, ticari ve operasyonel hükümleri yer bilgisiyle birlikte bir tabloya çıkarır."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Temel Hükümleri Çıkar"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Genel Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Temel Hükümleri Çıkar

## Talimatlar

Yüklenen belgelerden temel hukuki, ticari ve operasyonel hükümleri çıkar. Sonucu kısa bir Markdown tablosu olarak sun.

Tablo tam olarak şu sütunlardan oluşmalıdır:

- Hüküm
- İçerik
- Yer
- Notlar

Hukuki inceleme için en yararlı hükümleri, bulunduğu ölçüde çıkar:

- Taraflar ve sıfatları
- Belge tarihi ve yürürlük tarihi
- Süre, sona erme, yenileme ve uzatma hakları
- İşin, hizmetin ya da sözleşme konusunun kapsamı
- Bedel, fiyat, ödeme koşulları, temerrüt faizi, cezai şart ve para birimi
- Ön koşullar, onaylar, izinler ve bildirimler
- Taahhütler, garantiler ve kısıtlamalar
- Gizlilik, fikrî mülkiyet, kişisel verilerin korunması ve kullanım hakları
- Devir, temlik, kontrol değişikliği ve alt yüklenici kullanımı
- Fesih ve askıya alma hakları, ihtar ve süre verme, fesih sonuçları
- Sorumluluk sınırları, tazminat, sorumsuzluk kayıtları, sigorta ve diğer hukuki çareler
- Uygulanacak hukuk, yetkili mahkeme ya da tahkim, tebligat adresleri

**Yer** sütununa bulunabilen en iyi madde, bent, ek, sayfa ya da paragraf atfını yaz. Yer belirsizse olabildiğince somut tarif et. **Notlar** sütununda belirsizlikleri, eksik bilgileri, belgeler arasındaki çelişkileri ya da hükmün neden önemli olabileceğini açıkla. Bir hüküm emredici bir kanun hükmüyle çelişiyor görünüyorsa notta dayanak maddeyi atıfla belirt.

Temel bir hüküm bulunamazsa tahmini bir içerik yazma. Yalnızca hükmün yokluğu önemliyse satır ekle ve **İçerik** sütununa "Düzenlenmemiş" yaz. Olgu, atıf, hüküm, taraf, tarih, tutar ya da yükümlülük uydurma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
