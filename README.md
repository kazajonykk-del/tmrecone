# IT Quiz Pro
200 ta test: HTML 50 + CSS 50 + Bootstrap 50 + Kompyuter savodxonligi 50.

## Muhim: Telegram token
Bot tokenini GitHub yoki frontend JavaScript ichiga yozmang. Siz chatga token yuborgansiz, shuning uchun @BotFather orqali tokenni yangilang (revoke/regenerate). Yangi tokenni faqat server environment variable sifatida saqlang.

## Vercel sozlash
1. Loyihani GitHub repo'ga yuklang.
2. Vercel'da repo'ni import qiling.
3. Environment Variables qo‘shing:
   - `TELEGRAM_BOT_TOKEN` = yangi BotFather tokeni
   - `TELEGRAM_CHAT_ID` = sizning Telegram chat ID'ingiz
4. Deploy qiling.
5. GitHub Pages faqat frontend uchun ishlatilsa, `app.js` ichidagi `/api/result` manzilini Vercel deployment URL'iga almashtiring, masalan `https://YOUR-PROJECT.vercel.app/api/result`.

## GitHub Pages
GitHub Pages static frontendni ishlatadi. Telegram tokenini frontendga qo‘yish xavfsiz emas. Bot xabar yuborishi uchun serverless endpoint kerak.
