# نظام إدارة مستشفيات اللوائح الخاصة (PWA)

## الرفع على GitHub Pages
1. أنشئ مستودع جديد (Repository) على GitHub.
2. ارفع كل الملفات التالية في جذر المستودع:
   - index.html
   - manifest.json
   - sw.js
   - icons/ (المجلد كامل)
3. من Settings ← Pages ← Source اختر: Deploy from a branch → main → / (root).
4. بعد دقائق يصبح الموقع متاحًا على: https://<username>.github.io/<repo-name>/

## التثبيت على الجهاز
- Chrome / Edge (كمبيوتر وأندرويد): من قائمة المتصفح اختر "Install app" أو "تثبيت التطبيق".
- Safari (iPhone / iPad): زر المشاركة ← "Add to Home Screen".

## ملاحظات
- جميع الملفات تعمل بمسارات نسبية، لذلك يعمل الموقع داخل أي مسار فرعي في GitHub Pages.
- PWA تتطلب HTTPS، وGitHub Pages يوفره تلقائيًا.
- البيانات محفوظة في localStorage داخل كل متصفح، كما كانت في الملف الأصلي.
- عند تحديث الملف مستقبلًا، غيّر CACHE_VERSION في sw.js (مثلًا إلى hospitals-lawhs-v2) ليحصل المستخدمون على النسخة الجديدة.
