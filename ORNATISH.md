# FarmaPro 20 — o'rnatish

## Fayllar
`index.html`, `sw.js`, `manifest.json`, `icon-192.png`, `icon-512.png` — beshtasi bitta papkada turishi kerak.

## GitHub Pages'ga joylash (bepul, https)
1. github.com → **New repository** → nomi `farmapro` → Public → Create.
2. **Add file → Upload files** → 5 ta faylni tashlang → **Commit changes**.
3. **Settings → Pages** → Branch: `main`, papka: `/ (root)` → **Save**.
4. 1–2 daqiqadan keyin manzil: `https://<login>.github.io/farmapro/`
5. Telefonda shu manzilni oching → brauzer menyusi → **Uy ekraniga qo'shish**.

## Eski (v16) ma'lumotlarni ko'chirish
- Yangi `index.html` eskisi turgan **aynan o'sha manzilda** ochilsa — ma'lumotlar o'zi ko'chadi.
- Manzil boshqa bo'lsa: eski versiyada **Sozlamalar → JSON eksport** qiling, yangisida **Sozlamalar → Zaxira nusxa → Fayldan tiklash**.

## Sinxron (ikki qurilma)
Sozlamalar → Sinxron (GitHub) → token yarating (havola shu yerda) → har ikki qurilmaga **bir xil token va bir xil shifrlash parolini** kiriting.

## Havola rasmi (preview)
- `og-image.png` ni ham boshqa fayllar bilan birga yuklang — havolani Telegramga tashlaganda shu rasm chiqadi.
- GitHub repozitoriy rasmi uchun: **Settings → General → Social preview → Edit → Upload** → `og-image.png`.
- Agar Telegramda rasm chiqmasa, `index.html` ichidagi `content="og-image.png"` ni to'liq manzilga almashtiring:
  `content="https://<login>.github.io/farmapro/og-image.png"`
