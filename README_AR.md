# كشكول — Android APK عبر GitHub Actions

المشروع يحتوي على تطبيق Android يفتح `app/src/main/assets/index.html` داخل WebView، مع حفظ البيانات محليًا ودعم الروابط الخارجية.

## بناء APK

بعد رفع محتويات هذا المجلد إلى مستودع GitHub:

1. افتح **Actions**.
2. اختر **Build KashKool APK**.
3. اضغط **Run workflow**.
4. بعد انتهاء البناء افتح الـRun ثم قسم **Artifacts**.
5. نزّل `KashKool-APK` وستجد بداخله `app-debug.apk`.

يمكن أيضًا تشغيل البناء تلقائيًا عند كل `push` إلى `main`.
