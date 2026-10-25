# Lanu Lens — OTA Distribution

**Bu depo yalnızca APK + `latest.json` + SHA256SUMS içerir.**
Kaynak kod yoktur. Kaynak kod için: https://github.com/kanunal99-jpg/LANU-GURULTU-ENGELLEYICI

## latest.json şeması

```json
{
  "schema": 1,
  "versionCode": 100,
  "versionName": "2.0.10",
  "apkUrl": "https://github.com/kanunal99-jpg/LANU-LENS-OTA/releases/download/v2.0.10-buildN/Lanu-Lens-2.0.10.apk",
  "sha256": "64-küçük-harf-hex",
  "sizeBytes": 1234567
}
```

## Kullanım

Uygulama içinden **Güncelleme Kontrol** → **Güncelleme denetle** ile kontrol edilir.

Production imzalı APK'lar bu depoya yayınlanır. Debug imzalı dosyalar buraya konmaz.

## Durum

Henüz production imzalı ilk sürüm yayınlanmadı. Keystore + GitHub Secrets kurulumu tamamlandıktan sonra otomatik yayın başlar.
