# wdgroup3


English Learning Platform

📌 معرفی پروژه

این پروژه یک پلتفرم آموزش زبان انگلیسی است که با هدف کمک به کاربران برای یادگیری زبان، ارزیابی سطح و دسترسی به بخش‌های مختلف آموزشی طراحی می‌شود.

پروژه شامل بخش‌های مختلفی مانند صفحه اصلی، صفحات آموزشی، تمرین‌ها، طراحی ظاهری، JavaScript و فایل‌های رسانه‌ای خواهد بود.

---
🏗️ معماری پروژه

ساختار اصلی پروژه به صورت زیر در نظر گرفته شده است:

English-Learning-Platform/
│
├── index.html
│
├── pages/
│   ├── placement-test.html
│   ├── roadmap.html
│   ├── lessons.html
│   ├── practice.html
│   └── profile.html
│
├── css/
│   ├── style.css
│   └── responsive.css
│
├── js/
│   ├── main.js
│   ├── placement-test.js
│   ├── roadmap.js
│   ├── lessons.js
│   ├── practice.js
│   └── profile.js
│
├── assets/
│   ├── images/
│   └── icons/
│
├── components/
│
└── README.md

---

👥 تقسیم بخش‌های پروژه

هر عضو مسئول یک بخش کامل از پروژه است و در Branch مربوط به خودش روی همان بخش کار می‌کند.

👤 1. نگین تاجی

مسئول: صفحه اصلی

index.html

Branch:

feature/home

---

👤 2. ریحانه انصاری

مسئول: تمام صفحات اصلی سایت

pages/

شامل صفحات:

placement-test.html
roadmap.html
lessons.html
practice.html
profile.html

Branch:

feature/pages

---

👤 3. کسرا پرویزی

مسئول: استایل و طراحی ظاهری سایت

css/

شامل:

style.css
responsive.css

Branch:

feature/css

---

👤 4. نیما سازگار

مسئول: JavaScript پروژه

js/

شامل فایل‌های JavaScript مربوط به بخش‌های مختلف پروژه.

Branch:

feature/javascript

---

👤 5. طاها طیب

مسئول: تصاویر و فایل‌های تصویری

assets/images/

Branch:

feature/images

---

👤 6. ثنا آقاسی

مسئول: آیکون‌ها و اجزای رابط کاربری

assets/icons/
components/

Branch:

feature/components

---

👤 7.#نرکس_عبادی

مسئول: ساختار و آماده‌سازی بخش تمرین‌ها

practice/

Branch:

feature/practice

«این بخش می‌تواند در ادامه شامل فایل‌ها و ساختارهای مربوط به تمرین‌ها باشد.»

---

🌿 ساختار Branchها

پروژه دارای سه نوع Branch اصلی است:

"main"

نسخه نهایی و پایدار پروژه است.

main

این Branch نباید مستقیماً توسط اعضای گروه تغییر داده شود.

---

"develop"

Branch اصلی برای جمع شدن کار اعضای گروه است.

develop

بعد از بررسی کار هر عضو، تغییرات Branch او به "develop" منتقل می‌شود.


هر عضو یک Branch اختصاصی دارد:

feature/home
feature/pages
feature/css
feature/javascript
feature/images
feature/components
feature/practice

هر عضو ابتدا روی Branch خودش کار می‌کند و تغییرات خود را همان‌جا Commit و Push می‌کند.

---
⚠️ قوانین پروژه

❌ کارهایی که نباید انجام شود

1. هیچ عضوی نباید مستقیماً روی "main" Push کند.

2. هیچ عضوی نباید فایل‌های مربوط به عضو دیگر را بدون هماهنگی تغییر دهد.

3. Branch اعضای دیگر نباید حذف یا تغییر داده شود.

4. قبل از شروع کار روی Branch شخصی، در صورت نیاز تغییرات جدید "develop" بررسی شود.

5. بدون بررسی سرگروه، Pull Request نباید مستقیماً وارد "main" شود.

6. فایل‌های پروژه نباید بدون دلیل حذف یا جابه‌جا شوند.

7. نام پوشه‌ها و فایل‌های اصلی پروژه نباید خودسرانه تغییر کند.

8. هر عضو باید تغییرات مربوط به بخش خودش را در Branch خودش Commit و Push کند.

---

✅ کارهایی که باید انجام شود

1. هر عضو باید فقط روی Branch اختصاصی خودش کار کند.

2. نام‌گذاری فایل‌ها و پوشه‌ها باید مطابق معماری پروژه باشد.

3. Commitها باید واضح و مرتبط با تغییرات انجام‌شده باشند.

4. بعد از پایان کار، عضو باید تغییرات خود را Push کند.

5. سپس Pull Request برای "develop" ایجاد شود.

6. سرگروه تغییرات را بررسی می‌کند.

7. در صورت وجود مشکل، عضو باید اصلاحات لازم را انجام دهد.

8. بعد از تأیید، تغییرات به "develop" Merge می‌شوند.

9. "main" فقط نسخه نهایی و تأییدشده پروژه را نگهداری می‌کند.
