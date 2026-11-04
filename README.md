# MIRQAB | مِرقاب
دليل هندسي تفاعلي للاتصالات — واجهة Frontend ثابتة فقط.

## التقنية
- HTML5 متعدد الصفحات
- CSS3 responsive + RTL
- Vanilla JavaScript
- بيانات JSON محلية
- SVG/CSS effects
- لا يوجد Backend أو قاعدة بيانات أو API server
- مناسب للنشر على GitHub Pages

## التشغيل
لأن المتصفح قد يمنع `fetch()` لملفات JSON عند فتح `index.html` مباشرة عبر `file://`، شغّل مجلد المشروع عبر خادم محلي بسيط أو ارفع المشروع إلى GitHub Pages.
مثال باستخدام VS Code: إضافة Live Server ثم فتح `index.html`.

## إضافة الوسائط
ضع الملفات التي ستجهزها ضمن المسارات التالية:
- `assets/video/mirqab-hero.mp4` — فيديو الهيرو، 10 ثوانٍ، 16:9، بدون صوت
- `assets/video/mirqab-hero-poster.webp` — صورة ثابتة للفيديو
- `assets/images/fiber-optics.webp`
- `assets/images/microwave-transmission.webp`
- `assets/images/global-telecom-network.webp`

الفيديو مضبوط على autoplay muted playsinline، ويتوقف عند نهاية المقطع. عند تفعيل تقليل الحركة يتم إخفاؤه.

## الصفحات
- `index.html` الرئيسية
- `specialties.html` قائمة التخصصات والبحث والتصفية
- `specialty.html?id=...` قالب تفاصيل تخصص من بيانات JSON
- `career-paths.html` المسارات المهنية
- `career-navigator.html` مستكشف مسار تفاعلي
- `labs.html` أدوات حسابية تعليمية
- `projects.html` المشاريع
- `glossary.html` معجم عربي/إنجليزي
- `about.html` عن المنصة

## ملاحظات هندسية
الأدوات في المختبر تعليمية وتستخدم افتراضات مبسطة. يجب مراجعة النتائج والتحقق منها قبل استخدامها في تصميمات أو أعمال ميدانية حقيقية.
