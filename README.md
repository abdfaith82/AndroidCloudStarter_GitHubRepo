# Android Cloud Build Starter (Kotlin + Jetpack Compose)

مشروع أندرويد متكامل مهيأ للبناء السحابي التلقائي عبر **GitHub Actions** باستخدام **Kotlin** و **Jetpack Compose (Material 3)** مع توافق كامل مع **Java 17**.

## المميزات
- **Jetpack Compose & Material 3:** واجهة مستخدم حديثة بالكامل.
- **Java 17 Sync:** ضبط متوافق لتفادي أخطاء تعارض JVM Target بين Java و Kotlin.
- **GitHub Actions CI/CD:** بناء ملف `app-debug.apk` تلقائياً عند كل عملية رفع (Push).

## تحميل ملف الـ APK
1. اذهب إلى تبويب **Actions** في المستودع.
2. اضغط على آخر عملية بناء ناجحة (**Android Cloud Build**).
3. قم بتحميل الملف من قسم **Artifacts** (`app-debug-apk`).
