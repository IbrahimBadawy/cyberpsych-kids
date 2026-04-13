---
name: lesson
description: "خطة درس تعليمي عن الأمان السيبراني. تشمل الأهداف والمواد والأنشطة والتقييم."
allowed-tools: Read Write Glob Grep
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# خطة درس - Lesson Plan

## متى تستخدم هذه المهارة
- تصميم درس للمدرسة أو المنزل
- تحضير حصة عن الأمان السيبراني
- إنشاء وحدة تعليمية ضمن منهج

## المبدأ الأساسي
**الدرس الجيد يجعل المتعلم يكتشف ويجرب، لا يستمع ويحفظ فقط.**

## المدخلات
- الموضوع (topic) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --duration [30min|45min|60min] - افتراضي: 45min
- --output [html|markdown|slides] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/04-age-frameworks.md
2. **اقرأ** templates/lesson-plan-template.md
3. **صمم** خطة الدرس وفق هيكل:
   - أهداف SMART (3-5)
   - المواد والتحضير
   - تمهيد/إحماء (5 دقائق)
   - العرض والنقاش (15 دقيقة)
   - النشاط التطبيقي (15 دقيقة)
   - التقييم والختام (10 دقائق)
   - واجب/نشاط منزلي
   - ملاحظات للمعلم

## أمثلة
```
/lesson "البصمة الرقمية" --age 10-12 --duration 45min --output html
/lesson "الغرباء على الإنترنت" --age 6-8 --output slides
/lesson "إدارة وقت الشاشة" --age 14-16 --output markdown --lang both
```
