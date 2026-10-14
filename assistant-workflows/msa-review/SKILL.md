---
name: "msa-review"
description: "Yüklenen hizmet çerçeve sözleşmesini, kullanıcının temsil ettiği tarafın bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Hizmet Çerçeve Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Ticari Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Hizmet Çerçeve Sözleşmesi İncelemesi

## Talimatlar

Yüklenen hizmet çerçeve sözleşmesini (MSA) incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (hizmet alan ya da hizmet sağlayan) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

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
| Sorumluluk sınırı | Yüksek - Madde [x] hizmet sağlayanın toplam sorumluluğunu son üç ayın bedeliyle sınırlıyor ve ağır kusuru da sınırın içinde tutuyor; TBK md. 115 uyarınca ağır kusurdan sorumsuzluk kaydı kesin hükümsüzdür. | Hizmet alan için üst sınırı yıllık bedele çıkarın; kast, ağır kusur, gizlilik ve veri ihlallerini sınırın dışında tutun. |
| Fikrî mülkiyet | Orta - Madde [x] teslim edilenlerin mülkiyetini devrediyor ama FSEK'in aradığı biçimde hakları tek tek saymıyor. | Hizmet alan için devredilen mali hakları (işleme, çoğaltma, yayma, temsil, umuma iletim) ayrı ayrı sayın; süre ve yer sınırı olmadığını yazın. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Hizmet alan | Hizmet sağlayan |
| --- | --- | --- | --- |
| Sözleşmenin niteliği | Sözleşmenin hukuki niteliğini belirle: eser sözleşmesi (TBK md. 470), vekâlet (TBK md. 502), karma ya da isimsiz sözleşme. Nitelik, uygulanacak hükümleri ve fesih haklarını değiştirir. |  |  |
| Kapsam ve sipariş belgeleri | Hizmetlerin kapsamını, sipariş ya da iş emri yapısını ve çerçeve sözleşme ile sipariş belgeleri arasındaki öncelik sırasını özetle. | Belirsiz kapsamı, kapsam dışı işler için ek bedel kapısını ve sipariş belgelerinin çerçeve sözleşmeyi aleyhe değiştirebilmesini işaretle. | Açık uçlu yükümlülükleri ve kapsam değişikliği için bedel ayarlaması olmamasını işaretle. |
| Hizmet seviyeleri ve kabul | Hizmet seviyesi taahhütlerini, ölçüm yöntemini, hizmet kredilerini ve teslim edilenlerin kabul usulünü özetle. | Ölçülemeyen hizmet seviyelerini, tek çare olarak sınırlanan hizmet kredilerini ve zımni kabulü işaretle. | Ulaşılamaz hizmet seviyelerini, sınırsız kredileri ve süresiz kabul testlerini işaretle. |
| Bedel ve ödeme | Bedeli, faturalama, ödeme süresi, fiyat artışı ve KDV dahil olup olmadığını belirt. Temerrüt faizi ve ticari işlerde faiz serbestisini (TTK) dikkate al. | Tek taraflı fiyat artışını ve belirsiz masraf kalemlerini işaretle. | Uzun ödeme sürelerini, mahsup ve ödeme durdurma haklarını işaretle. |
| Fikrî mülkiyet | Teslim edilenler, önceden var olan haklar ve lisans kapsamını belirle. FSEK'e göre mali hakların devrinin yazılı ve tek tek gösterilerek yapılması gerektiğini dikkate al. | Hizmet alana gereken hakların devredilmemesini ya da lisansın dar olmasını işaretle. | Önceden var olan araçların ve genel bilgi birikiminin de devredilmesini işaretle. |
| Gizlilik ve kişisel veri | Gizlilik yükümlülüklerini ve kişisel veri işleniyorsa veri sorumlusu ve veri işleyen rollerini, KVKK md. 12 veri güvenliği yükümlülüklerini ve yurt dışına aktarımı (KVKK md. 9) belirle. | Veri güvenliği, alt işleyen ve ihlal bildirimi hükümlerinin eksikliğini işaretle. | Sınırsız denetim hakkını ve hizmet sağlayanın kontrolü dışındaki ihlallerden sorumluluğu işaretle. |
| Garantiler | Hizmetin özenle ve mesleki standartlara uygun yapılacağına ilişkin taahhütleri ve ayıba karşı tekeffülü özetle. | Garantilerin kısa süreli ya da yalnızca yeniden ifa ile sınırlı olmasını işaretle. | Belirsiz sonuç garantilerini işaretle. |
| Sorumluluk sınırları | Sorumluluk üst sınırını, dolaylı zarar istisnasını ve sınır dışı tutulan hâlleri belirle. Kast ve ağır kusurdan sorumsuzluk kaydının kesin hükümsüz olduğunu (TBK md. 115) dikkate al. | Hizmet alanın zararını karşılamayacak kadar düşük üst sınırı işaretle. | Sınırsız sorumluluğu ve dolaylı zararların sınır dışı tutulmamasını işaretle. |
| Tazminat ve üçüncü kişi talepleri | Fikrî mülkiyet ihlali ve üçüncü kişi taleplerine karşı tazmin yükümlülüklerini özetle. | Fikrî mülkiyet ihlal tazmininin olmamasını işaretle. | Hizmet alanın kendi talimatından doğan talepleri de kapsayan tazmini işaretle. |
| Süre ve fesih | Süreyi, yenilemeyi, haklı nedenle ve bildirimle fesih haklarını ve ihtar sürelerini belirt. | Hizmet alanın bildirimle fesih hakkı olmamasını ve fesihte devir ve geçiş desteği olmamasını işaretle. | Kısa bildirimle sebepsiz fesih ve fesihte ödenmemiş bedellerin belirsizliğini işaretle. |
| Alt yüklenici ve devir | Alt yüklenici kullanımını, devir ve kontrol değişikliği hükümlerini özetle. | Onaysız alt yüklenici kullanımını işaretle. | Bağlı şirketlere devri bile engelleyen kısıtlamaları işaretle. |
| Uygulanacak hukuk ve uyuşmazlık çözümü | Uygulanacak hukuku ve yetkili mahkemeyi ya da tahkimi belirt; HMK md. 17 ve md. 412 şartlarını kontrol et. |  |  |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
