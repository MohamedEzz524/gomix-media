# GoMix theme — دليل الثيم

ثيم **GoMix** لمتجر منتج واحد (خلاط محمول)، مبني بتقنية React على منصة سلة. داكن، متحرك، عربي أولاً مع دعم كامل للإنجليزية.

**الدعم:** gomixshopp@gmail.com

---

## العربية

### أقسام الصفحة الرئيسية
تُرتّب وتُخفى من محرر الثيم (عناصر الصفحة):
1. **الواجهة** – صورة المنتج، ثلاث بطاقات مزايا، وشريط شراء ثابت يعرض سعر المنتج وزر الإضافة للسلة.
2. **الفيديو** – غلاف وزر تشغيل. على سطح المكتب يفتح الفيديو في نافذة عمودية، وعلى الجوال يعمل داخل القسم.
3. **المزايا** – ثلاث مزايا تظهر مع التمرير.
4. **التصميم** – أجزاء الخلاط مع بطاقة لكل جزء، تتحرك مع التمرير.
5. **آراء العملاء** – صورة أو فيديو 360° يدور مع التمرير.
6. **المقارنة** – GoMix مقابل الشيكر التقليدي.
7. **الأسئلة الشائعة**.

### الإعدادات (محرر الثيم ← الإعدادات)
| الإعداد | الوصف |
|---|---|
| منتج الشريط الثابت (`gomix_product_id`) | المنتج المعروض في شريط الشراء. فارغ = أحدث منتج |
| روابط الفيديو | رابط مباشر لملف MP4 لكل قسم (سطح المكتب والجوال) |
| مدة الفيديو | النص الظاهر بجانب زر التشغيل |
| الدفع بالتقسيط | إظهار سطر التقسيط في صفحة المنتج |
| روابط التواصل الاجتماعي | فيسبوك، إنستغرام، X في التذييل |

### نصائح
- ارفع صور المنتج بصيغة WebP وعرض نحو 1000 بكسل.
- ملفات الفيديو: MP4 (H.264)، يُفضّل أقل من 8 ميجابايت.
- وصف المنتج: كل عنوان `h3` يبدأ قسماً قابلاً للطي في صفحة المنتج.

---

## English

### Home sections
Reorder or hide them in the theme editor (page elements):
1. **Hero** – product image, three feature cards and a fixed buy bar with the product price and add-to-cart.
2. **Video** – poster and play button. On desktop the video opens in a portrait popup; on mobile it plays in the section.
3. **Features** – three benefits revealed on scroll.
4. **Design** – the shaker parts, each with its card, animated on scroll.
5. **Reviews** – image or a 360° video that turns with the scroll.
6. **Comparison** – GoMix versus a traditional shaker.
7. **FAQ**.

### Settings (theme editor → settings)
| Setting | What it does |
|---|---|
| Buy bar product (`gomix_product_id`) | Product shown in the buy bar. Empty = the latest product |
| Video URLs | Direct MP4 link per section (desktop and mobile) |
| Video duration | Text shown next to the play button |
| Installments | Show the installment line on the product page |
| Social links | Facebook, Instagram and X in the footer |

### Tips
- Upload product photos as WebP, about 1000px wide.
- Videos: MP4 (H.264), ideally under 8 MB.
- Product description: each `h3` heading starts a collapsible section on the product page.
