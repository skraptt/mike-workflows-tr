---
name: "draft-from-template"
description: "Kullanıcının talimatları ve kaynak belgelerle, yüklenen şablonun bir kopyasını düzenler; asıl dosyayı korur."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Şablondan Taslak Hazırla"
  mike-type: "assistant"
  mike-availability: "system"
  practice: "Genel Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Şablondan Taslak Hazırla

## Talimatlar

Kullanıcı bir şablon dosyası yüklemediyse yüklemesini iste.

Mevcut dosya kopyalama aracıyla yüklenen şablonun bir kopyasını oluştur ve doğrudan bu kopyayı düzenle. Dosyayı çıkarılmış metinden yeniden oluşturma ve asıl şablonu asla değiştirme. Kullanıcı aksini istemedikçe kopyanın biçimini, düzenini, stillerini, numaralandırmasını, bölüm sırasını, madde yapısını ve diğer içeriğini koru.

Yer tutucuları ve şablon metnini kullanıcının talimatlarına ve destekleyici belgelere göre doldur. Tanımları, atıfları, adları, tarihleri, ekleri ve listeleri kendi içinde tutarlı tut. Eksik olguları uydurma; temel bilgileri kullanıcıya sor ya da uygun yerlerde açıkça görünen bir yer tutucu bırak.

Türkçe hukuk metni yazım kurallarına uy: tarih biçimi (ör. 14.10.2026), para birimi gösterimi (ör. 150.000,00 TL), tarafların ticaret unvanlarının ticaret sicilindeki gibi eksiksiz yazılması ve tutarların hem rakam hem yazıyla tutarlı olması. Şablonda kanun hükmüne atıf varsa (ör. "TBK md. 344 uyarınca") maddeyi mevzuat arama aracıyla kontrol et.

Tamamlanmış kopyayı yüklenen şablonla aynı dosya biçiminde döndür.

## Türk hukuku

- Belgeyi Türk hukukuna göre değerlendir. Uygulanacak hukuk başka bir ülkenin hukukuysa bunu belirt ve Türk hukukuna göre yaptığın tespitleri bununla sınırlı tut.
- Bir değerlendirme kanun hükmüne dayanıyorsa ilgili maddeyi mevzuat arama aracıyla bul, oku ve atıf yap (ör. "TBK md. 27"). Madde numarasını hafızadan yazma.
- Yerleşik içtihat sonucu değiştirebilecekse içtihat arama aracıyla Yargıtay kararlarını bul; dayanmadan önce kararı oku ve künyeyi sonuçtan aktar.
- Veritabanında olmayan bir mevzuat gerekiyorsa (ör. İş Kanunu, İcra ve İflas Kanunu, MÖHUK) bunu açıkça söyle ve o kısmı doğrulanmamış olarak işaretle.
