---
name: "dpa-review"
description: "Yüklenen veri işleme sözleşmesini KVKK'ya göre, kullanıcının temsil ettiği tarafın bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Victor Wang; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Veri İşleme Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Veri Koruma"
  jurisdictions: "Türkiye"
---

# Veri İşleme Sözleşmesi İncelemesi

## Talimatlar

Yüklenen veri işleme sözleşmesini incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (veri sorumlusu ya da veri işleyen) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

Temsil edilen taraf belli olduğunda tam olarak bir Markdown sonuç tablosu ver. Aşağıdaki kontrol listesine dayanarak sözleşmede bulduğun her önemli sorun için bir satır kullan ve en sona **Genel Risk Değerlendirmesi** başlıklı bir satır ekle. Tablo tam olarak şu sütunlardan oluşmalıdır:

- Sorun
- Özet
- Önerilen Değişiklik

**Özet** sütununa şu risk derecelerinden biriyle başla: Düşük, olağan ya da önemsiz bir endişedir; Orta, yönetilebilir bir müzakere konusudur; Yüksek, müzakere gerektiren önemli bir hukuki, ticari, operasyonel ya da geçerlilik sorunudur; Kritik, çözülmezse imzayı engelleyebilecek ciddi bir sorundur. Örnek: "Yüksek - rekabet yasağının süresi ve yer sınırı belirsiz".

**Özet** sütununa yalnızca kontrol listesinin **Genel** sütunundan ve temsil edilen tarafın sütunundan ilgili noktaları, mümkün olduğunda madde atıflarıyla yaz. Yalnızca karşı tarafın aleyhine olan ve temsil edilen taraf için risk yaratmayan noktaları ekleme. **Önerilen Değişiklik** sütununu temsil edilen tarafın bakış açısından yaz. Temsil edilen tarafı etkileyebilecek genel yazım hatalarını da işaretle: tutarsız tanımlar ve unvanlar, atıf ve numaralandırma hataları, tekrarlanan hükümler, eksik ekler ve iç çelişkiler. Yanıtı kısa tut; tablo dışında uzun düz yazıdan kaçın.

Bir sorun kanunun emredici bir hükmüne, kesin hükümsüzlüğe ya da genel işlem koşulları denetimine dayanıyorsa dayanak maddeyi atıfla göster ve maddeyi mevzuat arama aracıyla kontrol et.

## Sonuç Tablosu Biçimi

Bu tablo yapısını kullan. İlgili madde, bent, ek ya da sayfayı doğrudan **Özet** ve **Önerilen Değişiklik** sütunlarında belirt. Örnek satırlar yalnızca açıklama içindir; gerçek satırları yüklenen sözleşmeye ve temsil edilen tarafa göre hazırla.

| Sorun | Özet | Önerilen Değişiklik |
| --- | --- | --- |
| İhlal bildirimi | Yüksek - Madde [x] veri işleyene ihlali 'makul süre içinde' bildirme yükümlülüğü getiriyor; veri sorumlusunun Kurula bildirim yükümlülüğü (KVKK md. 12/5) bakımından bu süre belirsiz. | Veri sorumlusu için ihlalin öğrenilmesinden itibaren en geç 24 saat içinde, ihlalin kapsamını ve alınan önlemleri içeren bir bildirim şart koşun. |
| Yurt dışına aktarım | Kritik - Madde [x] verilerin ABD'deki sunucularda tutulmasına izin veriyor ama yeterlilik kararı ya da KVKK md. 9'daki uygun güvencelerden hiçbiri öngörülmemiş. | Veri sorumlusu için standart sözleşmenin imzalanmasını ve Kurula bildirimini aktarım öncesi şart olarak ekleyin. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Veri sorumlusu | Veri işleyen |
| --- | --- | --- | --- |
| Roller | Tarafların veri sorumlusu ve veri işleyen rollerini KVKK md. 3 tanımlarına göre belirle; ortak veri sorumluluğu ihtimalini değerlendir. | Veri işleyenin kendi amaçları için de veri işlemesine imkân veren belirsiz rolleri işaretle. | Veri işleyene veri sorumlusu yükümlülükleri yükleyen hükümleri işaretle. |
| İşlemenin konusu ve amacı | İşlenen veri kategorilerini, ilgili kişi gruplarını, amaçları ve süreyi özetle; özel nitelikli veri varsa KVKK md. 6 şartlarını değerlendir. | Amacın belirsiz ve geniş olmasını işaretle. | Veri sorumlusunun talimatlarının belirsiz bırakılmasını işaretle. |
| Talimatlarla bağlılık | Veri işleyenin yalnızca veri sorumlusunun talimatıyla işleme yapacağını ve hukuka aykırı talimatları bildireceğini belirt. | Talimat dışı işleme yasağının olmamasını işaretle. | Hukuka aykırı talimatlara uyma yükümlülüğünü işaretle. |
| Veri güvenliği | Teknik ve idari tedbirleri değerlendir; veri sorumlusu ile veri işleyenin bu tedbirlerden müştereken sorumlu olduğunu dikkate al (KVKK md. 12/2). | Asgari tedbirlerin tanımlanmamasını işaretle. | Ölçüsüz ya da teknik olarak uygulanamaz tedbirleri işaretle. |
| İhlal bildirimi | Veri ihlallerinin veri işleyen tarafından veri sorumlusuna bildirim süresini ve içeriğini belirt; veri sorumlusunun Kurula ve ilgili kişilere bildirim yükümlülüğünü (KVKK md. 12/5) ve Kurulun 72 saatlik bildirim kararını (doğrulanmamış) dikkate al. | Kurul süresine uyulmasını imkânsız kılan geç bildirim süresini işaretle. | Belirsiz ya da gerçekçi olmayan kısa bildirim süresini işaretle. |
| Alt işleyenler | Alt işleyen kullanımı için onay usulünü, itiraz hakkını ve alt işleyenin aynı yükümlülüklerle bağlanmasını özetle. | Onaysız alt işleyen kullanımını işaretle. | Her alt işleyen için ayrı yazılı onay gibi işleyişi kilitleyen şartları işaretle. |
| Yurt dışına aktarım | Yurt dışına aktarım olup olmadığını; yeterlilik kararını ya da KVKK md. 9'daki uygun güvenceleri (standart sözleşme ve Kurula bildirimi, bağlayıcı şirket kuralları vb.) belirle. | Aktarım için hukuki dayanak ve standart sözleşme bildiriminin olmamasını işaretle. | Veri işleyenin kendi altyapısındaki zorunlu aktarımları yasaklayan hükümleri işaretle. |
| İlgili kişi hakları | KVKK md. 11 başvurularında veri işleyenin desteğini ve başvuruların otuz gün içinde sonuçlandırılmasını (KVKK md. 13) değerlendir. | Destek yükümlülüğünün olmamasını işaretle. | Ücretsiz ve sınırsız destek yükümlülüğünü işaretle. |
| Denetim | Veri sorumlusunun denetim ve bilgi alma haklarını özetle. | Denetim hakkının olmamasını işaretle. | Sınırsız, habersiz ve masrafı veri işleyene yüklenen denetimleri işaretle. |
| Silme ve iade | Sözleşme sonunda verilerin silinmesini, yok edilmesini ya da iadesini (KVKK md. 7) ve saklama istisnalarını belirt. | Silme ve iade yükümlülüğünün olmamasını işaretle. | Kanuni saklama yükümlülükleri için istisna olmamasını işaretle. |
| Sorumluluk | KVKK ihlallerinden doğan sorumluluğu, idari para cezalarının rücuunu ve sorumluluk sınırlarını değerlendir. | Veri işleyenin ihlallerinden doğan cezalar için rücu imkânı olmamasını işaretle. | Sınırsız sorumluluğu ve veri sorumlusunun kendi ihlallerinden de sorumlu tutulmayı işaretle. |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
