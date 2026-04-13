---
name: infographic
description: "تصميم إنفوجرافيك تعليمي عن الأمان السيبراني. يشمل البيانات والتصميم المرئي."
allowed-tools: Read Write Glob Grep WebSearch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# إنفوجرافيك - Infographic

## متى تستخدم هذه المهارة
- تلخيص إحصائيات عن الأمان السيبراني بصرياً
- إنشاء ملصقات تعليمية للفصول
- تصميم محتوى مرئي للسوشيال ميديا

## المبدأ الأساسي
**الإنفوجرافيك الجيد يوصل الفكرة في 5 ثوانٍ. إذا احتاج المشاهد أكثر من ذلك، أعد التصميم.**

## المدخلات
- الموضوع (topic) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --output [html|markdown|prompts|chart] - افتراضي: html
- --lang [ar|en|both] - افتراضي: ar
- --style [stats|steps|comparison|timeline] - افتراضي: stats

## الخطوات
1. **اجمع** البيانات من knowledge/ والإنترنت
2. **نظّم** المعلومات: عنوان رئيسي، 3-5 نقاط، إحصائيات، خلاصة
3. **إذا html:** أنشئ إنفوجرافيك HTML مع Chart.js
4. **إذا prompts:** اكتب prompts لـ Canva/Freepik
5. **إذا chart:** أنشئ رسوم بيانية تفاعلية

## أمثلة
```
/infographic "إحصائيات التنمر الإلكتروني" --age 12-14 --output chart
/infographic "5 خطوات لكلمة مرور قوية" --age 8-10 --style steps --output html
/infographic "مقارنة: مع شاشة vs بدون شاشة" --age 28-40 --style comparison
```
