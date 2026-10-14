---
name: "compare-documents"
description: "Yüklenen belgeleri yapılandırılmış bir tabloda karşılaştırır; önemli benzerlikleri, farkları, riskleri ve takip edilecek noktaları gösterir."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Belgeleri Karşılaştır"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Genel Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Belgeleri Karşılaştır

## Talimatlar

Yüklenen belgeleri bir hukukçu ya da iş tarafı için karşılaştır. Belgeler arasında farklılaşan hükümlere, şartlara, risklere ve ticari noktalara odaklan. Karşılaştırma, yüklenen belge sayısı ne olursa olsun çalışmalıdır.

Karşılaştırmayı bir Markdown tablosu olarak hazırla. Tablo tam olarak şu sütunlardan oluşmalıdır:

- Konu
- Yüklenen her belge için bir sütun (sütun başlığı belgenin adı ya da kısa, okunaklı bir etiketi)
- Fark

Örneğin üç belge yüklendiyse tablo şu biçimde olur:

| Konu | Belge A | Belge B | Belge C | Fark |
| --- | --- | --- | --- | --- |

Belgeleri, bulunduğu ölçüde şu konularda karşılaştır:

- Taraflar ve sıfatları
- Belge tarihi ve yürürlük tarihi
- Süre, sona erme, yenileme ve uzatma hakları
- İşin, hizmetin, teslim edilecek şeylerin ya da sözleşme konusunun kapsamı
- Bedel, fiyat, ödeme koşulları, temerrüt faizi, cezai şart ve para birimi
- Ön koşullar, onaylar, izinler ve bildirimler
- Taahhütler, garantiler ve kısıtlamalar
- Gizlilik, fikrî mülkiyet, kişisel verilerin korunması ve kullanım hakları
- Devir, temlik, kontrol değişikliği ve alt yüklenici kullanımı
- Fesih ve askıya alma hakları, ihtar ve süre verme, fesih sonuçları
- Sorumluluk sınırları, tazminat, sorumsuzluk kayıtları, sigorta ve diğer hukuki çareler
- Uygulanacak hukuk, yetkili mahkeme ya da tahkim, tebligat adresleri

Belge sütunlarına kısa girişler yaz. Her girişte ilgili hükmü ve bulunabilen en iyi yeri belirt (madde, bent, ek, sayfa, paragraf ya da başlık). Yer belirsizse olabildiğince somut tarif et.

**Fark** sütununda neyin değiştiğini ya da ayrıştığını, gerektiğinde müzakere, hukuki, operasyonel ya da ticari önemiyle birlikte açıkla. Fark bir kanun hükmü bakımından önem taşıyorsa (ör. genel işlem koşulu denetimi, kesin hükümsüzlük, cezai şart) dayanak maddeyi atıfla göster.

Tablodan sonra en önemli farkları ve takip edilecek adımları özetleyen, en fazla beş maddelik kısa bir **Önemli Noktalar** bölümü ekle.

Olgu, hüküm, taraf, tarih, tutar ya da yükümlülük uydurma. Bir belgede konu düzenlenmemişse o belge için "Düzenlenmemiş" yaz. Belgeler karşılaştırılabilir değilse nedenini açıkla ve en yararlı yakın karşılaştırmayı sun.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
