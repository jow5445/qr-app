# Tiny QR Generator

QR code generator squeezed into a single HTML file.

---

### What it does

* Generates QR codes from raw text or URLs on the fly
* Supports `Enter` key shortcut & quick clear
* Zero external assets, libraries, or build steps

---

### Size & Footprint

Current uncompressed file size: **~6.26 KB**.

#### How it stays tiny
* **Single file architecture:** All HTML, CSS, and JS live directly inside `index.html`.
* **Zero dependencies:** No frameworks, UI libraries, or local icon packs.
* **Flat DOM:** Stripped down to the bare markup needed for layout and accessibility.
* **Minified build:** Cleaned up whitespace and redundant boilerplate.

---

### How to run it

```bash
git clone git@github.com:jow5445/qr-app.git
cd qr-app
```

Just double-click `index.html` or open it directly in any browser.

---

### Under the hood

QR generation is offloaded to the [QR Server API](https://goqr.me/api/):

```text
https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=YOUR_DATA
```

---

### License

MIT
