---
name: project-discuss
description: "مناقشة مشروع قائم - إضافة أفكار وملاحظات وأبحاث في مرحلة المناقشة."
allowed-tools: Read Write Glob Grep WebSearch WebFetch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# مناقشة المشروع - Project Discussion

## متى تستخدم هذه المهارة
- إضافة أفكار جديدة لمشروع في مرحلة المناقشة
- البحث عن مراجع ومصادر للمشروع
- مناقشة الاتجاه العام والقرارات

## المبدأ الأساسي
**المناقشة الجيدة تستكشف كل الاحتمالات قبل الالتزام بخطة. لا تتسرع في التنفيذ.**

## المدخلات
- اسم المشروع (project) - مطلوب
- --action [add-idea|research|brainstorm|decide|summarize] - افتراضي: brainstorm

## الخطوات
1. **اقرأ** `projects/[اسم-المشروع]/status.json` للتأكد من المرحلة
2. **اقرأ** `projects/[اسم-المشروع]/01-discussion/notes.md` للسياق السابق
3. **حسب الإجراء:**
   - **add-idea**: أضف فكرة جديدة مع التاريخ في `ideas.md`
   - **research**: ابحث في knowledge/ والإنترنت وسجّل في `research.md`
   - **brainstorm**: جلسة عصف ذهني مع المستخدم - سجّل كل الأفكار
   - **decide**: لخّص النقاشات واطلب قرارات من المستخدم
   - **summarize**: اكتب ملخص شامل لكل المناقشات
4. **حدّث** `notes.md` بالمناقشة الجديدة مع timestamp
5. **إذا تمت المناقشة:** اقترح الانتقال لمرحلة التخطيط (`/project-plan`)

## شكل التسجيل في notes.md
```markdown
---
### [التاريخ] - [عنوان المناقشة]

**المشاركون:** المستخدم + Claude
**الموضوع:** [موضوع النقاش]

#### النقاط الرئيسية:
1. ...
2. ...

#### القرارات:
- [✅] قرار تم اتخاذه
- [❓] نقطة تحتاج مزيد من النقاش

#### الخطوة التالية:
...
---
```

## أمثلة
```
/project-discuss "سلسلة-قصص-التنمر" --action brainstorm
/project-discuss "سلسلة-قصص-التنمر" --action research
/project-discuss "سلسلة-قصص-التنمر" --action decide
```
