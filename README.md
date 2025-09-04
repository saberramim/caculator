#Calculator Javascript
A simple, beautiful, and efficient calculator built with modern JavaScript (ES6). This project showcases clean code organization, a responsive UI, and reliable arithmetic operations suitable for everyday use.
<img width="1089" height="618" alt="Snap36" src="https://github.com/user-attachments/assets/b2f06a34-774a-45e1-9110-f84edc85fe13" />

Features
Smooth and elegant UI: Modern, user-friendly, responsive design for all screen sizes.
Basic arithmetic operations: Addition, subtraction, multiplication, division, with common operations supported.
ES6 code quality: Uses modern JavaScript features like classes, modules, and arrow functions.
Straightforward event handling: Clean input handling and UI updates.
Accessible and keyboard-friendly: Keyboard support and adaptive features.
Optional memory: Ability to store the last result for repeated use.
No heavy dependencies: Vanilla JavaScript only (no external libraries) for performance and maintainability.

Project Structure
bash
Calculator-Javascript/
├── index.html          # Main page and display
├── styles.css          # Modern, responsive styling
└── README.md            # Project documentation
index.html: HTML structure for the display, input, and keypad.
styles.css: Responsive styling using Flexbox/Grid for a polished look.
script.js: ES6-based calculator logic, managing operations and UI updates.
assets/: Optional assets like icons.
README.md: This description and usage details.

How to Run
Clone or download the project.
Open index.html in a browser.
(Optional) Serve locally with a simple server, e.g.:
python -m http.server 8000
Then open http://localhost:8000
Installation & Setup
No dependencies. Just place the files in a folder and open in a browser.
If hosting on GitHub, ensure index.html, styles.css, and script.js are up to date.

Usage
Click numeric and operator keys to build expressions.
The result updates on each operation.
Keyboard support is available (future enhancement).

Code Architecture
Single Responsibility: Clear separation between user input, calculation logic, and UI updates.
ES6 Classes / Modules: Encapsulation and modular structure.
Error Handling: Graceful handling of divisions by zero and invalid input.
Documentation & Comments: Clear in-code comments explaining core logic.
Future Enhancements
Operator precedence and expression parsing for complex chains.
History storage and recall for calculations.
Additional keys like Percent, Sign (+/-), etc.
Subtle animations for user feedback.
Full keyboard navigation and shortcuts.

About the Project
The goal is to deliver a lightweight yet quality calculator built with ES6 JavaScript, suitable for educational purposes, small demos, or as a basic web tool.
...
..
.


یک ماشین‌حساب ساده، زیبا و کارآمد با استفاده از جاوااسکریپت مدرن (ES6). این پروژه سازماندهی کد تمیز، رابط کاربری پاسخگو و محاسبات معتبر پایه را برای استفاده روزمره به نمایش می‌گذارد.

ویژگی‌ها
رابط کاربری روان و زیبا: طراحی مدرن، کاربرپسند و پاسخگو برای هر اندازه صفحه.
عملیات حسابداری پایه: جمع، تفریق، ضرب، تقسیم، با پشتیبانی از عملیات متداول.
کیفیت کد ES6: از ویژگی‌های مدرن جاوااسکریپت مانند کلاس‌ها، ماژول‌ها و توابع箭 استفاده می‌شود.
مدیریت رویداد ساده: ورودی کاربر و بروزرسانی نمایشگر به‌طور ساده مدیریت می‌شود.
دسترسی و پشتیبانی از کیبرد: پشتیبانی از کیبرد و ویژگی‌های سازگار با دسترس‌پذیری.
حافظه محلی (اختیاری): امکان ذخیره نتیجه آخر یا استفاده مجدد از آن در محاسبات.
بدون وابستگی به فریم‌ورک‌های سنگین: فقط با جاوااسکریپت خام (vanilla) بدون کتابخانه‌های خارجی برای کارایی و نگهداری آسان.
ساختار پروژه
bash
Calculator-Javascript/
├── index.html          # صفحه اصلی و نمایشگر ماشین حساب
├── styles.css          # طراحی مدرن و پاسخگو
└── README.md            # توضیحات پروژه
.
index.html: ساختار HTML برای نمایشگر، ورودی کاربر و کلیدها.
styles.css: استایل‌های پاسخگو با استفاده از Flexbox/Grid برای طراحی زیبا.
README.md: این توضیحات و نشانه‌های استفاده.
چگونگی اجرا
کل پروژه را دانلود یا کلون کنید.
باز کردن index.html در مرورگر.
(اختیاری) استفاده از یک سرور محلی:
python -m http.server 8000
سپس به آدرس http://localhost:8000 مراجعه کنید.
.
نصب و راه‌اندازی
بدون نیاز به وابستگی‌ها. فقط فایل‌ها را در یک پوشه قرار دهید و از مرورگر باز کنید.
اگر می‌خواهید پروژه را روی گیت‌هاب میزبانی کنید:
مطمئن شوید که فایل‌های index.html، styles.css و script.js به‌روز هستند.
می‌توانید یک بخش Script با استفاده از ماژول یا IIFE برای جداسازی کلاس‌ها کنار بگذارید.
.
نمونه استفاده
کلیدهای عددی و عملیاتی را برای ساخت عبارت محاسباتی فشار دهید.
نتیجه با انجام هر عملیات در نمایشگر بالایی نشان داده می‌شود.
پشتیبانی از کیبرد در نسخه‌های آینده (در صورت پیاده‌سازی).
.
معماری کد
مسئولیت واحد (Single Responsibility): هر جزء مسئولیت مشخصی دارد: ورودی کاربر، منطق محاسبه، و بروزرسانی UI.
کلاس‌ها/ماژول‌های ES6: استفاده از کلاس‌ها برای کپسوله‌سازی یا ماژول‌ها برای جداسازی منطق.
مدیریت خطاها: مدیریت ساده خطاهای محاسبه مانند تقسیم بر صفر با پیام کاربرپسند.
کامنت‌گذاری و مستندسازی داخلی: توضیحات واضح برای منطق کلیدی و توابع.
.
نکات بهبود و توسعه آینده
اولویت و پارس یک عبارت پیچیده با توالی عملگرها.
ذخیره و بازیابی تاریخ محاسبات.
کلیدهای اضافی مانند Percent، +/- برای تغییر علامت، و غیره.
انیمیشن‌های لطیف برای بازخورد کاربر.
پشتیبانی کامل از ورودی کیبرد و شورتکات‌ها.
.
درباره پروژه
هدف از پروژه "Calculator Javascript" ارائه یک ماشین‌حساب ساده اما با کیفیت است که با JavaScript ES6 نوشته شده و به‌صورت مدرن و کارآمد طراحی شده است. مناسب برای آموزش، نمونه پروژه‌های کوچک یا به‌عنوان ابزار پایه محاسباتی وب.
