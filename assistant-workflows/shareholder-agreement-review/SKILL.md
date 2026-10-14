---
name: "shareholder-agreement-review"
description: "Yüklenen pay sahipleri sözleşmesini, kullanıcının temsil ettiği pay sahibinin bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Pay Sahipleri Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Şirketler Hukuku"
  jurisdictions: "Türkiye"
---

# Pay Sahipleri Sözleşmesi İncelemesi

## Talimatlar

Yüklenen pay sahipleri sözleşmesini incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (çoğunluk pay sahibi ya da azınlık pay sahibi) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

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
| Esas sözleşme ile uyum | Yüksek - Madde [x] azınlığa yönetim kurulunda bir üye seçme hakkı tanıyor ama bu hak esas sözleşmeye işlenmemiş; şirkete ve genel kurula karşı ileri sürülemeyebilir. | Azınlık pay sahibi için hakkın imtiyazlı pay ya da esas sözleşme değişikliğiyle güvenceye alınmasını ve bunun kapanış koşulu yapılmasını isteyin. |
| Satmaya zorlama | Yüksek - Madde [x] çoğunluğun asgari bir fiyat güvencesi olmadan azınlığı satışa zorlamasına izin veriyor. | Azınlık pay sahibi için satmaya zorlamayı bağımsız değerleme ile belirlenen adil değerin altında olmayan ve aynı koşullarla yapılan satışlarla sınırlayın. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Çoğunluk pay sahibi | Azınlık pay sahibi |
| --- | --- | --- | --- |
| Taraflar ve şirket | Pay sahiplerini, pay oranlarını, şirketin türünü (A.Ş. ya da Ltd. Şti.) ve sözleşmenin şirketi de bağlayıp bağlamadığını belirle. |  |  |
| Esas sözleşme ile ilişki | Pay sahipleri sözleşmesinin yalnızca taraflar arasında borç doğurduğunu, esas sözleşmeye işlenmeyen hükümlerin şirkete ve üçüncü kişilere karşı ileri sürülemeyeceğini değerlendir. A.Ş. esas sözleşmesi TTK'dan ancak izin verildiği ölçüde sapabilir (TTK md. 340). | Esas sözleşmeye işlenmesi gereken hükümlerin işlenmemesini işaretle. | Azınlık korumalarının yalnızca borçsal düzeyde kalmasını işaretle. |
| Yönetim kurulu | Yönetim kurulu üyelerini aday gösterme haklarını, toplantı ve karar nisaplarını özetle. | Çoğunluğun yönetimi kontrol edememesine yol açan hükümleri işaretle. | Azınlığa yönetim kurulunda temsil hakkı tanınmamasını işaretle. |
| Önemli kararlar ve veto | Ağırlaştırılmış nisap ya da veto gerektiren konuları belirle. | İşletmenin olağan yönetimini kilitleyecek geniş veto haklarını işaretle. | Sermaye artırımı, birleşme, esas sözleşme değişikliği ve ilişkili taraf işlemleri için veto olmamasını işaretle. |
| Pay devri kısıtlamaları | Devir yasaklarını, önalım ve onay haklarını belirt. Nama yazılı payların devrinin esas sözleşmeyle sınırlandırılabileceğini ve şirketin önemli sebeple onaydan kaçınabileceğini dikkate al (TTK md. 490, 493). |  |  |
| Önalım, birlikte satış ve satmaya zorlama | Önalım (ROFR/ROFO), birlikte satış (tag-along) ve satmaya zorlama (drag-along) haklarını ve fiyat belirleme usulünü özetle. | Çıkış işlemini engelleyen birlikte satış ve önalım haklarını işaretle. | Birlikte satış hakkının olmamasını ve satmaya zorlamada adil değer güvencesi olmamasını işaretle. |
| Sermaye artırımı ve sulanma | Rüçhan haklarını ve sulanmaya karşı koruma hükümlerini belirle. | Gelecek finansmanı zorlaştıran ağır sulanma korumasını işaretle. | Rüçhan hakkının kısıtlanabilmesini ve sulanma korumasının olmamasını işaretle. |
| Kâr payı politikası | Kâr dağıtım politikasını ve yedek akçe ayrılmasını özetle. | Bağlayıcı yüksek kâr dağıtım taahhüdünü işaretle. | Kâr dağıtımının tamamen çoğunluğun takdirine bırakılmasını işaretle. |
| Bilgi alma ve denetim | Pay sahiplerinin bilgi alma ve inceleme haklarını belirt. | Rakip pay sahibine hassas bilgi verilmesini işaretle. | Kanuni bilgi alma hakkının ötesinde düzenli raporlama olmamasını işaretle. |
| Rekabet yasağı ve gizlilik | Pay sahiplerinin rekabet yasağı ve gizlilik yükümlülüklerini, süre ve kapsamıyla değerlendir. | Yönetici pay sahipleri için rekabet yasağı olmamasını işaretle. | Azınlık pay sahibinin diğer yatırımlarını kısıtlayan geniş yasakları işaretle. |
| Kilitlenme ve çıkış | Kilitlenme (deadlock) çözüm yöntemlerini, karşılıklı alım-satım (shotgun) ve halka arz gibi çıkış yollarını özetle. | Belirsiz kilitlenme çözümünü işaretle. | Azınlığın finansal gücünü dikkate almayan karşılıklı alım-satım mekanizmasını işaretle. |
| Cezai şart ve uygulanabilirlik | Sözleşmeye aykırılık yaptırımlarını, cezai şartları ve oy anlaşmalarının uygulanabilirliğini değerlendir (TBK md. 179-182). | Etkili bir yaptırım olmamasını işaretle. | Orantısız cezai şartları işaretle. |
| Uygulanacak hukuk ve uyuşmazlık çözümü | Uygulanacak hukuku, yetkili mahkemeyi ya da tahkimi belirt; HMK md. 412 tahkim şartını kontrol et. |  |  |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
