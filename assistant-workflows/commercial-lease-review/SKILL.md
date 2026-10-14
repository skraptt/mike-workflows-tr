---
name: "commercial-lease-review"
description: "Yüklenen işyeri kira sözleşmesini, kullanıcının temsil ettiği tarafın bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "İşyeri Kira Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Gayrimenkul"
  jurisdictions: "Türkiye"
---

# İşyeri Kira Sözleşmesi İncelemesi

## Talimatlar

Yüklenen işyeri kira sözleşmesini incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (kiraya veren ya da kiracı) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

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
| Kira artışı | Yüksek - Madde [x] her yıl %40 sabit artış öngörüyor; TBK md. 344 uyarınca artış bir önceki kira yılının TÜFE on iki aylık ortalamasını geçemez, aşan kısım geçersizdir. | Kiracı için artışı TÜFE on iki aylık ortalamasıyla sınırlayın; beşinci yıldan sonrası için hakkaniyet belirlemesini saklı tutun. |
| Güvence | Orta - Madde [x] altı aylık kira tutarında nakit depozito istiyor; TBK md. 342 uyarınca güvence üç aylık kirayı aşamaz ve vadeli hesaba yatırılmalıdır. | Kiracı için güvenceyi üç aylık kirayla sınırlayın ve iki tarafın onayı olmadan çekilemeyecek bir vadeli hesaba yatırılmasını şart koşun. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Kiraya veren | Kiracı |
| --- | --- | --- | --- |
| Kiralanan ve kullanım amacı | Kiralananı, eklentilerini ve kullanım amacını belirle. Çatılı işyeri kiralarında TBK md. 339 vd. koruyucu hükümlerinin uygulanacağını not et. | Belirsiz kullanım amacını ve kiracıya fazla geniş kullanım serbestisini işaretle. | Faaliyeti engelleyecek dar kullanım amacını işaretle. |
| Süre ve yenileme | Süreyi ve yenilemeyi belirt. Kiracı bildirimde bulunmazsa sözleşmenin aynı koşullarla bir yıl uzayacağını ve kiraya verenin süre bitimine dayanarak sözleşmeyi sona erdiremeyeceğini dikkate al (TBK md. 347). | On yıllık uzama süresinden sonraki fesih imkânının değerlendirilmemesini işaretle. | Kanuni korumayı dolanmaya yönelik hükümleri işaretle. |
| Kira bedeli ve artış | Kira bedelini, ödeme zamanını ve artış oranını belirt. Yenilenen dönemlerde artış TÜFE on iki aylık ortalamasını geçemez; beş yıldan sonra hâkim hakkaniyete göre belirleyebilir (TBK md. 344). Yabancı para üzerinden kira kararlaştırılmasına ilişkin güncel kısıtlamaları (doğrulanmamış) not et. | Kanuni sınırı aşan ve bu nedenle aşan kısmı geçersiz olacak artış hükmünü işaretle. | Kanuni sınırı aşan artışı ve kiracı aleyhine kira dışı değişiklikleri (TBK md. 343) işaretle. |
| Güvence (depozito) | Güvencenin tutarını ve saklanma biçimini belirt. Güvence üç aylık kirayı aşamaz ve vadeli bir tasarruf hesabına yatırılır (TBK md. 342). | Güvencenin bankaya yatırılmamasından doğan riskleri işaretle. | Üç ayı aşan güvenceyi ve nakit olarak kiraya verene ödenmesini işaretle. |
| Bağlantılı sözleşmeler | Sözleşmenin kurulmasının kiracının başka bir sözleşme yapmasına bağlanıp bağlanmadığını belirle; bu tür bağlantı kiracı aleyhine kesin hükümsüzdür (TBK md. 340). |  | Kiracıyı kiraya verenin belirlediği tedarikçilerle sözleşmeye zorlayan hükümleri işaretle. |
| Bakım, onarım ve giderler | Kiralananın bakımını, onarım sorumluluğunu, yan giderleri ve vergi ile aidat paylaşımını özetle. | Esaslı onarımların kiraya verene yüklenmesini işaretle. | Kiraya verenin olağan ve esaslı onarım yükümlülüklerinin kiracıya aktarılmasını işaretle. |
| Tadilat ve tesisat | Kiracının tadilat yapma hakkını, izin usulünü ve sözleşme sonunda iade durumunu belirt. | İzin olmadan tadilat yapılmasını işaretle. | Yapılan faydalı masrafların karşılıksız kalmasını işaretle. |
| Alt kira ve devir | Alt kiraya verme ve kira ilişkisinin devrini belirt; işyeri kiralarında kiraya verenin haklı sebep olmadıkça devre rıza göstermekten kaçınamayacağını dikkate al (TBK md. 323). | Kontrolsüz devri işaretle. | İşletmenin devrini engelleyen mutlak yasakları işaretle. |
| Temerrüt ve tahliye | Kira bedelinin ödenmemesinde yazılı süre verme ve fesih usulünü (TBK md. 315, çatılı işyerinde en az otuz gün) ve iki haklı ihtar nedeniyle tahliyeyi (TBK md. 352) özetle. Tahliye taahhütnamesi varsa geçerlilik koşullarını değerlendir. | Kanuni usulle uyumsuz, uygulanamayacak fesih hükümlerini işaretle. | Kanuni süreleri kısaltan ve kiracının ihtarsız temerrüde düşeceğini öngören hükümleri işaretle. |
| Cezai şart | Cezai şartları belirle. Kiracının borçlarını zamanında ödememesi hâlinde ceza ya da muacceliyet öngörülmesinin geçersizliğini değerlendir (TBK md. 346). | Geçersizlik riskini işaretle. | Kira borcuna bağlanmış cezai şart ve muacceliyet kayıtlarını işaretle. |
| Sigorta ve risk | Kiralananın ve faaliyetin sigortalanmasını, hasar ve risk paylaşımını özetle. | Kiracının sorumluluk sigortası yükümlülüğünün olmamasını işaretle. | Kiracının kusuru olmayan hasarlardan sorumlu tutulmasını işaretle. |
| Uyuşmazlık çözümü | Yetkili mahkemeyi ve icra dairesini belirt; kira uyuşmazlıklarında sulh hukuk mahkemesinin görevli olduğunu ve dava şartı arabuluculuğu (doğrulanmamış) not et. |  |  |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
