# Tabib IQ Backend

منصة طبيب - الخادم الخلفي

## 🚀 التثبيت والتشغيل

### المتطلبات
- Node.js (الإصدار 16 أو أحدث)
- npm أو yarn
- MongoDB

### التثبيت
```bash
npm install
```

### إعداد متغيرات البيئة
انسخ ملف `env.example` إلى `.env` وعدل القيم:
```bash
cp env.example .env
```

### التشغيل في بيئة التطوير
```bash
npm run dev
```

### التشغيل في بيئة الإنتاج
```bash
npm start
```

## 🌐 النشر على Railway/Render

1. اربط هذا المجلد بـ Railway أو Render
2. أضف متغيرات البيئة المطلوبة:
   - `NODE_ENV`: `production`
   - `PORT`: `10000`
   - `MONGO_URI`: رابط قاعدة البيانات MongoDB
   - `JWT_SECRET`: مفتاح JWT آمن
   - `CORS_ORIGIN`: رابط الواجهة الأمامية

## 📁 هيكل المشروع

```
├── server.js          # الملف الرئيسي
├── package.json       # التبعيات
├── env.example        # مثال متغيرات البيئة
├── uploads/           # الملفات المرفوعة
└── ...
```

## 🔧 التقنيات المستخدمة

- Node.js
- Express.js
- MongoDB
- Mongoose
- Multer
- bcryptjs
- CORS

## 📞 الدعم

للمساعدة التقنية، يرجى التواصل مع فريق التطوير. 