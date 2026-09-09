# Yayın dosyaları

**Varsayılan:** Kurulum EXE ve ZIP dosyaları bu git deposunda **tutulmaz**. İndirme yalnızca [GitHub Releases](https://github.com) sayfasından yapılır; ana `README.md` tablosundaki linkler oraya yönlendirir.

Dosyalar ana geliştirme deposundaki `scripts/sync-release-repo.ps1` ile `publish/belgiarsiv/` çıktısından hazırlanır ve `gh release upload` ile yüklenir.

## İsteğe bağlı: dosyaları repoda da tutmak

Eski LFS modeli için senkron script'ine `-CopyToRepo` ekleyin. Bu durumda `releases/v{X.Y.Z}/` altına kopyalanır ve git'e commit edilir (önerilmez).
