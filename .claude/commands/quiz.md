---
name: quiz
description: "اختبار تفاعلي عن الأمان السيبراني. يشمل أسئلة متنوعة مع إجابات وشرح."
allowed-tools: Read Write Glob Grep
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# اختبار تفاعلي - Quiz

## متى تستخدم هذه المهارة
- إنشاء اختبار لتقييم معرفة الأطفال بالأمان السيبراني
- تصميم كويز ممتع للمسابقات
- تقييم ما بعد الدرس أو الورشة

## المبدأ الأساسي
**الاختبار الجيد يعلّم أثناء التقييم. كل سؤال فرصة لتعلم شيء جديد.**

## المدخلات
- الموضوع (topic) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --questions [5|10|15] - افتراضي: 10
- --type [mcq|truefalse|scenario|mixed] - افتراضي: mixed
- --output [html|markdown|json] - افتراضي: html
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/04-age-frameworks.md
2. **صمم** الأسئلة بتنوع:
   - اختيار متعدد (4 خيارات)
   - صح وخطأ
   - سيناريو + ماذا تفعل؟
   - مطابقة
3. **أضف** شرح لكل إجابة
4. **إذا html:** أنشئ كويز تفاعلي مع نظام نقاط وتقييم فوري
5. **إذا json:** صدّر بصيغة Kahoot/Quizlet

## أمثلة
```
/quiz "كلمات المرور" --age 8-10 --questions 10 --output html
/quiz "التنمر الإلكتروني" --age 12-14 --type scenario --output json
/quiz "أمان الإنترنت الشامل" --age 10-12 --questions 15 --output html
```
