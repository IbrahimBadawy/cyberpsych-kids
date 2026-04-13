---
name: blender-scene
description: "إنشاء مشهد 3D في Blender باستخدام أدوات MCP - نماذج ثلاثية الأبعاد وبيئات وأنيميشن."
allowed-tools: Read Write mcp__blender__execute_blender_code mcp__blender__generate_hyper3d_model_via_text mcp__blender__search_polyhaven_assets mcp__blender__search_sketchfab_models
metadata:
  author: CyberPsych-Kids
  version: "1.0"
---

# مشهد 3D في Blender

## متى تستخدم هذه المهارة
- إنشاء شخصيات 3D لفيديوهات تعليمية
- بناء بيئات افتراضية لقصص الأمان السيبراني
- تصميم عناصر VR تعليمية
- إنشاء أصول لألعاب ثلاثية الأبعاد

## المبدأ الأساسي
**المشهد الثلاثي الأبعاد يجعل المفهوم المجرد ملموساً ومرئياً للطفل.**

## المدخلات
- الموضوع (topic) - مطلوب: وصف المشهد المطلوب
- --type [character|environment|object|animation] - مطلوب
- --style [cartoon|realistic|low-poly] - افتراضي: cartoon
- --output [code|instructions|markdown] - افتراضي: code

## الخطوات
1. **حدد** نوع المشهد والأسلوب البصري
2. **ابحث** في Polyhaven/Sketchfab عن أصول جاهزة
3. **ولّد** نماذج جديدة بـ Hyper3D أو Hunyuan3D إذا لزم
4. **اكتب** كود Python لتجميع المشهد في Blender
5. **أضف** الإضاءة والكاميرا والمواد
6. **نفّذ** الكود عبر execute_blender_code

## أمثلة
```
/blender-scene "غرفة طفل مع كمبيوتر" --type environment --style cartoon
/blender-scene "شخصية محقق إنترنت" --type character --style low-poly
/blender-scene "درع الخصوصية الرقمي" --type object --output code
```
