
# سایت ایستا – گروه‌های آموزشی دانشگاه گیلان

این پروژه یک وب‌سایت ساده و RTL برای معرفی ۴ رشته است که می‌توانید آن را روی **GitHub Pages** منتشر کنید.

## ساختار
```
guilan-dept-site/
├── index.html
├── pages/
│   ├── computer-engineering.html
│   ├── industrial-engineering.html
│   ├── civil-engineering.html
│   └── engineering-science.html
├── assets/
│   ├── css/styles.css
│   ├── js/main.js
│   ├── img/guilan-logo.png
│   └── docs/
│       ├── chart-computer.pdf
│       ├── chart-industrial.pdf
│       ├── chart-engineering-science.pdf
│       ├── syllabus-computer.pdf
│       ├── syllabus-industrial.pdf
│       └── syllabus-engineering-science.pdf
└── .nojekyll
```

> نکته: فایل‌های فونت با CDN بارگذاری می‌شوند (Vazir/Vazirmatn). اگر خواستید می‌توانید فونت‌ها را دانلود و در `assets/fonts` بگذارید و مسیر CSS را تغییر دهید.

## انتشار روی گیت‌هاب
1. یک مخزن جدید بسازید (مثلاً `guilan-dept-site`).  
2. همهٔ فایل‌ها را در ریشهٔ مخزن کپی کنید.  
3. از تنظیمات مخزن، GitHub Pages را روی Branch: `main` و مسیر `/ (root)` قرار دهید.  
4. آدرس سایت شما بعد از چند دقیقه فعال می‌شود.  

### بروزرسانی‌ها
- **مدیر گروه‌ها**: متن داخل هر صفحه قابل ویرایش است (کافی است رشتهٔ مربوطه را باز کنید و مقدار `نام مدیر گروه` را جایگزین کنید).
- **افزودن فایل‌های عمران**: به `pages/civil-engineering.html` بروید و دکمه‌های غیرفعال را با لینک‌های واقعی (مثلاً در `assets/docs`) جایگزین کنید.
