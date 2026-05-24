# 🚀 دليل رفع عقاري CRM

## الملفات المطلوبة للرفع:
```
📁 المشروع/
├── index.html              ← الصفحة الرئيسية (redirect)
├── real-estate-crm.html   ← التطبيق الرئيسي
├── manifest.json           ← إعدادات PWA
└── sw.js                   ← Service Worker
```

---

## الخطوة 1: إعداد Firebase 🔥

1. اذهب إلى: https://firebase.google.com
2. اضغط "Get Started" وسجل بـ Google
3. اضغط "Create Project" → اسم المشروع: "aqari-crm"
4. من القائمة الجانبية → Build → Firestore Database
5. اضغط "Create Database" → اختر "Start in test mode"
6. من ⚙️ Settings → Project Settings → Your Apps → اضغط </>  (Web)
7. انسخ الـ firebaseConfig وضعه في الملف بدل YOUR_API_KEY إلخ

---

## الخطوة 2: رفع على Netlify 🌐

1. اذهب إلى: https://netlify.com
2. سجل حساب مجاني
3. اضغط "Add new site" → "Deploy manually"
4. اسحب مجلد المشروع كله وحطه في المربع
5. ✅ جاهز! هتحصل على رابط مثل: https://aqari-crm.netlify.app

---

## الخطوة 3: تثبيت كتطبيق 📱

### آيفون:
1. افتح الرابط في Safari
2. اضغط زر المشاركة (Share) ⬆️
3. اختر "Add to Home Screen"
4. ✅ يظهر كتطبيق!

### أندرويد:
1. افتح الرابط في Chrome
2. ستظهر نافذة "Install App" تلقائياً
3. أو: القائمة ⋮ → "Add to Home Screen"
4. ✅ يظهر كتطبيق!

---

## Firestore Collections المطلوبة:
- `leads` - العملاء
- `appointments` - المواعيد  
- `properties` - العقارات
