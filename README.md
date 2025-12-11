# TalentAI – منصة توظيفي الذكية بالذكاء الاصطناعي  
Prototype for Tuwaiq Hackathon | نموذج أولي لمشروع هاكاثون طويق

---

## 🌍 نبذة عن المشروع (Arabic)

**TalentAI | منصة توظيفي الذكية**  
هي واجهة نموذجية (Landing Page Prototype) لمنصة توظيف مبتكرة تعتمد على **الذكاء الاصطناعي** لدعم سوق العمل السعودي والخليجي، وتتماشى مع مستهدفات **رؤية المملكة العربية السعودية 2030** في تمكين الكفاءات الوطنية وتقليل فجوة المهارات.

هذا النموذج يقدّم تصورًا بصريًا وعمليًا لفكرة المنصة، يمكن استخدامه في:

- عرض المشروع أمام لجنة تحكيم هاكاثون طويق  
- بناء نسخة أولية (MVP) لاحقًا  
- تطويره إلى منصة متكاملة للتوظيف الذكي

---

## ✨ المزايا الرئيسية في النموذج

- 🌐 **دعم لغتين**: العربية والإنجليزية مع زر تبديل اللغة (RTL / LTR)
- 🎨 **تصميم عصري** مستوحى من هوية المنصات التقنية والذكاء الاصطناعي
- 📱 **تصميم متجاوب** يعمل على الجوال والتابلت والكمبيوتر
- 🧠 عرض فكرة:
  - نظام ATS ذكي
  - تحليل السيرة الذاتية
  - Talent Score
  - المقابلات الافتراضية
  - الربط مع معاهد التدريب
- 💬 **زر واتساب عائم** للتواصل المباشر مع رقم دعم المنصة
- 📝 **نموذج اهتمام** (Contact Form) يرسل البيانات إلى واتساب (فتح محادثة جاهزة)
- ⬆️ **زر العودة إلى الأعلى** (Back to Top) مع سكرول ناعم
- 🎭 أنيميشن ناعم عند ظهور العناصر أثناء التمرير (Scroll Reveal Animation)

---

## 🧩 الهيكل العام للمشروع (Project Structure)

```text
talentai-landing/
├─ index.html    # صفحة الهبوط (الواجهة الرئيسية)
├─ style.css     # تنسيق التصميم (CSS)
├─ script.js     # منطق التبديل بين اللغات + الأنيميشن + الواتساب
└─ app.py        # (اختياري) ملف Flask لتشغيل المشروع عبر Python محليًا


# TalentAI – Smart Recruitment Platform (Prototype)

Prototype landing page for **TalentAI | Tawdifi AI**, an AI-powered recruitment platform concept built for the **Tuwaiq Hackathon**.

---

## 🌍 Project Overview

**TalentAI** is a concept for an intelligent recruitment platform that uses **AI** to:

- Analyze CVs and extract skills
- Score candidates (Talent Score)
- Match candidates to jobs using AI (ATS+Matching)
- Support virtual interviews and training recommendations

This repository contains a **responsive bilingual landing page** that visually presents the idea and can be used as:

- A live demo during the hackathon pitch
- A foundation for an MVP
- A starting point for a full recruitment platform

---

## ✨ Key Features

- 🌐 **Bilingual Interface** – Arabic & English with a language toggle (RTL/LTR support)
- 📱 **Fully Responsive** – Works on mobile, tablet, and desktop
- 🎨 **Modern Design** – Glassmorphism, gradients, smooth animations
- 🧠 Sections that highlight:
  - Smart ATS engine
  - CV analysis & Talent Score
  - AI virtual interviews
  - Training & skill development integration
- 💬 **Floating WhatsApp Button**
  - Direct contact via WhatsApp to: `+966541331320`
- 📝 **Contact Form → WhatsApp**
  - On submit, opens WhatsApp chat with pre-filled message containing:
    - Name
    - Email
    - User type (Job Seeker / Company / Training Institute)
- ⬆️ **Back-to-Top Button**
  - Appears on scroll and smoothly returns the user to the top
- 🎭 **Scroll Reveal Animations**
  - Elements animate into view using `IntersectionObserver`

---

## 🧩 Project Structure

```text
talentai-landing/
├─ index.html    # Main landing page
├─ style.css     # Styles (responsive layout, animations, theming)
├─ script.js     # Language toggle, scroll animations, WhatsApp integration
└─ app.py        # (Optional) Simple Flask server for local hosting
