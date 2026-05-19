# 🤝 دليل المساهمة | Contributing Guide

شكراً لاهتمامك بالمساهمة في مشروع **مولّد شهادات المدرسة الأثرية**!

---

## 📋 كيفية المساهمة | How to Contribute

### 1. **اقترح تحسين جديد** 💡
- افتح issue جديد
- اشرح الفكرة بوضوح
- أضف أمثلة إن أمكن

### 2. **أصلح خطأ** 🐛
- افتح issue للخطأ
- اشرح المشكلة والحل المقترح
- قدم pull request مع الإصلاح

### 3. **أضف ميزة جديدة** ✨
- ناقش الميزة أولاً في issue
- انتظر الموافقة
- قدم pull request مع الكود

---

## 🔧 خطوات العمل | Development Steps

### **1. Fork المشروع**
```bash
# انسخ المشروع إلى حسابك
```

### **2. Clone المستودع**
```bash
git clone https://github.com/YOUR_USERNAME/Athariyyah-certificate-.git
cd Athariyyah-certificate-
```

### **3. أنشئ فرع جديد**
```bash
git checkout -b feature/your-feature-name
# مثال
git checkout -b feature/add-qr-codes
```

### **4. قم بالتعديلات**
```bash
# قم بتعديل الملفات
```

### **5. اختبر التغييرات**
```bash
# اختبر المشروع محلياً
# تأكد من عدم وجود أخطاء
```

### **6. Commit التغييرات**
```bash
git add .
git commit -m "Add: وصف الميزة الجديدة"
```

### **7. Push إلى حسابك**
```bash
git push origin feature/your-feature-name
```

### **8. فتح Pull Request**
- اذهب إلى GitHub
- انقر "Compare & pull request"
- اشرح التغييرات
- انتظر المراجعة

---

## 📝 قواعد الكود | Code Style

### **التسميات:**
```javascript
// ✅ أسماء واضحة وموجزة
const certificateTemplate = "...";
function generateCertificate() {}

// ❌ تجنب الأسماء الغريبة
const ct = "...";
function gen() {}
```

### **التعليقات:**
```javascript
// استخدم تعليقات واضحة
// ✅ جيد
function calculateGrade() {
  // حساب النتيجة بناءً على المعايير
}

// ❌ سيء - بدون تعليقات
function calc() {}
```

### **التنسيق:**
```javascript
// استخدم 2 spaces للـ indentation
// صيغة واضحة وسهلة القراءة
```

---

## ✅ قائمة التحقق | Checklist

قبل فتح Pull Request، تأكد من:

- [ ] ✅ الكود يعمل بدون أخطاء
- [ ] ✅ اختبرت على متصفحات مختلفة
- [ ] ✅ أضفت تعليقات للكود المعقد
- [ ] ✅ حديثت الـ README إن لزم الأمر
- [ ] ✅ حديثت CHANGELOG.md
- [ ] ✅ لا توجد أخطاء console
- [ ] ✅ الكود يدعم العربية بشكل صحيح

---

## 🚀 أمثلة على المساهمات

### **مثال 1: إضافة ميزة QR Code**
```javascript
// قبل
downloadPDF() { ... }

// بعد
downloadPDF() { ... }
addQRCode() { ... }
```

### **مثال 2: إصلاح خطأ في عرض الخط**
```javascript
// قبل
font-family: 'Arial';

// بعد
font-family: 'Amiri', Georgia, serif;
```

---

## 📞 التواصل | Contact

- 📧 البريد: [your-email@example.com]
- 💬 WhatsApp: +234 814 658 4652
- 🐙 GitHub: @NasirTahirMuhammed

---

## 📄 الترخيص | License

بمساهمتك، توافق على أن تكون مساهمتك تحت MIT License.

---

**شكراً على المساهمة! 🙏**