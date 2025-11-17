# ملف الأداء الوظيفي للمعلم (Teacher Performance File)

هذا المستودع يحتوي على صفحة إلكترونية متجاوبة (Responsive Web Page) مصممة لتكون ملفًا إلكترونيًا للأداء الوظيفي للمعلم، قابلة للنشر مجانًا عبر **GitHub Pages**.

## الميزات الرئيسية
*   **متجاوب (Responsive):** يعمل بشكل جيد على الهواتف الذكية والأجهزة اللوحية وأجهزة الكمبيوتر.
*   **دعم اللغة العربية (RTL):** مصمم خصيصًا لدعم اتجاه النص من اليمين إلى اليسار.
*   **نشر تلقائي (Automatic Deployment):** يتم نشر أي تغييرات تقوم بدفعها إلى فرع `main` تلقائيًا عبر GitHub Actions.

## كيفية التعديل والاستخدام

### 1. استنساخ المستودع (Clone the Repository)
للبدء في التعديل، قم باستنساخ المستودع إلى جهازك المحلي:

```bash
git clone https://github.com/fa7838301276al-svg/teacher-performance-file-1.git
cd teacher-performance-file-1
```

### 2. التعديل على المحتوى
الملف الرئيسي الذي ستقوم بتعديله هو `index.html`. يحتوي هذا الملف على هيكل الصفحة والمحتوى الخاص ببنود الأداء الوظيفي الـ 11.

*   **`index.html`:** قم بتعديل المحتوى النصي وإضافة الروابط والمرفقات الخاصة بك.
*   **`assets/`:** ضع هنا أي صور، ملفات PDF، أو ملفات أخرى تريد إرفاقها بالملف الوظيفي.

### 3. الدفع والنشر (Commit and Push)
بعد الانتهاء من التعديلات، قم بحفظها ورفعها إلى GitHub:

```bash
git add .
git commit -m "Update: Added my personal performance data"
git push origin main
```

سيقوم GitHub Actions تلقائيًا بنشر التغييرات على GitHub Pages.

## إرشادات أمنية هامة
لقد تم استخدام تفويض مؤقت (PAT أو OAuth) لإنشاء هذا المستودع. لضمان أمان حسابك، **يرجى إلغاء التفويض أو حذف رمز PAT** الذي استخدمته فورًا بعد التأكد من نجاح النشر.

---

# Teacher Performance File

This repository contains a responsive web page designed to serve as an electronic teacher performance portfolio, freely deployable via **GitHub Pages**.

## Key Features
*   **Responsive:** Works well on smartphones, tablets, and desktops.
*   **Arabic Language Support (RTL):** Specifically designed to support Right-to-Left text direction.
*   **Automatic Deployment:** Any changes pushed to the `main` branch are automatically deployed via GitHub Actions.

## How to Edit and Use

### 1. Clone the Repository
To start editing, clone the repository to your local machine:

```bash
git clone https://github.com/fa7838301276al-svg/teacher-performance-file-1.git
cd teacher-performance-file-1
```

### 2. Edit the Content
The main file you will edit is `index.html`. This file contains the page structure and the content for the 11 performance items.

*   **`index.html`:** Modify the text content and add your specific links and attachments.
*   **`assets/`:** Place any images, PDF files, or other files you wish to attach to the performance file here.

### 3. Commit and Push
Once you are done with your edits, save them and push them to GitHub:

```bash
git add .
git commit -m "Update: Added my personal performance data"
git push origin main
```

GitHub Actions will automatically deploy the changes to GitHub Pages.

## Important Security Note
A temporary authorization (PAT or OAuth) was used to create this repository. To ensure the security of your account, **please revoke the authorization or delete the PAT** you used immediately after confirming the deployment is successful.
