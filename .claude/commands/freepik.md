---
name: freepik
description: "إرشادات خطوة بخطوة لإنشاء محتوى في Freepik Spaces - صور وفيديو وصوت بالذكاء الاصطناعي."
allowed-tools: Read Write Glob Grep WebSearch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# إنشاء محتوى في Freepik Spaces

## متى تستخدم هذه المهارة
- إنشاء صور لشخصيات القصص في Freepik Spaces
- توليد مشاهد متسقة لسلسلة قصصية
- إنتاج تعليق صوتي بالذكاء الاصطناعي
- توليد مقاطع فيديو قصيرة

## المبدأ الأساسي
**Freepik Spaces يعمل بنظام Nodes - كل خطوة هي عقدة تتصل بالتالية. الاتساق في الشخصيات هو المفتاح.**

## المدخلات
- الموضوع (topic) - مطلوب: ماذا تريد إنشاءه
- --type [character|scene|series|voice|video] - مطلوب
- --age [الفئة العمرية] - لتحديد أسلوب الرسم
- --output [prompts|instructions|markdown] - افتراضي: prompts
- --lang [ar|en|both] - افتراضي: en (prompts الصور تكون بالإنجليزية)

## الخطوات

### لإنشاء شخصية (character):
1. **أنشئ** Character Reference Sheet prompt:
   ```
   Character sheet of [name], [age] year old [description],
   multiple angles (front, side, back, 3/4 view),
   children's book illustration style, [color palette],
   white background, consistent design
   ```
2. **استخدم** Image Generator node مع Custom Elements
3. **احفظ** كـ Custom Character للاستخدام المتكرر

### لإنشاء سلسلة مشاهد (series):
1. **حمّل** الشخصية المحفوظة
2. **استخدم** List Node لتوليد مشاهد متعددة
3. **اكتب** prompt لكل مشهد مع الحفاظ على الاتساق
4. **استخدم** Image Upscaler لتحسين الجودة

### للتعليق الصوتي (voice):
1. **استخدم** Voice Generator node
2. **اختر** النموذج: ElevenLabs v3 (طبيعي) أو Gemini (متعدد اللغات)
3. **اكتب** النص بالعربية
4. **حدد** نبرة الصوت (هادئ للقصص، حماسي للألعاب)

## أمثلة
```
/freepik "شخصية سارة بطلة قصة التنمر" --type character --age 6-8
/freepik "5 مشاهد لقصة كلمة السر" --type series --age 4-6
/freepik "تعليق صوتي لقصة الخصوصية" --type voice --lang ar
```
