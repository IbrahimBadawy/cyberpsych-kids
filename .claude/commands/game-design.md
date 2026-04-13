---
name: game-design
description: "تصميم لعبة تعليمية عن الأمان السيبراني - إلكترونية أو حركية أو لوحية. يشمل القواعد والمراحل والمكافآت."
allowed-tools: Read Write Glob Grep WebSearch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# تصميم لعبة - Game Design

## متى تستخدم هذه المهارة
- تصميم لعبة إلكترونية (Scratch/GDevelop/Twine)
- تصميم لعبة حركية في الفصل أو الفناء
- تصميم لعبة لوحية أو بطاقات
- لألعاب أسرية استخدم /family-game بدلاً

## المبدأ الأساسي
**اللعبة الجيدة تجعل التعلم ممتعاً لدرجة أن الطفل لا يدرك أنه يتعلم.**

## المدخلات
- الموضوع (topic) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --type [electronic|physical|board|card|interactive-story] - مطلوب
- --tool [scratch|gdevelop|twine|godot|none] - للإلكترونية
- --output [html|markdown|instructions|code] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/09-gamification-guide.md
2. **اقرأ** templates/game-design-doc-template.md
3. **صمم** اللعبة:

### وثيقة تصميم اللعبة (GDD)
```
اسم اللعبة: [اسم جذاب]
النوع: [إلكترونية|حركية|لوحية|بطاقات|قصة تفاعلية]
الفئة العمرية: [X-Y سنة]
عدد اللاعبين: [فردي|2|3-6]
المدة: [10-30 دقيقة]

المفهوم السيبراني: [ماذا سيتعلم اللاعب]
الهدف التعليمي: [جملة واحدة]

آليات اللعب:
- الهدف: [كيف يفوز]
- التحديات: [العقبات]
- المكافآت: [نقاط/شارات/تقدم]
- المستويات: [عدد المراحل ووصفها]

المواد/الأدوات:
- [للإلكترونية: المنصة والأداة]
- [للحركية: المساحة والأدوات]
- [للوحية: المكونات المطلوبة]

القواعد التفصيلية:
1. التحضير: ...
2. البداية: ...
3. اللعب: ...
4. نهاية اللعبة: ...

التنويعات:
- نسخة سهلة
- نسخة صعبة
```

4. **للإلكترونية (output=code):** اكتب الكود أو وصف الـ blocks
5. **للحركية (output=instructions):** اكتب تعليمات واضحة
6. **إذا output=html:** صمم لعبة HTML تفاعلية بسيطة

## أمثلة
```
/game-design "كشف التصيد الإلكتروني" --age 10-12 --type electronic --tool scratch
/game-design "سباق كلمات المرور" --age 6-8 --type physical --output instructions
/game-design "بطاقات الأمان" --age 8-10 --type card --output html
/game-design "مغامرة في عالم الإنترنت" --age 10-12 --type interactive-story --tool twine
```
