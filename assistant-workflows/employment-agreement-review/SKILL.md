---
name: "employment-agreement-review"
description: "Yüklenen iş sözleşmesini, kullanıcının temsil ettiği tarafın bakış açısından tabloya dayalı olarak inceler."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "İş Sözleşmesi İncelemesi"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "İş Hukuku"
  jurisdictions: "Türkiye"
---

# İş Sözleşmesi İncelemesi

## Talimatlar

Yüklenen iş sözleşmesini incele ve kullanıcının (müvekkilin) temsil ettiği tarafın bakış açısından tabloya dayalı kapsamlı bir hukuki inceleme hazırla. Kullanıcı hangi tarafı (işveren ya da işçi) temsil ettiğini belirtmediyse incelemeye başlamadan önce bunu sor.

Temsil edilen taraf belli olduğunda tam olarak bir Markdown sonuç tablosu ver. Aşağıdaki kontrol listesine dayanarak sözleşmede bulduğun her önemli sorun için bir satır kullan ve en sona **Genel Risk Değerlendirmesi** başlıklı bir satır ekle. Tablo tam olarak şu sütunlardan oluşmalıdır:

- Sorun
- Özet
- Önerilen Değişiklik

**Özet** sütununa şu risk derecelerinden biriyle başla: Düşük, olağan ya da önemsiz bir endişedir; Orta, yönetilebilir bir müzakere konusudur; Yüksek, müzakere gerektiren önemli bir hukuki, ticari, operasyonel ya da geçerlilik sorunudur; Kritik, çözülmezse imzayı engelleyebilecek ciddi bir sorundur. Örnek: "Yüksek - rekabet yasağının süresi ve yer sınırı belirsiz".

**Özet** sütununa yalnızca kontrol listesinin **Genel** sütunundan ve temsil edilen tarafın sütunundan ilgili noktaları, mümkün olduğunda madde atıflarıyla yaz. Yalnızca karşı tarafın aleyhine olan ve temsil edilen taraf için risk yaratmayan noktaları ekleme. **Önerilen Değişiklik** sütununu temsil edilen tarafın bakış açısından yaz. Temsil edilen tarafı etkileyebilecek genel yazım hatalarını da işaretle: tutarsız tanımlar ve unvanlar, atıf ve numaralandırma hataları, tekrarlanan hükümler, eksik ekler ve iç çelişkiler. Yanıtı kısa tut; tablo dışında uzun düz yazıdan kaçın.

Bir sorun kanunun emredici bir hükmüne, kesin hükümsüzlüğe ya da genel işlem koşulları denetimine dayanıyorsa dayanak maddeyi atıfla göster ve maddeyi mevzuat arama aracıyla kontrol et.

İş Kanunu, 1475 s. K. ve İş Mahkemeleri Kanunu mikeTR veritabanında yoktur. Bu kanunlara dayanan tespitleri doğrulanmamış olarak işaretle; TBK'nın hizmet sözleşmesi hükümlerini (TBK md. 393 vd.) ise mevzuat arama aracıyla kontrol et.

## Sonuç Tablosu Biçimi

Bu tablo yapısını kullan. İlgili madde, bent, ek ya da sayfayı doğrudan **Özet** ve **Önerilen Değişiklik** sütunlarında belirt. Örnek satırlar yalnızca açıklama içindir; gerçek satırları yüklenen sözleşmeye ve temsil edilen tarafa göre hazırla.

| Sorun | Özet | Önerilen Değişiklik |
| --- | --- | --- |
| Rekabet yasağı | Yüksek - Madde [x] işçiye beş yıl süreyle Türkiye genelinde aynı sektörde çalışma yasağı getiriyor; TBK md. 444-445 uyarınca yasak kural olarak iki yılı aşamaz. | İşçi için yasağı en fazla bir yıl, belirli il ve doğrudan rakip firmalarla sınırlayın; yasak süresince bir karşılık ödenmesini önerin. |
| Cezai şart | Kritik - Madde [x] yalnızca işçi için [tutar] cezai şart öngörüyor; TBK md. 420 uyarınca hizmet sözleşmelerine sadece işçi aleyhine konulan cezai şart geçersizdir. | İşveren için cezai şartı karşılıklı hâle getirin ya da kaldırıp zararın ispatına dayalı tazminata yer verin. |

## İnceleme Kontrol Listesi

Her konu için **Genel** sütunundaki noktaları her zaman, taraf sütunlarından yalnızca temsil edilen tarafınkini uygula.

| Konu | Genel | Işveren | Işçi |
| --- | --- | --- | --- |
| Taraflar ve sözleşme türü | Tarafları, işin tanımını ve sözleşmenin belirli ya da belirsiz süreli, tam ya da kısmi süreli olduğunu belirle. Belirli süreli sözleşmenin objektif koşullara dayanması gerektiğini (İş Kanunu md. 11, veritabanında yok) not et. |  |  |
| Deneme süresi | Deneme süresini ve bu süre içindeki fesih koşullarını özetle. | Deneme süresinin olmamasını ya da çok kısa olmasını işaretle. | Kanuni üst sınırı aşan deneme süresini işaretle (İş Kanunu md. 15, doğrulanmamış). |
| Ücret ve yan haklar | Ücreti, ödeme zamanını, prim, ikramiye, kâra katılma ve yan hakları belirt (TBK md. 401, 403). | Kazanılmış hak doğurabilecek belirsiz prim taahhütlerini işaretle. | Ödenme koşulları işverenin takdirine bırakılan primleri ve ücretin ödeneceği tarihin belirsizliğini işaretle. |
| Çalışma süresi ve fazla çalışma | Çalışma süresini ve fazla çalışma ücretinin ücrete dahil sayılıp sayılmadığını belirt. | Fazla çalışmanın ücrete dahil sayılmasının yıllık sınırlarını aşmasını işaretle (Yargıtay içtihadına bak). | Fazla çalışmanın karşılıksız bırakılmasını işaretle. |
| Görev yeri ve görev değişikliği | Görev yerini ve işverenin görev ya da yer değiştirme yetkisini özetle. | Gerekli esnekliğin olmamasını işaretle. | Çalışma koşullarında esaslı değişikliğe sınırsız yetki veren hükümleri işaretle (İş Kanunu md. 22, doğrulanmamış). |
| Sadakat ve gizlilik | İşçinin özen ve sadakat borcunu ve gizlilik yükümlülüklerini özetle (TBK md. 396). | Ticari sırları korumayan zayıf gizlilik hükmünü işaretle. | Süresiz ve belirsiz kapsamlı gizlilik yükümlülüklerini işaretle. |
| Rekabet yasağı | Rekabet yasağının yazılı olup olmadığını, yer, zaman ve iş türü bakımından sınırlarını belirle. Yasak kural olarak iki yılı aşamaz ve işçinin ekonomik geleceğini hakkaniyete aykırı biçimde tehlikeye düşüremez (TBK md. 444-447). | Sınırları belirsiz olduğu için hâkimce daraltılabilecek ya da geçersiz sayılabilecek yasağı işaretle. | İki yılı aşan, geniş coğrafi kapsamlı ya da karşılıksız rekabet yasağını işaretle. |
| Cezai şart | Cezai şartları belirle. İşçi aleyhine tek taraflı konulan cezai şart geçersizdir (TBK md. 420). | Geçersizlik riski taşıyan tek taraflı cezai şartı işaretle. | İşçi aleyhine tek taraflı cezai şartı ve aşırı yüksek tutarları işaretle. |
| Eğitim gideri ve iade | İşverenin karşıladığı eğitim giderlerinin iadesine ilişkin hükümleri özetle. | İade koşullarının belirsizliğini işaretle. | Hizmet süresiyle orantılı azalmayan iade yükümlülüğünü işaretle. |
| Fesih ve ihbar | Fesih usulünü, ihbar sürelerini, haklı nedenleri ve iş güvencesi kapsamını belirt; kıdem ve ihbar tazminatı hesaplamasını etkileyen hükümleri özetle (İş Kanunu ve 1475 s. K. md. 14, doğrulanmamış). | İhbar süresini kısaltan ya da haklı nedenleri belirsiz bırakan hükümleri işaretle. | Kanuni asgarinin altında ihbar süresini ve tazminat haklarından feragat ifadelerini işaretle. |
| Kişisel veriler | Aydınlatma yükümlülüğünü (KVKK md. 10) ve özel nitelikli verilerin (sağlık raporu, biyometrik veri) işlenmesini değerlendir (KVKK md. 6). | Aydınlatma metninin ve işleme şartlarının eksikliğini işaretle. | Sözleşmeye gömülü genel açık rıza ifadelerini işaretle. |
| Uyuşmazlık çözümü | Yetkili mahkemeyi ve arabuluculuk şartını belirt; iş uyuşmazlıklarında dava şartı arabuluculuğu not et (7036 s. İş Mahkemeleri Kanunu, veritabanında yok). |  |  |

İncelemeyi sohbette, satır içinde ver. Kullanıcı açıkça istemedikçe indirilebilir bir Word belgesi oluşturma.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
