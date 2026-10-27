# وافقري WAFQARI 3D — Android Studio

هذا المشروع يعرض لعبة وافقري المنشورة على Playabl داخل تطبيق أندرويد باستخدام WebView.
**يحتاج إلى الإنترنت**، ويعتمد على بقاء اللعبة منشورة على Playabl. لا يحتوي على كود اللعبة الأصلي.

## البناء
1. افتح Android Studio واختر Open ثم مجلد WAFQARI_Android.
2. دع Android Studio يثبت Android SDK 35 وAndroid Gradle Plugin 8.7.3 عند الطلب.
3. إذا طلب Gradle distribution، استخدم Gradle 8.9 مع JDK 17 (قد يلزم ضبطه من Settings > Build Tools > Gradle).
4. من Build اختر Build Bundle(s) / APK(s) > Build APK(s).
5. ستجد ملف APK في `app/build/outputs/apk/debug/app-debug.apk`.
6. انسخ APK إلى هاتف أندرويد وثبته.

## ملاحظات
- هذه ليست لعبة أوفلاين ولا APK جاهز؛ هذا **مشروع مصدر** لإنتاج APK.
- قد لا تعمل بعض خصائص Playabl داخل Android WebView إذا منع الموقع التضمين أو تطلب ميزات متصفح غير متوفرة.
- لم نتمكن من اختبار تشغيل اللعبة أو بناء APK في هذه البيئة.
- لم تُضف صلاحيات حساسة، ويقتصر إذن التطبيق على الإنترنت.
