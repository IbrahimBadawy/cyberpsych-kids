---
name: video-script
description: "سيناريو فيديو تعليمي عن الأمان السيبراني. يشمل Hook والمقاطع وملاحظات B-Roll والتوقيت."
allowed-tools: Read Write Glob Grep
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# سيناريو فيديو - Video Script

## متى تستخدم هذه المهارة
- كتابة سيناريو فيديو يوتيوب تعليمي
- إنشاء سكريبت TikTok/Reels قصير
- تحضير فيديو لدورة تعليمية

## المبدأ الأساسي
**كل ثانية في الفيديو يجب أن تكسب الثانية التالية. إذا لم يكن لدى المشاهد سبب للاستمرار، سيغادر.**

## المدخلات
- الموضوع (topic) - مطلوب
- --age [الفئة العمرية] - مطلوب
- --duration [1-2min|3-5min|5-10min|10-15min] - حسب العمر
- --platform [youtube|tiktok|reels|course] - افتراضي: youtube
- --output [html|markdown|prompts|slides] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/04-age-frameworks.md و knowledge/07-storytelling-techniques.md
2. **اقرأ** templates/video-script-template.md
3. **اكتب** السيناريو:

### هيكل السيناريو
```
[HOOK - أول 3 ثوان]
نص: "..." 
مرئي: [وصف ما يظهر على الشاشة]

[INTRO - 10-15 ثانية]
نص: تقديم الموضوع
[TEXT ON SCREEN]: العنوان

[SEGMENT 1 - المشكلة]
نص: "..."
[B-ROLL]: [وصف المشاهد المصاحبة]
[TEXT ON SCREEN]: [نقاط رئيسية]

[SEGMENT 2 - لماذا يحدث هذا]
نص: "..."
[B-ROLL]: [وصف]

[SEGMENT 3 - الحل]
نص: "..."
[B-ROLL]: [وصف]
[TEXT ON SCREEN]: [خطوات عملية]

[OUTRO + CTA]
نص: خلاصة + دعوة للعمل
[TEXT ON SCREEN]: "اشترك" / "شارك"

المدة الإجمالية: [X:XX]
```

4. **أضف** ملاحظات إنتاجية (إضاءة، زوايا كاميرا)
5. **إذا output=prompts:** اكتب prompts لتوليد مشاهد B-Roll

## أمثلة
```
/video-script "خطورة مشاركة المعلومات الشخصية" --age 8-10 --duration 3-5min
/video-script "5 نصائح للأمان الرقمي" --age 12-14 --platform tiktok --duration 1-2min
/video-script "كيف تحمي طفلك" --age 28-40 --duration 10-15min --output slides
```
