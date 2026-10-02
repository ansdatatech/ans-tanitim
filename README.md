# ANS DataTech – Tanıtım Sayfası (Astro)

## Klasör yapısı
```
ans-datatech/
├─ public/
│  ├─ ans-logo.png       ← baykuş logosu
│  └─ favicon.png        ← tarayıcı sekmesindeki küçük ikon
├─ src/
│  ├─ layouts/
│  │  └─ BaseLayout.astro   ← <head>, yazı tipleri, renkler
│  └─ pages/
│     └─ index.astro        ← ana sayfa (içerik + stil + script)
├─ astro.config.mjs
├─ package.json
└─ tsconfig.json
```

## Çalıştırma
```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # yayına hazır dosyalar dist/ klasörüne çıkar
```

## İçerik nasıl değiştirilir?
`src/pages/index.astro` dosyasının en üstündeki `---` bloğunda
`contact`, `services`, `steps`, `showcaseFeatures` dizilerini düzenlemeniz yeterli.
