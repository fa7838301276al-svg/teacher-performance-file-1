# سياسة الأمان (Security Policy)

## الرموز والتفويضات (Tokens and Authorizations)

تم استخدام تفويض مؤقت (OAuth أو Personal Access Token - PAT) لإنشاء هذا المستودع ورفع الملفات الأولية. **هذا الرمز يجب أن يُحذف فورًا بعد الانتهاء من الإعداد الأولي.**

### خطوات حذف التفويض:

#### إذا كنت تستخدم Personal Access Token (PAT):
1.  اذهب إلى [GitHub Settings - Personal Access Tokens](https://github.com/settings/tokens)
2.  ابحث عن الرمز المستخدم لإنشاء هذا المستودع
3.  انقر على **Delete** لحذفه

#### إذا كنت تستخدم OAuth:
1.  اذهب إلى [GitHub Settings - Authorized OAuth Apps](https://github.com/settings/applications)
2.  ابحث عن التطبيق الذي استخدمته
3.  انقر على **Revoke** لإلغاء التفويض

## الملفات الحساسة (Sensitive Files)

**لا تقم أبدًا بـ:**
*   حفظ رموز أو كلمات مرور في ملفات المشروع
*   رفع ملفات `.env` تحتوي على معلومات حساسة
*   نشر معلومات شخصية حساسة في الملف الوظيفي

## الإبلاغ عن الثغرات الأمنية (Reporting Security Vulnerabilities)

إذا اكتشفت أي ثغرة أمنية في هذا المشروع، يرجى الإبلاغ عنها بشكل خاص:
*   لا تقم بنشر التفاصيل علنًا في Issues
*   قم بإرسال بريد إلكتروني إلى مسؤول المستودع

---

# Security Policy

## Tokens and Authorizations

A temporary authorization (OAuth or Personal Access Token - PAT) was used to create this repository and upload the initial files. **This token must be deleted immediately after the initial setup is complete.**

### Steps to Delete the Authorization:

#### If you are using a Personal Access Token (PAT):
1.  Go to [GitHub Settings - Personal Access Tokens](https://github.com/settings/tokens)
2.  Find the token used to create this repository
3.  Click **Delete** to remove it

#### If you are using OAuth:
1.  Go to [GitHub Settings - Authorized OAuth Apps](https://github.com/settings/applications)
2.  Find the application you used
3.  Click **Revoke** to revoke the authorization

## Sensitive Files

**Never:**
*   Save tokens or passwords in project files
*   Upload `.env` files containing sensitive information
*   Publish sensitive personal information in the performance file

## Reporting Security Vulnerabilities

If you discover any security vulnerabilities in this project, please report them privately:
*   Do not publish details publicly in Issues
*   Send an email to the repository administrator
