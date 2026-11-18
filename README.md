# wildmon-updates

Wildmon oyununun güncelleme paketleri (kaynak kod burada değil).

- `latest.json`: oyunun okuduğu güncelleme bildirimi (stamp, commit, min_apk, size, md5, pck adresi).
- Paket (`wildmon.pck`) GitHub Releases'te durur. Yayın: paket `parts/` klasörüne parçalar halinde gönderilir; `.github/workflows/release.yml` birleştirir, md5 doğrular, release'e koyar ve `latest.json`'u günceller.
