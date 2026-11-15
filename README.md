# Adlerian Write sürümleri

Native macOS akademik yazım editörü Adlerian Write'ın kurulum dosyaları. Apple Silicon ve macOS 14 veya üzeri gerekir.

**Kurulum:** [Son sürüm](https://github.com/cyrenard/adlerian-write-releases/releases/latest) sayfasından `AdlerianWrite-<sürüm>.dmg` dosyasını indirin, içindeki uygulamayı Applications klasörüne sürükleyin. Uygulama ad-hoc imzalıdır ve Apple noterlemesi yapılmamıştır; ilk açılışta macOS geliştiriciyi doğrulayamazsa uygulamaya sağ tıklayıp Aç'ı seçin.

**Güncellemeler:** 0.16.0 ve sonrası güncellemeleri kendisi denetler (Adlerian Write > Güncellemeleri Denetle…). Her sürümde şu dosyalar bulunur:

- `AdlerianWrite-<sürüm>.dmg` — kurulum disk görüntüsü
- `AdlerianWrite-<sürüm>.dmg.sha256` — disk görüntüsünün SHA-256 özeti
- `update.json` — sürüm, yapı numarası, disk görüntüsünün boyutu ve SHA-256'sı, yenilikler
- `update.json.sig` — `update.json`'ın Ed25519 imzası

Uygulama `update.json`'ı yalnızca imzası kendi içindeki açık anahtarla doğrulanırsa okur ve yalnızca bu bilgideki özetle eşleşen disk görüntüsünü kurar.

Bu depo yalnızca sürüm dosyalarını içerir.
