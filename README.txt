SERENTHA VILLAS FINANS v0.4

Bu sürüm yerel test içindir. Veriler tarayıcının localStorage alanında saklanır; cihazlar arası eşitleme ve sunucu veritabanı yoktur.

DEĞİŞİKLİKLER
1) Personel modülünde banka hesabına yatan net ücret girilir. Uygulama tahmini brüt ücret, çalışan SGK/işsizlik payı, gelir vergisi kesintisi, damga vergisi, işveren primleri, SGK'ya tahmini toplam ödeme, muhtasar kesintisi ve toplam işveren maliyetini hesaplar.
2) Gelir faturası ekranından ayrı “tahsil edilen” alanı kaldırıldı. Girilen fatura toplamı gelir kaydı olarak tutulur; banka/tahsilat ayrı bir giriş değildir.
3) Kısmen uygun giderlerde başlangıç tahmini %50 olarak hesaplanır. Bu oran bir varsayımdır, mevzuat kararı değildir.

KULLANIM
- ZIP'i çıkarıp index.html dosyasını aç.
- Ayarlar & yedek bölümünden sık sık JSON yedeği al.
- Test kayıtları gerçek mali müşavir kayıtlarıyla doğrulanmadan kesin vergi borcu kabul edilmemelidir.

PERSONEL HESAPLAMA NOTU
Netten brüte hesaplama yaklaşık bordro simülasyonudur. Varsayılanlar: işçi SGK %14, işçi işsizlik %1, 2026 asgari ücret vergi istisnası için başlangıç değerleri, seçilebilir gelir vergisi dilimi ve işveren prim oranı. Kümülatif vergi matrahı, eksik gün, fazla mesai, BES/icra kesintileri, özel teşvikler ve kişisel durumlar hesaba tam olarak dahil değildir. SGK ve GİB'ye ait resmi bordro/ödeme tutarı yerine geçmez.


Sürüm 0.4 değişiklikleri:
- Gelir faturasında ayrı tahsil edilen alanı yoktur. Bankaya gelen tutara ilişkin fatura bir kez kaydedilir.
- Personel formunda bankaya yatan net maaştan brüt ve işveren maliyeti tahmini yapılır.
- HTML dosyası ve servis çalışanı önbellek sürümü güncellendi.
