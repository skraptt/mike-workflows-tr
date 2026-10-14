---
name: "nda-review"
description: "Yüklenen gizlilik sözleşmesini, kullanıcının temsil ettiği tarafın bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Gizlilik Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Genel Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Gizlilik Sözleşmesi İncelemesi

## Talimatlar

Yüklenen gizlilik sözleşmesini (NDA) incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (bilgiyi açıklayan taraf ya da bilgiyi alan taraf) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

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
| Gizli bilginin tanımı | Orta - Madde [x] yazılı belgeleri kapsıyor ama sözlü açıklamaları açıkça düzenlemiyor. | Açıklayan taraf için sözlü ve görsel açıklamaları da ekleyin; bunların belirli bir süre içinde yazılı olarak teyit edilmesini öngörün. |
| Cezai şart | Yüksek - Madde [x], her ihlal için [tutar] cezai şart ve ayrıca tüm zararların tazminini öngörüyor; TBK md. 179 uyarınca bunun ifa ile ilişkisi belirsiz. | Alan taraf için cezai şartı makul bir tutarla sınırlayın ve cezai şartın ödenmesinin ayrıca tazminat isteme hakkını ortadan kaldırıp kaldırmadığını açıkça yazın. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Bilgiyi açıklayan taraf | Bilgiyi alan taraf |
| --- | --- | --- | --- |
| Taraflar | Her tarafı ve sıfatını belirle. Sözleşmenin karşılıklı mı tek taraflı mı olduğunu ve yükümlülüklerin doğru dağıtıldığını teyit et. |  |  |
| Amaç | Gizli bilginin hangi amaçla kullanılabileceğini özetle. | Amacın, işlem dışında kullanıma izin verecek kadar geniş olmasını işaretle. | Amacın, işlemle ilgili meşru kullanımı engelleyecek kadar dar ya da belirsiz olmasını işaretle. |
| Gizli bilginin tanımı | Korunan bilgiyi açıkla: sözlü, görsel, türetilmiş ve önceden paylaşılmış bilgi dahil mi. | Sözlü ya da işaretlenmemiş bilgiyi kapsamayan dar tanımları işaretle. | Kamuya açık ya da gerçekte hassas olmayan bilgiyi de yakalayan aşırı geniş tanımları işaretle. |
| İstisnalar | Kamuya açık, bağımsız geliştirilen, önceden bilinen ve üçüncü kişiden kısıtlamasız alınan bilgi istisnalarını belirle. | Alan tarafın yükümlülükten kolayca kurtulmasına yol açan istisnaları işaretle. | Eksik standart istisnaları ya da ispatı çok zor istisnaları işaretle. |
| Gizlilik yükümlülükleri | Gizlilik yükümlülüklerini, özen ölçüsünü ve kullanma ve açıklama yasaklarını özetle. | Bilgiyi yeterince korumayan zayıf özen ölçüsünü işaretle. | Kusursuz sorumluluk, belirsiz özen ölçüsü ya da kendi bilgisine gösterdiğinden yüksek özen yükümlülüğünü işaretle. |
| Bilgiye erişebilecek kişiler | Çalışanlar, bağlı şirketler, danışmanlar ve finansman sağlayanlar gibi bilgiyi alabilecek kişileri belirle. | Fazla geniş alıcı kategorilerini ya da alıcıların eşdeğer yükümlülükle bağlanmamasını işaretle. | İşlemin değerlendirilmesi için gereken danışman, bağlı şirket ya da finansman sağlayan erişiminin eksikliğini işaretle. |
| Alıcıların ihlalinden sorumluluk | Alan tarafın, bilgiyi paylaştığı kişilerin ihlalinden sorumlu olup olmadığını belirt (TBK md. 116 yardımcı kişilerin fiillerinden sorumluluk). | Bu sorumluluğun bulunmamasını işaretle. | Doğrudan kontrolü dışındaki kişiler için sınırsız sorumluluğu işaretle. |
| Zorunlu açıklama | Kanun, mahkeme kararı ya da düzenleyici kurum (ör. SPK, KVKK Kurulu) gereği açıklamayı özetle. | Bildirim hakkı ya da işbirliği yükümlülüğü olmamasını işaretle. | Uygulanamayacak kadar ağır bildirim ya da direnme yükümlülüklerini işaretle. |
| Süre | Sözleşmenin süresini ve gizlilik yükümlülüklerinin ne kadar devam ettiğini belirt. | Yükümlülüklerin erken sona ermesini ya da sözleşme bitiminden sonra devamının belirsizliğini işaretle. | Ticari sır niteliği taşımayan bilgi için süresiz ya da olağandışı uzun süreleri işaretle. |
| İade ve imha | İade, imha, saklama ve arşiv kopyası yükümlülüklerini özetle; kişisel veri içeren bilgide KVKK md. 7 silme ve yok etme yükümlülüğünü de dikkate al. | İade yükümlülüğünün olmamasını ya da imha usulünün yetersizliğini işaretle. | Arşiv, uyum, yedekleme ya da yasal saklama kopyaları için istisna olmamasını işaretle. |
| Cezai şart ve tazminat | Cezai şart, tazminat ve ihtiyati tedbir gibi hukuki çareleri belirle. Cezai şartın TBK md. 179-182 kapsamında ifa ile ilişkisini ve hâkimin indirim yetkisini değerlendir; tacirler arasında indirim yasağını (TTK md. 22) dikkate al. | Etkili bir cezai şart ya da tedbir imkânı olmamasını işaretle. | Aşırı yüksek cezai şartı, ceza ile birlikte ayrıca tazminat istenebilmesini ve otomatik tedbir ifadelerini işaretle. |
| Devir | Sözleşmenin devrine ilişkin kısıtlamaları özetle. | Yükümlülüklerin bilinmeyen kişilere devrine imkân veren serbest devri işaretle. | İşlem süreci için gereken bağlı şirket devirlerini engelleyen kısıtlamaları işaretle. |
| Uygulanacak hukuk ve uyuşmazlık çözümü | Uygulanacak hukuku, yetkili mahkemeyi ya da tahkimi belirt. Yetki sözleşmesinin HMK md. 17, tahkim şartının HMK md. 412 şartlarını karşıladığını kontrol et. |  |  |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
