<div align="center">
  <img src="https://raw.githubusercontent.com/amiraction0938/Downloader-file/main/dl-icon.gif" width="200" alt="Downloader Icon" />
  <h1>📥 File Downloader + 🌐 Web Browser</h1>
  <p>
    <a href="https://github.com/amiraction0938/Downloader-file/actions"><img src="https://img.shields.io/github/actions/workflow/status/amiraction0938/Downloader-file/01-downloader.yaml?label=Downloader&logo=github" alt="Downloader" /></a>
    <a href="https://actionfamily.lol/"><img src="https://img.shields.io/badge/Site-actionfamily.lol-ff6b6b?logo=google-chrome" alt="Website" /></a>
    <a href="https://github.com/amiraction0938/YT-dl"><img src="https://img.shields.io/badge/YouTube_Downloader-amiraction0938%2FYT--dl-blueviolet?logo=youtube" alt="YT-dl" /></a>
  </p>
</div>

---

🎬 **برای دانلود ویدیوهای یوتیوب از پروژه اختصاصی زیر استفاده کنید:**  
🔗 [YouTube Downloader](https://github.com/amiraction0938/YT-dl)

---

## ⬇️ دانلود هر فایل از هر کجا – مستقیم در گیت‌هاب شما

- ✅ **دانلود مستقیم با لینک** – یک یا چند فایل را فقط با چند کلیک دریافت کنید
- ✅ **سرعت دیوانه‌وار** – کش کردن WARP و پیش‌نیازها؛ اجراهای بعدی چند برابر سریع‌تر
- ✅ **پارتی‌بندی هوشمند** – شکستن فایل‌های بزرگ به قطعات ۹۰ مگابایتی و زیپ شدن آن‌ها
- ✅ **رمزگذاری دلخواه** – فایل‌های زیپ‌شده را با پسورد محافظت کنید
- ✅ **ذخیره در شاخهٔ جدید** (اختیاری) – شاخهٔ اصلی همیشه تمیز بماند
- ✅ **مرورگر وب داخلی** – از هر سایتی اسکرین‌شات بگیرید و محتوایش را ذخیره کنید
- ✅ **مدیریت کامل** – مرتب‌سازی خودکار فایل‌ها، پاک‌سازی یک‌جا، و نمایش لینک دانلود
- ✅ **تاریخچهٔ سبک** – مخزن شما بدون فایل‌های قدیمی حجیم

---

## ⚙️ نصب (فقط یک فورک)

1. روی دکمۀ **Fork** در بالای همین صفحه کلیک کنید.  
2. یک نام انتخاب کنید (یا همان `Downloader-file` بماند).  
3. روی **Create fork** کلیک کنید.  
   **همین!** حالا پروژه روی اکانت شماست.

> 💡 حجم پیش‌فرض هر ریپازیتوری گیت‌هاب ۴ گیگابایت است. اگر پر شد، یک فورک تازه از [همین پروژه](https://github.com/amiraction0938/Downloader-file) بسازید.

---

## 🚀 روش استفاده

1. وارد ریپازیتوری فورک‌شده‌ی خود شوید و به تب **Actions** بروید.  
2. از منوی سمت چپ، یکی از workflowهای زیر را انتخاب کنید:

| Workflow | کاربرد |
|----------|--------|
| **`01- Download from url`** | دانلود فایل(ها) از لینک مستقیم |
| **`2-Sort files`** | مرتب‌سازی فایل‌های زیپ‌شده و پارتی‌ها |
| **`3-Clean downloads folder`** | خالی کردن کامل پوشه‌ی `downloads` |
| **`4-Browse the Web`** | اسکرین‌شات از وب‌سایت‌ها و دانلود محتوای آن‌ها |

3. روی **Run workflow** کلیک کنید و تنظیمات را انجام دهید:

| فیلد (در دانلودر) | توضیح | پیش‌فرض |
|-------------------|-------|---------|
| `urls` | لینک(های) فایل (با فاصله جدا کنید) | *(الزامی)* |
| `mode` | `normal` (هر فایل جداگانه) یا `zip` (همه در یک زیپ) | `normal` |
| `password` | رمز برای فایل‌های زیپ (اختیاری) | خالی |
| `save_in_new_branch` | `true` = ذخیره در یک شاخهٔ جدید | `false` |

4. روی **Run workflow** کلیک کنید و منتظر بمانید.  
5. با سبز شدن تیک، فایل‌ها در پوشه‌ی `downloads` (یا در شاخهٔ جدید) قرار گرفته‌اند.

> 💡 اگر `save_in_new_branch = true` را انتخاب کرده‌اید، برای دیدن فایل‌ها:  
> **Branches** ← روی شاخهٔ جدید کلیک کنید (نامش شبیه `download-20260510-143022-a1b2c3` است).

---

## 📂 فایل‌ها کجا ذخیره می‌شوند؟

- **`save_in_new_branch = false` (پیش‌فرض):**  
  فایل‌ها در پوشه‌ی `downloads` در شاخه‌ی اصلی (`main`). هر فایل یک زیرپوشه با README اختصاصی دارد.

- **`save_in_new_branch = true`:**  
  فایل‌ها در یک شاخهٔ جدید (نام خودکار بر اساس تاریخ) ذخیره می‌شوند. برای پیدا کردن آن‌ها:  
  ۱. روی `main` کلیک کنید.  
  ۲. تب **Branches** را بزنید.  
  ۳. روی شاخهٔ جدید کلیک کنید (مثلاً `download-20260510-143022-a1b2c3`).  
  ۴. فایل‌ها در ریشهٔ آن شاخه هستند.

---

## 🧹 پاک‌سازی

با اجرای **`3-Clean downloads folder`**، تمام محتوای پوشه‌ی `downloads` از شاخه‌ی `main` حذف می‌شود.  
اگر از شاخه‌های جداگانه استفاده کرده‌اید، خودتان می‌توانید شاخه‌های قدیمی را از تب Branches حذف کنید.

---

## 🌐 مرورگر وب

با workflow **`4-Browse the Web`** می‌توانید:
- از هر سایتی اسکرین‌شات تمام‌صفحه بگیرید.
- HTML صفحه را ذخیره کنید.
- تصاویر و فایل‌های رسانه‌ای صفحه را دانلود کنید.
- (برای عبور از فیلترینگ، از پروکسی WARP استفاده می‌شود)

---

## ❓ پرسش‌های رایج

<details>
<summary><strong>چرا فایل من ۲۰ کیلوبایت دانلود شد ولی حجم اصلی ۱ گیگ بود؟</strong></summary>
این مشکل در نسخه‌های جدید کاملاً رفع شده. فایل‌های HTML اشتباهی تشخیص داده می‌شوند و پیام خطا دریافت می‌کنید. مطمئن شوید لینک مستقیم فایل را وارد می‌کنید (نه لینک صفحه‌ی دانلود با دکمه).
</details>

<details>
<summary><strong>چطور فایل‌های زیپ‌شده را باز کنم؟</strong></summary>
همه‌ی پارت‌ها (`.zip`, `.z01`, `.z02`, ...) را در یک پوشه بگذارید و با 7-Zip یا WinRAR فایل `.zip` را استخراج کنید.
</details>

<details>
<summary><strong>چطور سرعت را افزایش دهیم؟</strong></summary>
سرعت اجرا با کش خودکار بهبود یافته. دفعات بعدی اجرا بسیار سریع‌تر از بار اول است.
</details>

---

## 🔔 به‌روزرسانی

برای دریافت آخرین تغییرات، در فورک خود روی **Sync fork** و سپس **Update branch** کلیک کنید.

---
---

<div align="center">
  <sub>Made with ❤️ by <strong>amiraction</strong> – فایل‌های شما، همیشه امن در گیت‌هاب</sub>
</div>

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

## Files downloaded to your GitHub

1. [compressed_watermark_5215_layladr_85262600956](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_5215_layladr_85262600956)

2. [compressed_watermark_62848_fake_billie_eilish_72291341055](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_62848_fake_billie_eilish_72291341055)

3. [compressed_watermark_68365_layladr_30932244169](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_68365_layladr_30932244169)

4. [compressed_watermark_71198_layladr_66029907691](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_71198_layladr_66029907691)

5. [compressed_watermark_77347_layladr_(1)](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_77347_layladr_(1))

6. [compressed_watermark_9310_layladr_(21)](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_9310_layladr_(21))

7. [compressed_watermark_98933_layladr_87220576480](https://github.com/ti44-lgtm/Downloader-file6667/tree/main/downloads/compressed_watermark_98933_layladr_87220576480)

---
