# 💞 Uyg'unlik — Moslik Ilovasi

Yoshlar uchun dunyo qarashlari va moslikni aniqlash ilovasi.

## O'rnatish

### 1. Node.js o'rnating
https://nodejs.org — LTS versiyasini yuklab o'rnating.

### 2. Loyihani oching
```bash
cd uygunlik
npm install
```

### 3. API kalitni kiriting
`index.html` faylini oching va quyidagi qatorni toping:
```js
const API_KEY = 'YOUR_API_KEY_HERE';
```
`YOUR_API_KEY_HERE` o'rniga o'zingizning kalitingizni yozing.

API kalitni bu yerdan oling: https://console.anthropic.com

### 4. Ishga tushiring
```bash
npm run dev
```
Brauzerda `http://localhost:5173` ga kiring.

## Fayl tuzilmasi
```
uygunlik/
├── index.html      ← Asosiy ilova
├── vite.config.js  ← Proxy sozlamalari
├── package.json    ← Loyiha ma'lumotlari
└── README.md       ← Shu fayl
```
