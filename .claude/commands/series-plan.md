---
name: series-plan
description: "تخطيط سلسلة محتوى كاملة - قصص أو فيديوهات أو دروس. يشمل الحلقات والتطور والشخصيات."
allowed-tools: Read Write Glob Grep WebSearch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# تخطيط سلسلة - Series Plan

## متى تستخدم هذه المهارة
- تخطيط سلسلة قصص مصورة (5-12 قصة)
- تخطيط سلسلة فيديوهات يوتيوب (season)
- تخطيط منهج تعليمي متكامل (دورة)

## المبدأ الأساسي
**السلسلة الناجحة تجعل الطفل ينتظر الحلقة القادمة بشوق. كل حلقة مكتملة بذاتها لكنها جزء من قصة أكبر.**

## المدخلات
- الموضوع العام (theme) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --type [stories|videos|lessons|mixed] - مطلوب
- --episodes [5|8|10|12] - افتراضي: 8
- --output [html|markdown] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/04-age-frameworks.md و knowledge/03-digital-problems.md
2. **صمم** السلسلة:
   - اسم السلسلة
   - الفكرة العامة (Logline)
   - الشخصيات الرئيسية
   - قائمة الحلقات مع ملخص كل حلقة
   - التطور التعليمي (من السهل للصعب)
   - أقواس الشخصيات (Character Arcs)
3. **أنشئ** Series Bible شامل

## أمثلة
```
/series-plan "أبطال الإنترنت" --age 6-8 --type stories --episodes 10
/series-plan "دقيقة أمان" --age 10-12 --type videos --episodes 12
/series-plan "رحلة الأمان الرقمي" --age 8-10 --type mixed --episodes 8
```
