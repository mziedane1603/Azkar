طريقة تثبيت التطبيق على أندرويد:
1) ارفع محتويات هذا المجلد كما هي (index.html, manifest.webmanifest, sw.js, مجلد icons) على أي استضافة HTTPS (Netlify, GitHub Pages, Firebase Hosting...).
2) افتح الرابط من Chrome على الموبايل، ثم القائمة (⋮) > "تثبيت التطبيق" / Install app.
3) لو عاوز ملف APK حقيقي: ادخل pwabuilder.com، حط رابط موقعك، واختار Android.
عند تعديل أي ملف: غيّر رقم CACHE في sw.js (adhkar-v1 > adhkar-v2) علشان التحديث يوصل للمستخدمين.
