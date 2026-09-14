# Belgi Arşiv — İndir

**Belgi Arşiv**, e-Logo e-belgelerini Windows bilgisayarınızda arşivlemenizi, PDF olarak görüntülemenizi ve yazdırmanızı sağlayan masaüstü uygulamasıdır.

Bu depo **indirme sayfasıdır** (README + sürüm geçmişi). Kurulum dosyaları git'te değil, **[GitHub Releases](https://github.com)** üzerinden sunulur. Kaynak kod burada yer almaz.

**Geliştirici:** [Olimpus Bilgisayar](https://www.olimpus.com.tr)

---

## Son sürüm

Sürüm **v0.8.6**
<!-- DOWNLOADS -->
| Profil | Açıklama | Dosya |
|--------|----------|-------|
| Taşınabilir (win-x64) | Tek EXE; .NET 8 runtime dahil | [BelgiArsiv-portable-win-x64.exe](https://github.com/kemalersin/belgi-arsiv/releases/download/v0.8.6/BelgiArsiv-portable-win-x64.exe) |
| Taşınabilir (win-arm64) | Tek EXE; ARM64, .NET dahil | [BelgiArsiv-portable-win-arm64.exe](https://github.com/kemalersin/belgi-arsiv/releases/download/v0.8.6/BelgiArsiv-portable-win-arm64.exe) |
| Self-contained (win-x64) | Klasör ZIP; kurulu runtime gerekmez | [BelgiArsiv-self-contained-win-x64.zip](https://github.com/kemalersin/belgi-arsiv/releases/download/v0.8.6/BelgiArsiv-self-contained-win-x64.zip) |
| Framework bağımlı (win-x64) | Klasör ZIP; .NET 8 Desktop Runtime gerekir | [BelgiArsiv-fxdep-win-x64.zip](https://github.com/kemalersin/belgi-arsiv/releases/download/v0.8.6/BelgiArsiv-fxdep-win-x64.zip) |
| Kurulum (win-x64) | Setup EXE; self-contained, Program Files kurulumu | [BelgiArsiv-setup-win-x64.exe](https://github.com/kemalersin/belgi-arsiv/releases/download/v0.8.6/BelgiArsiv-setup-win-x64.exe) |
<!-- /DOWNLOADS -->

### Profiller

| Profil | Ne zaman? |
|--------|-----------|
| **Kurulum (win-x64)** | Önerilen kurulum. Self-contained Setup; Program Files + Başlat menüsü kısayolu. |
| **Taşınabilir (win-x64)** | Tek `.exe`; .NET 8 runtime dahil. USB veya ağ paylaşımından çalıştırılabilir. |
| **Taşınabilir (win-arm64)** | Windows ARM64 cihazlar (Surface Pro X vb.). |
| **Self-contained klasör** | Kurulum programı istemeyenler; ZIP arşivini açıp `BelgiArsiv.exe` çalıştırın. |
| **Framework bağımlı** | Hedef makinede [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) yüklüyse en küçük indirme. |

---

## Sistem gereksinimleri

- Windows 10 / 11 veya Windows Server 2016 ve üzeri (64 bit)
- Framework bağımlı sürüm için: .NET 8 Desktop Runtime (x64 veya ARM64)
- e-Logo entegrasyonu için geçerli e-Logo hesabı

---

## Kurulum

1. Yukarıdaki tablodan uygun profili indirin.
2. **Kurulum (Setup):** `BelgiArsiv-setup-win-x64.exe` dosyasını çalıştırın; sihirbazı tamamlayın.
3. **Taşınabilir:** `BelgiArsiv.exe` dosyasını istediğiniz klasöre kopyalayın ve çalıştırın.
4. **ZIP (klasör):** Arşivi açın, `BelgiArsiv.exe` dosyasını çalıştırın.
5. İlk açılışta yapılandırma `%AppData%\Roaming\BelgiArsiv\` altına oluşturulur.

Windows SmartScreen uyarısı görürseniz «Yine de çalıştır» seçeneğini kullanın (imzasız veya yeni yayıncı sertifikası).

---

## Lisans

Belgi Arşiv ticari yazılımdır. Kullanım, satın alma veya deneme lisansı koşullarına tabidir. Lisans etkinleştirme uygulama içinden yapılır.

---

## Destek

Teknik destek ve lisans talepleri için Olimpus Bilgisayar ile iletişime geçin.

---

## Sürüm geçmişi

[`RELEASES.md`](./RELEASES.md) — her sürümde neler değişti. Aynı özet [GitHub Releases](https://github.com/kemalersin/belgi-arsiv/releases) sayfasında da yer alır.
