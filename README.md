# وصّلها 🛵 — منصة توصيل أكل وطلبات (نسخة تجريبية)

## النشر على GitHub Pages (خطوة بخطوة)

1. اعمل حساب على github.com وسجّل دخولك
2. اعمل New Repository باسم مثل: waselha (خليها Public)
3. اضغط "uploading an existing file" وارفع ملف index.html واضغط Commit
4. من تبويب Settings ← Pages:
   - Source: اختر "Deploy from a branch"
   - Branch: main ← /(root) ← Save
5. بعد دقيقة تقريباً هيكون موقعك على:
   https://USERNAME.github.io/waselha/

## ربط الدومين الخاص بك (اختياري)

1. في نفس صفحة Settings ← Pages اكتب الدومين في "Custom domain"
   مثال: waselha.com واضغط Save
2. عند مزود الدومين أضف سجلات DNS:
   - نوع A للنطاق الرئيسي يشاور على: 185.199.108.153
     (وأيضاً 185.199.109.153 و 185.199.110.153 و 185.199.111.153)
   - أو سجل CNAME باسم www يشاور إلى: USERNAME.github.io
3. فعّل HTTPS من "Enforce HTTPS"

## الظهور على جوجل (SEO)

- ادخل موقعك على: https://search.google.com/search-console
- أضف الموقع وادعُownership برفع ملف HTML أو سجل DNS
- اطلب فهرسة الرابط: "Request Indexing"

## ملاحظات

- الموقع تجريبي: الحسابات والطلبات تُحفظ في متصفح المستخدم فقط
- للإطلاق الحقيقي ستحتاج: بوابة دفع (Tap/HyperPay)، Google Maps API، وقاعدة بيانات (Firebase/Supabase)
