---
name: tool-guide
description: "دليل اختيار الأدوات المناسبة لإنشاء محتوى معين - يقارن بين المجانية والمدفوعة ويقترح أفضل workflow."
allowed-tools: Read Write Glob Grep WebSearch
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# دليل الأدوات - Tool Guide

## متى تستخدم هذه المهارة
- لا تعرف أي أداة تستخدم لمهمة معينة
- تريد مقارنة بين الأدوات المجانية والمدفوعة
- تحتاج workflow كامل لإنتاج محتوى
- تريد تقدير الوقت والتكلفة

## المبدأ الأساسي
**استخدم الأداة الأبسط التي تحقق الهدف. لا تعقّد الأمور بأدوات أكثر مما تحتاج.**

## المدخلات
- ماذا تريد إنشاءه (task) - مطلوب
- --budget [free|low|any] - افتراضي: any
- --output [markdown|html|chart] - افتراضي: markdown

## الخطوات
1. **اقرأ** knowledge/13-tools-ecosystem.md
2. **حلل** المهمة المطلوبة
3. **اقترح** الأدوات المناسبة:

### جدول الأدوات حسب المهمة
```
المهمة              | الأفضل (مدفوع)    | المجاني
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
صور شخصيات         | Freepik Spaces     | Leonardo.ai
صور مع نص          | ChatGPT DALL-E     | Ideogram
فيديو قصير         | Freepik Video      | Pika / CapCut
تعليق صوتي         | Freepik Voice      | ElevenLabs free
قصة مصورة          | Claude + Freepik   | Claude + Canva
لعبة إلكترونية     | --                 | GDevelop / Scratch
قصة تفاعلية        | --                 | Twine
بودكاست            | Gemini TTS         | NotebookLM Audio
كتاب إلكتروني      | --                 | Book Creator / KDP
عرض تقديمي         | --                 | Google Slides
إنفوجرافيك         | Freepik            | Canva free
3D / VR            | Blender MCP        | Blender (مجاني)
```

4. **صمم** الـ workflow المقترح خطوة بخطوة
5. **قدّر** الوقت المطلوب لكل خطوة

## أمثلة
```
/tool-guide "أريد كتابة وتصوير قصة مصورة للأطفال 4-6"
/tool-guide "أريد عمل فيديو تعليمي 5 دقائق" --budget free
/tool-guide "أريد لعبة تفاعلية على الويب" --budget free --output html
```
