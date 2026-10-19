MMG Inc Web PWA — تعليمات مبسطة

الملفات:
- index.html: واجهة الموقع
- style.css: التصميم
- app.js: منطق التطبيق والاتصال بـ Supabase
- manifest.json و sw.js و icons: إعداد التثبيت كتطبيق PWA

مهم قبل النشر:
1) افتح app.js بمحرر نصوص.
2) استبدل PASTE_YOUR_SUPABASE_PROJECT_URL_HERE بعنوان Project URL الخاص بمشروعك.
3) استبدل PASTE_YOUR_SUPABASE_PUBLISHABLE_OR_ANON_KEY_HERE بالمفتاح العام publishable/anon فقط.
4) لا تضع service_role أو أي secret key في ملفات المتصفح.
5) احفظ الملف وارفع كل ملفات هذا المجلد إلى جذر مستودع GitHub.
6) في GitHub: Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
7) انتظر رابط Pages. بعدها افتح الرابط. في Chrome على أندرويد استخدم القائمة ⋮ ثم Install app / Add to Home screen.

قاعدة البيانات:
تم إعداد schema.sql مسبقًا وفق ما قاله المستخدم. إذا لم يتم تشغيله في Supabase، شغّل ملف schema.sql من مشروع Flutter السابق مرة واحدة من SQL Editor.

الإدارة:
- سجّل الدخول أولًا بحساب مستخدم عادي ثم افتح «إدارة الشركة».
- الرمز الافتراضي المهيأ في قاعدة البيانات: Mohamed2910.
- صلاحيات الإدارة يتم التحقق منها عبر دوال RPC في قاعدة البيانات، لا بمجرد إخفاء الواجهة.
- لا تشارك مفتاح قاعدة البيانات السري أو كلمة مرور قاعدة البيانات.

تنبيه: السعر المعروض سعر داخلي تجريبي تديره الشركة وليس سعر بورصة. طلب واتساب لا يحرك أموالًا ولا يضيف أسهمًا تلقائيًا.
