# 🌙 DreamDecoder

> AI dream interpreter

Decode your dreams with AI — symbolism, emotional tone, subconscious messages, and reflection prompts across cultural lenses.

## ✨ Features

- 5 cultural lenses: western, Chinese, Jungian, Freudian, spiritual
- Symbolism, emotional tone, dream type classification
- Reflection questions and subconscious message
- Action suggestions grounded in the dream
- Mystical-but-grounded UI vibe
- Multi-language UI (English / 中文)
- BYOK Xiaomi MiMo API support with free Pollinations fallback
- Zero dependencies, single-file HTML

## 🚀 Quick Deploy

### Vercel (drag-drop, paling cepat)
1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag folder `dreamdecoder/` ke area drop
3. Klik Deploy. URL hidup dalam 30 detik.

### Local
```bash
cd dreamdecoder
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Setup MiMo API Key (recommended)

1. Klik **⚙** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Test Connection → Save

Tanpa API key, app pakai Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- Single-file HTML, vanilla JS, zero dependencies
- Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- localStorage untuk settings, no server

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com)

## 📄 License

MIT — fork, modify, gunakan komersial bebas.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
