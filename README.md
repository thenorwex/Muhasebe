# Serentha Villas Finans v0.2

Türkçe, mobil uyumlu fatura bazlı muhasebe prototipi.

## İçerik
- Gelir faturaları: fatura no, müşteri, tarih, kaynak, brüt, KDV, tahsilat ve alacak takibi
- Gider belgeleri: kategori, belge türü, gider uygunluğu, KDV indirimi ve ödeme takibi
- Personel maliyeti: brüt, tahmini işveren prim oranı, ek maliyet, teşvik, ödenen
- Vergi ödeme geçmişi ve yaklaşık KDV/geçici vergi/konaklama vergisi/yıllık gelir vergisi görünümü
- Aylık rapor, CSV dışa aktarma, JSON yedek/geri yükleme

## Kullanım
`index.html` dosyasını tarayıcıda açın. En iyi PWA deneyimi için HTTPS üzerinden statik hosting gerekir (ör. GitHub Pages).

## Önemli sınırlamalar
- Veriler yalnızca kullanılan tarayıcıdaki localStorage alanında tutulur. Otomatik cihazlar arası eşitleme, çok kullanıcılı oturum, sunucu veritabanı ve otomatik bulut yedeği yoktur.
- Vergi motoru tahmin amaçlıdır. Vergi dönemlerinin doğru mahsup edilmesi, KDV kapsamı, gider kabulü, konaklama vergisi, SGK teşvikleri, amortisman ve bordro maliyetleri mali müşavir tarafından doğrulanmalıdır.
- Geçici vergi ve yıllık gelir vergisi tahminleri aynı borç olarak toplanmamalıdır. Uygulama bunları ayrı bilgi kalemleri olarak gösterir.
- Bu sürüm e-Fatura/e-Arşiv sistemine bağlanmaz ve resmî muhasebe yazılımı değildir.

## Önerilen sonraki üretim adımı
Supabase/Postgres gibi bir sunucu veritabanı, kimlik doğrulama, otomatik yedekleme, audit log ve eşitleme eklenmesi; bunu yapabilmek için kullanıcı hesabı/proje oluşturma ve dağıtım onayı gerekir.
