# Target Pro
محلي: `python3 -m http.server 8080` داخل المجلد ثم افتح http://localhost:8080 (الـ Service Worker يحتاج localhost أو HTTPS).
نشر: Netlify Drop (اسحب المجلد على app.netlify.com/drop) أو Vercel (`npx vercel --prod`) أو GitHub Pages.
تثبيت على أندرويد: افتح الرابط في Chrome ثم اضغط "تثبيت" في الشريط أو قائمة ⋮ ← تثبيت التطبيق / إضافة إلى الشاشة الرئيسية.
أوفلاين: بعد أول تحميل ناجح يعمل التطبيق بدون إنترنت. عند صدور نسخة جديدة يظهر شريط "تحديث".
عند تعديل الملفات غيّر رقم الإصدار C في sw.js.
