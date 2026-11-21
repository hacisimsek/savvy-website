# Savvy website

Savvy iOS uygulamasının App Store için gereken herkese açık sayfaları: gizlilik politikası, destek ve `app-ads.txt`.

Saf HTML ve CSS; derleme adımı yok. Yerelde bakmak için:

```bash
python3 -m http.server 8765
```

## Yayından önce

- `privacy/index.html` ve `support/index.html` içindeki `destek@ornek.com` adresini gerçek destek adresiyle değiştir.
- `app-ads.txt` içindeki `pub-0000000000000000` değerini AdMob yayıncı kimliğiyle değiştir.
- `app-ads.txt` alan adının kökünde olmalı, bu yüzden siteyi özel bir alan adıyla yayınla.
- Gizlilik metni, Savvy reposundaki `AppStore/privacy-policy.md` ve uygulamadaki `PrivacyPolicyView` ile aynı tutulmalı.
