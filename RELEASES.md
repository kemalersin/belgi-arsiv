# Sürüm geçmişi

Her yayında `sync-release-repo.ps1` bu dosyaya o sürümün **kısa madde özetini** ekler.

**Ayrıntılı sürüm notları** (geliştirici `CHANGELOG.md` içeriği, kategori başlıklarıyla) [GitHub Releases](https://github.com/kemalersin/belgi-arsiv/releases) sayfasında yayınlanır. İndirilen kurulum, ZIP veya taşınabilir EXE paketlerine changelog **dahil edilmez**.

## v0.8.1

- Release yayın akışı Cursor kuralı (`.cursor/rules/release.mdc`)
- Inno Setup: aynı sürüm zaten yüklüyse kurulum atlanır (`RegQueryStringValue` + `PrepareToInstall` yedek kontrolü); `build-belgiarsiv-installer.ps1` ISS güncellenince yeniden derler, `-Force` ile zorla
- Inno Setup kurulumu yeniden çalıştırıldığında masaüstüne ikinci kısayol eklenmez; eski `.lnk` dosyaları silinip sabit ada yazılır
- PDF penceresi başlığında uzun karşı taraf adı sistem düğmelerinin (kapat vb.) üzerine taşmıyor; başlık `…` ile kısaltılır
- Ayarlar sayfası Durum infobar'ında varsayılan mesaj ile durum bildirimi arasında yükseklik kayması (gizli metin `Hidden` ile yerleşimde tutulur)
- `release-repo/RELEASES.md` giriş metni: kısa özet bu dosyada, ayrıntılı notlar GitHub Releases'ta; paketlere changelog dahil değil
- `sync-release-repo.ps1`: `RELEASES.md` her yayında `CHANGELOG.md` maddeleriyle güncellenir (yalnızca `-ReleaseNotes` ile sınırlı değildi)

## v0.8.0

- Logo ERP kapalıyken ana menüde «Satış Belgeleri» gizlenir; açıkken bağlantı yoksa Satış Belgeleri sayfalarında e-Logo tarzı uyarı çubuğu gösterilir
- Self-contained sürüm için Inno Setup kurulum paketi; `BelgiArsiv-setup-win-x64.exe`
- Yayın ve dağıtım kılavuzu; GitHub Releases üzerinden ikili dağıtım
- Logo ERP «Kaydet» / «Bağlantıyı test et» sonrası sol menünün gereksiz yeniden çizilmesi giderildi

## v0.7.0

- Lisanslama ve 7 günlük deneme
- Publish/release altyapısı, gömülü yapılandırma ve matbu şablonlar
- AppData tabanlı yazdırma ayarları

## v0.6.3

- İlk public indirme deposu yapısı.
