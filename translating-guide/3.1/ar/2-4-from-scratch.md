---
book: translating-guide
version: 3.1
---

## Starting a Translation From Scratch

Using the Translation plugin to start a translation from scratch is a little more involved than editing an incomplete, installed translation. إن استعمال الإضافة المخصصة للترجمة للشروع بها من الصفر هو أمر أكثر قبولاً من تعديل ترجمة منصبة غير مكتملة. سيكون عليك أن تقوم يدوياً بإنشاء ورفع ملف اللغة الرئيسي (`locales/[your_LANG]/locale.xml`) مع ملف قوالب المراسلات الالكترونية (`dbscripts/xml/data/locale/[your_LANG]/email_templates_data.xml` إلى نظام المجلات المفتوحة بإصداره ما قبل 2.3؛ أما ما عدا ذلك، حاول الوصول إلى `locales/[your_LANG]/`)، ثم أدخل لغتك المضافة إلى مدخلات الملف `registry/locales.xml`، وعندها ستظهر لغتك ضمن قائمة اللغات القابلة للتعديل عندما تستعمل إضافة الترجمة. Once this is done you can add new locale files as per the above instructions, and you'll even be able to edit the above two files.
