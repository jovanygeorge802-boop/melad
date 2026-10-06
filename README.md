خِدمة

تطبيق Android/React Native لمنصة الكشافة والخدمة الكنسية.

## التشغيل

```bash
npm install
npx expo start
```

## ربط Supabase

انسخ `.env.example` إلى `.env` وضع:
- `EXPO_PUBLIC_SUPABASE_URL`
- `EXPO_PUBLIC_SUPABASE_PUBLISHABLE_KEY`

لا تضع `service_role` أو أي مفتاح سري داخل التطبيق.

## النسخة الحالية

- شاشة البداية
- تسجيل الدخول
- إنشاء حساب
- اختيار كشافة / خدمة كنسية
- الصفحة الرئيسية
- اتصال Supabase Auth جاهز

الخطوة التالية: إنشاء جداول قاعدة البيانات والصلاحيات ثم بناء المحتوى والاختبارات والأنشطة ولوحة القائد والإدارة.
