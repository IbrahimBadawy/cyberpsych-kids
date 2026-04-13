---
name: character
description: "تصميم شخصية لسلسلة محتوى الأمان السيبراني. يشمل الاسم والمظهر والشخصية وprompts توليد الصور."
allowed-tools: Read Write Glob Grep
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# تصميم شخصية - Character Design

## متى تستخدم هذه المهارة
- إنشاء بطل/ة لسلسلة قصصية
- تصميم شخصيات متكررة للفيديوهات
- بناء عالم شخصيات متكامل

## المبدأ الأساسي
**الشخصية الجيدة هي التي يتذكرها الطفل ويريد أن يكون مثلها.**

## المدخلات
- وصف الشخصية (description) - مطلوب
- --age [عمر الشخصية أو الجمهور] - مطلوب
- --role [hero|friend|mentor|villain|parent] - مطلوب
- --output [html|markdown|prompts] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** knowledge/10-character-bible.md
2. **اقرأ** templates/character-sheet-template.md
3. **صمم** الشخصية:
   - الاسم (عربي) + اللقب
   - العمر والمظهر التفصيلي
   - السمات الشخصية (3 إيجابية + 1 نقطة ضعف)
   - القصة الخلفية
   - العبارة المميزة (Catchphrase)
   - العلاقات مع الشخصيات الأخرى
4. **إذا prompts:** اكتب Character Reference Sheet prompt للـ AI
5. **إذا html:** صمم بطاقة شخصية جميلة

## أمثلة
```
/character "بطلة قصص التنمر الإلكتروني" --age 8-10 --role hero --output prompts
/character "شرير التصيد الإلكتروني" --age 10-12 --role villain --output html
/character "معلمة الأمان الرقمي" --age 6-8 --role mentor --output markdown
```
