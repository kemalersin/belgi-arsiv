# Sürüm geçmişi

Belgi Arşiv sürümlerinde neler değişti — kısa özet.

İndirilen kurulum, ZIP veya taşınabilir EXE paketlerine bu liste **dahil edilmez**.

## v0.8.6

- Ayarlar → WhatsApp mesaj şablonları: Meta'da kayıtlı şablonları listeleme, seçilenleri programa çekme ve Meta'dan silme
- WhatsApp gönderim diyaloğu, kişi adı yazılırken genişliği değiştirmiyor; sabit 480px kullanılıyor
- Koyu modda DatePicker takvim popup arka planı şeffaf görünüyordu; opak yüzey rengi kullanılıyor
- Meta şablon silme, onay diyaloğu açılınca kapanan veritabanı bağlamı yüzünden hata veriyordu
- WhatsApp şablon doğrulaması «{{Karşı Taraf}}, {{Belge No}}» gibi virgülle ayrılmış değişkenleri yanlışlıkla yan yana sayıyordu
- Meta'dan silinen şablon Ayarlar listesinden hemen kalkmıyordu
- Matbu PDF sorgu düzenleme diyaloğunda SQL kod renklendirmesi koyu temada açık tema renklerini kullanıyordu; koyu palete uyarlandı
- Windows başlangıcında arka planda açılışta görev çubuğu simgesi ekran dışındaki pencereyi göstermiyordu; tepsi veya görev çubuğundan pencere görünür alana taşınıyor
- WhatsApp gönderim diyaloğunda kişi adı alanı en fazla 50 karakter ile sınırlandı

## v0.8.5

- Lisans aktivasyon penceresinde XML metin alanı kaldırıldı; yalnızca dosyası seçimi kullanılıyor
- Lisans aktivasyon penceresinde kopyala ve dosya seç düğmeleri, Ayarlar’daki gibi giriş alanı içi simge düğme olarak gösteriliyor
- Lisans aktivasyon penceresi, Splash/Hakkında kart düzeni ve Ayarlar form etiketleriyle yeniden düzenlendi; hata mesajları durum bandı olarak gösteriliyor
- Lisans aktivasyon penceresinde FluentWindow çerçevesi kaldırıldı; Splash/login ile aynı çerçevesiz panel görünümü kullanılıyor
- Lisans aktivasyon paneline diyalog gölgesi eklendi
- Splash/login ve bootstrap uyarı panellerine uygulandı; bootstrap uyarı penceresi çerçevesiz panel görünümüne alındı
- Splash, login ve lisans panellerinde kenarlık kaldırıldı; yalnızca gölge kullanılıyor
- Hakkında diyalog kartında kenarlık kaldırıldı

## v0.8.4

- Ana pencere title bar açıklama cümlesi birkaç saniye sonra yalnızca uygulama adına döner
- Uygulama yapılandırması artık yalnızca kod varsayılanları ve SQLite tablosundan okunuyor; gömülü dosyası ve AppData kopyası kaldırıldı
- (kaynak, gömülü kaynak ve AppData bootstrap akışı)

## v0.8.3

- Belge sayfaları araç çubuğunda simge düğmeleri Filtrele düğmesinin gerçek yüksekliğine bağlandı; son (önizleme) düğmesinin sağındaki fazla boşluk giderildi
- Ana pencere title bar'ında uygulama adının yanında kısa açıklama cümlesi gösterilir
- GitHub Releases notları artık tam CHANGELOG yerine ile aynı son kullanıcı özetini kullanır

## v0.8.2

- Ayarlar: WhatsApp mesaj şablonları listesi boşken CardExpander altındaki gereksiz boşluk giderildi

## v0.8.1

- Inno Setup: aynı sürüm zaten yüklüyse kurulum atlanır
- Inno Setup kurulumu yeniden çalıştırıldığında masaüstüne ikinci kısayol eklenmez; eski `.lnk` dosyaları silinip sabit ada yazılır
- PDF penceresi başlığında uzun karşı taraf adı sistem düğmelerinin (kapat vb.) üzerine taşmıyor; başlık `…` ile kısaltılır
- Ayarlar sayfası Durum infobar'ında varsayılan mesaj ile durum bildirimi arasında yükseklik kayması giderildi

## v0.8.0

- Logo ERP kapalıyken ana menüde «Satış Belgeleri» gizlenir; açıkken bağlantı yoksa Satış Belgeleri sayfalarında e-Logo tarzı uyarı çubuğu gösterilir
- Self-contained sürüm için Inno Setup kurulum paketi
- Logo ERP «Kaydet» / «Bağlantıyı test et» sonrası sol menünün gereksiz yeniden çizilmesi giderildi

## v0.7.0

- Lisanslama ve 7 günlük deneme
- AppData tabanlı yazdırma ayarları

## v0.6.3

- İlk kamuya açık indirilebilir sürüm
