---
name: "proofread"
description: "Yüklenen belgeyi yazım kalitesi, iç tutarlılık ve biçim hataları bakımından inceler."
license: "MIT"
metadata:
  version: "1.1.0-tr.1"
  author: "Anna Guo; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Yazım ve Tutarlılık Denetimi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Genel Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Yazım ve Tutarlılık Denetimi

## Talimatlar

Yüklenen belgeyi yazım kalitesi, iç tutarlılık ve biçim hataları bakımından incele. Belge dolaşıma sokulmadan, imzalanmadan ya da mahkemeye sunulmadan önce bir hukukçunun düzeltmesi gereken sorunlara odaklan.

Bunu hızlı bir okuma değil, titiz bir denetim olarak ele al. Tutarsız numaralandırma, eskimiş atıflar, kullanılmayan tanımlar, ileri tarihli üst veriler ve gizli bağlantılar tek okumada göze çarpmaz; farklı açılardan yapılan ayrı geçişler gerektirir. **Ölçüt:** bitirdiğinde ikinci bir inceleyicinin kaçırdığın önemli bir şey bulmaması.

## Çalışma İlkeleri

- **Yalnızca metni değil, dosyayı incele.** Araçlar elveriyorsa belge dosyalarında görünen metnin yanında bağlantıları ve hedeflerini, yazı tiplerini, stilleri, yorumları ve izlenen değişiklikleri de incele. Yalnızca düz metin varsa bunu açıkça belirt ve bağlantı, yazı tipi, revizyon, yorum ve üst veri kontrollerinin yapılamadığını not et.
- **Önce haritaları çıkar, sonra denetle.** Bölüm haritası olmadan eskimiş bir atfı, tanımlar haritası olmadan kullanılmayan bir tanımı yakalayamazsın.
- **Her geçişte tek bir açıdan bak.** Aşağıdaki her kategoriyi ayrı bir geçiş olarak ele al.
- **Sessizce düzeltme, işaretle.** Kararı inceleyene bırak; belgeyi yeniden yazma.
- **Hatayı üslup tercihinden ayır.** Yazım yanlışı, var olmayan bir maddeye atıf ya da yanlış tarih gerçek hatadır. Üslup tercihi ancak kendi içinde tutarsızsa sorundur.

## 1. Adım: Çıkar ve İncele

Belge dosyalarında görünen içeriği ve olanaklı olduğunda alttaki yapıyı (paragraf metni, bağlantı hedefleri, yazı tipleri, stiller, yorumlar, izlenen değişiklikler) incele. PDF'lerde çıkarılan metni sayfa görüntüsü ve belge yapısıyla birlikte incele. Dosyanın kendisi yoksa ve yalnızca metin varsa devam et ama üst veri ve görsel düzen geçişlerinin yapılamadığını belirt.

## 2. Adım: Haritaları Çıkar

- **Taraf haritası:** Her taraf için kullanılan bütün adlar; büyük-küçük harf, noktalama ve yazılışıyla birlikte, nerede geçtiğiyle. Aynı şirketin unvanının farklı yazılışları hata işareti olabilir (ör. "A.Ş." ile "Anonim Şirketi", eksik "Ticaret" ibaresi).
- **Bölüm ve numara haritası:** Her başlık ve numarası, sırayla. Eksik, atlanan, tekrarlanan numaraları ve karışık hiyerarşiyi bul. İçindekiler varsa ayrıca karşılaştır.
- **Tanımlar haritası:** Tanımlanan her terim, nerede tanımlandığı ve sonraki kullanımları. Tutarsız yazımı, büyük harfle yazılıp tanımlanmayan terimleri ve hiç kullanılmayan tanımları bul.

## 3. Adım: Denetim Kategorileri

| Kategori | Neye bakılır | Örnek |
| --- | --- | --- |
| Tanımlar | Tanımlı terimlerin tutarlı kullanımı; büyük harfle yazılan terimlerin tanımlı olması; çelişen ya da döngüsel tanımlar; kullanılmayan tanımlar. | "Gizli Bilgi" bir kez tanımlanmış ama hiç kullanılmamış → silin ya da amaçlanan yerde kullanın. |
| Atıflar | Her madde, bent, ek ve belge atfı var olan ve doğru yeri gösteriyor mu; kanun maddesi atıfları doğru mu. | Madde 12'de "Madde 9.3'e göre" denmiş ama Madde 9'un alt bendi yok → atfı düzeltin. |
| İç tutarlılık | Şartlar, tarihler, taraflar, tutarlar, eşikler, bildirim süreleri, yükümlülükler arasında çelişki. | Madde 4'te ihtar süresi 15 gün, Madde 11'de 30 gün → birini seçin. |
| Taraflar ve unvanlar | Ticaret unvanları, MERSİS/vergi numaraları, adresler, imza yetkilileri ve sıfatlar tutarlı mı. | Girişte "ABC Yazılım A.Ş.", imza bloğunda "ABC Bilişim A.Ş." → doğru unvanı teyit edin. |
| Sayılar, tarihler, hesaplar | Tutarlar, yüzdeler, tarihler, süreler, faiz oranları; rakam ile yazının uyumu; Türk usulü yazım (14.10.2026, 150.000,00 TL). | "Yüz bin (150.000) TL" → rakam ve yazı uyuşmuyor. |
| Dil ve yazım | Yazım (TDK), dil bilgisi, noktalama, eksik ya da tekrarlanan kelimeler, yarım kalan cümleler, ek hataları ("-de/-da" ayrı yazımı). | "...telefon numarası ya da bir)" → cümle yarım kalmış. |
| Numaralandırma | Madde, bent ve ek numaraları; atlanan, tekrarlanan ya da sırasız numaralar; içindekilerle uyum. | Madde 5'ten 7'ye geçilmiş, Madde 6 yok. |
| Biçim | Başlıklar, listeler, girintiler, yazı tipleri, tablolar; görünen metinle uyuşmayan bağlantı hedefleri; kalmış yorumlar ve izlenen değişiklikler. | Görünen adres `bilgi@abc.com.tr`, bağlantı hedefi `bilgi@abc.com` → hedefi düzeltin. |

## Önem Dereceleri

- **Kritik:** Hakları, yükümlülükleri, tarafları, süreleri ya da geçerliliği esaslı biçimde değiştirebilecek hata (yanlış tüzel kişi, bildirimin yanlış adrese gitmesi, atıf düzenini bozan numaralandırma).
- **Yüksek:** Belirsizlik, müzakere sürtüşmesi ya da uygulama riski yaratması muhtemel hata (yarım cümle, sayısal çelişki, anlamı değiştiren dil bilgisi hatası).
- **Orta:** Düzeltilmesi gereken ama asıl hukuki etkiyi değiştirmesi beklenmeyen tutarlılık sorunu.
- **Düşük:** Küçük yazım, noktalama ya da biçim sorunu.

## Çıktı

Tam olarak şu sütunlardan oluşan kısa bir Markdown tablosu hazırla:

- Önem
- Kategori
- Yer
- Sorun
- Önerilen Düzeltme

**Yer** sütununa bulunabilen en iyi madde, sayfa ya da paragraf atfını yaz. **Sorun** sütununda hatayı ve neden önemli olduğunu açıkla. **Önerilen Düzeltme** sütununda somut düzeltmeyi, gerekiyorsa kısa bir öneri metniyle ver; belgenin tamamını yeniden yazma. Tabloyu önem derecesine göre (Kritik önce) sırala.

Tablodan sonra önce düzeltilmesi gereken iki ila beş noktayı listeleyen kısa bir **En Kritik Sorunlar** özeti ekle.

## Hata Sayılmayanlar

Güvenilirliği korumak için şunları işaretleme: tutarlı kullanılan üslup tercihlerini, metin gerçekten anlaşılmaz değilse cümle uzunluğunu, yalnızca senin tercihin olmayan geçerli kelime seçimlerini ve bağlamda yeterince belirli olan üst numaralı madde atıflarını. Bir şeyin hata mı tercih mi olduğundan emin değilsen bu belirsizliği belirt.

## Sonuçlandırmadan Önce

Tanımları, atıfları, numaralandırmayı, biçimi, tarafları, sayıları ve tarihleri, dili ve iç tutarlılığı ayrı ayrı ele aldığını teyit et. Önemli bir sorun yoksa bunu belirten tek satırlık bir tablo ver ve yalnızca metin sağlandığı için üst verinin incelenememesi gibi sınırlamaları not et.
