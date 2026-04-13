---
name: export
description: "تصدير وتنظيم المحتوى المنتج في مجلدات منظمة مع فهرس وكتالوج."
allowed-tools: Read Write Glob Grep Bash
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# تصدير وتنظيم المحتوى - Export

## متى تستخدم هذه المهارة
- تنظيم المحتوى المنتج في مجلدات output/
- إنشاء فهرس/كتالوج لكل المحتوى
- تصدير محتوى لمنصة معينة (YouTube, Instagram, etc.)
- إنشاء معرض HTML لعرض المحتوى

## المدخلات
- --type [catalog|gallery|organize|platform] - مطلوب
- --platform [youtube|instagram|tiktok|kdp|itch] - مع type=platform
- --output [html|markdown|json] - افتراضي: markdown

## الخطوات
1. **امسح** مجلد output/ لمعرفة المحتوى الموجود
2. **صنّف** المحتوى حسب النوع والفئة العمرية
3. **أنشئ** الفهرس أو المعرض المطلوب
4. **نظّم** الملفات في المجلدات الصحيحة

## أمثلة
```
/export --type catalog --output html
/export --type gallery --output html
/export --type organize
/export --type platform --platform youtube --output markdown
```
