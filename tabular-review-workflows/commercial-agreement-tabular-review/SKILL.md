---
name: "commercial-agreement-tabular-review"
description: "Yüklenen ticari sözleşmelerden taraflar, kapsam, bedel, sorumluluk, fesih ve uyuşmazlık çözümü gibi temel hükümleri tabloya çıkarır."
license: "MIT"
metadata:
  version: "1.0.0-tr.1"
  author: "Open Legal Products; Türkçe uyarlama: mikeTR"
  language: "Turkish"
  mike-display-name: "Ticari Sözleşme Tablo İncelemesi"
  mike-type: "tabular"
  mike-availability: "system"
  practice: "Ticari Sözleşmeler"
  jurisdictions: "Türkiye"
---

# Ticari Sözleşme Tablo İncelemesi

## Amaç

Bu iş akışıyla yüklenen belgeleri incele ve yapılandırılmış bilgiyi `table-columns.yaml` dosyasında tanımlı sütunlara çıkar.

## Talimatlar

- `table-columns.yaml` dosyasındaki her sütun sorusunu her belgeye ayrı ayrı uygula.
- Yalnızca belge metninin desteklediği bilgiyi çıkar.
- Mümkün olduğunda madde atıflarını, bölüm adlarını, tarihleri, tutarları, taraf adlarını ve tanımlı terimleri ekle.
- Yanıt verecek bilgi bulunamazsa boş bırak ya da kısaca "Bulunamadı" yaz.
- Hücreleri kısa tut ama çıkarılan bilginin işe yarar olması için yeterli bağlam ver.
- Atıf, olgu, taraf, tarih, hak, yükümlülük ya da mali sonuç uydurma.
- Tamamlanan sonuçları dışa aktarılabilir bir Excel (`.xlsx`) dosyası olarak ver. Excel çıktısı mümkün değilse sonuçları Markdown tablosu olarak ver.
## Türk hukuku

- Belgeleri Türk hukukuna göre değerlendir; bir sütun sorusu kanun hükmüne dayanıyorsa ilgili maddeyi atıfla belirt (ör. "TBK md. 344").
- Bir hükmün kanuna aykırı ya da geçersiz olabileceğini düşünüyorsan bunu hücrede kısaca not et; kesin hüküm kurma.
