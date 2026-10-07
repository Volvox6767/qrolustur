# qrolustur 📱🔗

**EN | Free QR code generator for links & WiFi — offline, no signup, never expires. Runs in your browser.**
**TR | Link ve WiFi için ücretsiz QR kod üretici — çevrimdışı, kayıtsız, süresiz. Tarayıcında çalışır.**

**▶ Open / Aç:** **https://volvox6767.github.io/qrolustur/**

Most "free" QR sites expire after 14 days, hide the download behind a login,
or track every code you make. **qrolustur is one HTML file**: the QR is
generated *inside your browser*, nothing is sent anywhere, and the code is
yours forever — static QR never expires.

Çoğu "ücretsiz" QR sitesi 14 gün sonra kodu öldürür, indirmeyi kayıt arkasına
saklar, ürettiğin her kodu takip eder. **qrolustur tek HTML dosyasıdır**: QR
*tarayıcının içinde* üretilir, hiçbir yere hiçbir şey gitmez, kod sonsuza
kadar senindir — statik QR süresizdir.

---

## 🇬🇧 English

### Features

- **Link mode** — any URL or text
- **WiFi mode** — guests scan → phone connects automatically. Print it, stick it on the wall (the famous LifeProTip)
- PNG download + print-friendly card with credit line
- Escapes special characters in passwords correctly (`;`, `:`, `\`)
- Works **fully offline** after first load — turn off your internet and try
- No account, no analytics, no expiry, no watermark

### Install (optional)

```bash
curl -LO https://raw.githubusercontent.com/Volvox6767/qrolustur/main/index.html
```

Double-click the file. Done. It loads the tiny QR engine (qrcode-generator)
from CDN when online and works from cache afterwards.

### FAQ

**Do the QR codes expire?** Never. These are static QR codes — the data lives in the pattern itself, not on a server.

**Is my link/password sent anywhere?** No. Generation happens in your browser. Verify it: open DevTools → Network — zero requests when generating.

**WiFi doesn't connect?** Some Android phones need the password *exactly* as set (case-sensitive). iOS handles WPA/WPA3 automatically.

---

## 🇹🇷 Türkçe

### Özellikler

- **Link modu** — istediğin URL veya metin
- **WiFi modu** — misafir okutur → telefon otomatik bağlanır. Bastır, duvara yapıştır (meşhur LifeProTip)
- PNG indirme + altında kredi satırı olan yazdırılabilir kart
- Şifrelerdeki özel karakterleri doğru kaçırır (`;`, `:`, `\`)
- İlk yüklemeden sonra **tamamen çevrimdışı** çalışır — interneti kapat dene
- Hesap yok, analitik yok, süre yok, filigran yok

### Kurulum (isteğe bağlı)

```bash
curl -LO https://raw.githubusercontent.com/Volvox6767/qrolustur/main/index.html
```

Dosyaya çift tıkla. Bitti. Minik QR motorunu (qrcode-generator) çevrimiçiyken
CDN'den yükler, sonrasında önbellekten çalışır.

### SSS

**Kodların süresi doluyor mu?** Asla. Bunlar statik QR — veri desensiz bir
sunucuda değil, desende yaşıyor.

**Linkim/şifrem bir yere gönderiliyor mu?** Hayır. Üretim tarayıcında olur.
Doğrula: DevTools → Network — üretim sırasında sıfır istek.

**WiFi'ye bağlanmadı?** Bazı Android telefonlar şifreyi *birebir* ister (büyük/küçük harf önemli). iOS WPA/WPA3'ü otomatik anlar.

---

Made with ❤ by **Ahmet Gedik** — [instagram.com/ahmetgedik67](https://www.instagram.com/ahmetgedik67)
Follow on Instagram for more free everyday tools.
Daha fazla ücretsiz günlük araç için Instagram'da takip edin.

License / Lisans: [MIT](LICENSE)
