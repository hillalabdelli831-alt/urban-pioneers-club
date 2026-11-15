# URBAN PIONEERS CLUB — Website

نسخة مرتبة للعمل عليها في Visual Studio Code ثم نشرها على Vercel.

## هيكل المشروع

```text
urban-pioneers-club/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── images/
        ├── urban-pioneers-logo.png
        └── qr-code.jpg
```

## ما تم تنظيمه

- فصل الصور التي كانت مضمنة بصيغة Base64 داخل `index.html` إلى ملفات مستقلة داخل `assets/images/`.
- إزالة التكرار؛ الشعار يُستخدم من ملف صورة واحد في مواضعه المختلفة.
- ترتيب وتهيئة HTML وCSS وJavaScript لتسهيل القراءة والتعديل.
- الإبقاء على محتوى الموقع، الأقسام، النصوص، الروابط، والألعاب كما كانت دون إعادة تصميمها.

## التشغيل محلياً

1. فكّي ضغط ملف ZIP.
2. افتحي مجلد المشروع كاملاً في VS Code عبر **File → Open Folder**.
3. افتحي `index.html` ثم اختاري **Open with Live Server** (إذا كانت إضافة Live Server مثبتة).
4. بعد أي تعديل احفظي بـ `Ctrl + S` وحدّثي المتصفح.

يمكن أيضاً فتح `index.html` مباشرة في المتصفح.

## النشر على Vercel عبر GitHub

ارفعي محتويات هذا المجلد إلى جذر المستودع في GitHub، وليس ملف ZIP وحده. يجب أن يكون `index.html` في جذر المستودع. في Vercel اختاري Framework Preset: **Other**، واتركي Build Command فارغاً، ثم Deploy.

## ملاحظات

- الخط Cairo يُحمّل من Google Fonts، لذلك يحتاج اتصالاً بالإنترنت لعرض الخط الخارجي.
- لا توجد قاعدة بيانات أو لوحة إدارة في هذه النسخة.
- احتفظي بنسخة احتياطية قبل التعديلات الكبيرة.
