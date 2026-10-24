# منيو المزرعة The Farm

منيو إلكتروني تفاعلي مع سلة وإرسال الطلب عبر واتساب.

## الملفات
- `index.html`: تطبيق المنيو (صفحة واحدة).
- `farm-menu.xlsx`: ملف الأسعار لاستيراده في Google Sheets.

## النشر على GitHub Pages
1. أنشئ مستودعاً جديداً على github.com (مثلاً `farm-menu`) وارفع محتويات هذا المجلد.
2. من Settings ثم Pages: اختر Branch = main والمجلد / (root) ثم Save.
3. بعد دقائق يصبح الرابط: `https://USERNAME.github.io/farm-menu/` (اعمل منه QR Code).

## ربط Google Sheets (تحديث الأسعار تلقائياً)
1. استورد `farm-menu.xlsx` في Google Sheets (ورقة Menu أولاً).
2. ملف ثم مشاركة ثم نشر على الويب ثم ورقة Menu ثم CSV، وانسخ الرابط.
3. الصقه في `index.html` داخل `const SHEET_URL=""` وارفع التعديل.

## تغيير رقم واتساب الكاشير
في `index.html` عدّل `const WA="201558138090"` (بصيغة دولية بدون + أو أصفار).
