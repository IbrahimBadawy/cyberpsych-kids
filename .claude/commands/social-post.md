---
name: social-post
description: "محتوى سوشيال ميديا للتوعية بالأمان السيبراني - Instagram, TikTok, Twitter, LinkedIn."
allowed-tools: Read Write Glob Grep
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# محتوى سوشيال ميديا - Social Post

## متى تستخدم هذه المهارة
- إنشاء carousel تعليمي لـ Instagram
- كتابة سكريبت TikTok/Reels قصير
- تصميم thread تعليمي لـ Twitter/X
- كتابة مقال LinkedIn للمهنيين والوالدين

## المبدأ الأساسي
**المحتوى الاجتماعي يتنافس مع ملايين المنشورات. إما أن توقف الإبهام في أول ثانية أو تخسر.**

## المدخلات
- الموضوع (topic) - مطلوب
- --platform [instagram|tiktok|twitter|linkedin|facebook] - مطلوب
- --format [carousel|reel|thread|story|post|article] - حسب المنصة
- --age [جمهور مستهدف] - مطلوب
- --output [html|markdown|prompts] - افتراضي: markdown
- --lang [ar|en|both] - افتراضي: ar

## الخطوات
1. **اقرأ** templates/social-media-template.md
2. **صمم** المحتوى حسب المنصة:
   - **Instagram Carousel:** 5-10 شرائح، كل شريحة = فكرة واحدة
   - **TikTok/Reels:** Hook (1 ثانية) → محتوى (15-60 ثانية) → CTA
   - **Twitter Thread:** Hook tweet → 5-8 tweets → خلاصة
   - **LinkedIn:** مقدمة شخصية → المشكلة → الحل → CTA
3. **اكتب** الكابشن والهاشتاقات (5-10)
4. **أضف** وصف مرئي لكل عنصر

## أمثلة
```
/social-post "5 علامات إدمان الشاشة" --platform instagram --format carousel --age 28-40
/social-post "كلمة السر في 15 ثانية" --platform tiktok --format reel --age 10-12
/social-post "لماذا أطفالنا مدمنون" --platform linkedin --format article --age 28-40
```
