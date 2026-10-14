<div align="center">

![Wintercle](docs/afis.svg)

[![Canlı demo](https://img.shields.io/badge/▶_Aç-odaklan-4fb3e0?style=for-the-badge)](https://enskygr234.github.io/wintercle/)
[![Lisans](https://img.shields.io/badge/lisans-MIT-e63946?style=for-the-badge)](LICENSE)

</div>

# ❄ Wintercle

**Kar yağışı altında sakin bir odak zamanlayıcısı.** *winter + circle*

Wintercle, tarayıcıda çalışan minimal bir pomodoro zamanlayıcısıdır. Ekranda sürekli kar yağar, süre zarif bir halka üzerinde akar, istersen arka planda yumuşak bir kış rüzgârı eser. Kurulum yok, bağımlılık yok, derleme yok.

🔗 **Canlı demo:** https://enskygr234.github.io/wintercle/

## Özellikler

- ⏱ **Pomodoro döngüsü:** Odak → kısa mola, her 4 odakta bir uzun mola
- ⭕ **Dairesel ilerleme halkası** (projenin adı buradan geliyor)
- 🌨 **Canvas kar yağışı:** yoğunluk ayarlanabilir, `prefers-reduced-motion`'a saygılı
- 🌬 **Üretilmiş ortam sesi:** Web Audio ile sentezlenen kış rüzgârı, hiç ses dosyası yok
- 🔔 Oturum bitince zil sesi ve sekme arka plandayken bildirim
- 🌐 Türkçe / English
- 💾 Ayarlar ve tamamlanan oturum sayısı tarayıcıda saklanır

## Kısayollar

| Tuş | İşlev |
| --- | --- |
| `Boşluk` | Başlat / durdur |
| `R` | Sıfırla |
| `S` | Ortam sesini aç/kapat |

## Çalıştırma

`index.html` dosyasını tarayıcıda açman yeterli. İstersen yerel sunucuyla da çalıştırabilirsin:

```bash
npx serve .
# veya
python -m http.server
```

## Yapı

```
index.html   arayüz
style.css    tasarım
app.js       zamanlayıcı, kar animasyonu, ses, i18n
```

## Lisans

[MIT](LICENSE)
