# 🚀 AI NAVIGATORS | منصة مهندس الأوامر الذكي
### Better Prompts • Bigger Possibilities | Smarter • Faster

> **تطوير وإشراف:** أبو آيسل (Abo Aisel) — مؤسس مجتمع AI Navigators  
> **واتساب:** [+201037489146](https://wa.me/201037489146)  
> **الترخيص والاستخدام:** منتج رقمي مفتوح المصدر قابل للاستضافة الفورية على **GitHub Pages**.

---

## 🌟 نظرة عامة على المنصة

تطبيق ويب تفاعلي عالي الأداء ومُصمم بهوية بصرية مستقبلية (Cyberpunk Dark / Cyan & Gold)، يحول أطر عمل هندسة الأوامر المتقدمة (Prompt Engineering) إلى أداة سحابية سهلة الاستخدام تساعد المستخدمين على:

1. **🛠️ مُولّد الأوامر الاستراتيجي (Prompt Architect):**
   - بناء برومبتات بمعمارية الـ 12 قسماً المعتمدة.
   - توليد **4 نسخ مستقلة متزامنة بنقرة زر واحدة**:
     * 🇸🇦 النسخة العامة العربية القياسية.
     * 🇬🇧 Universal English Architecture.
     * 🤖 النسخة المهيأة لـ OpenAI ChatGPT & Canvas.
     * ✨ النسخة المهيأة لـ Google Gemini & Gems.
   - خيارات تفعيل متقدمة: محاكاة مجلس الخبراء، التفكير خطوة بخطوة (CoT)، ومكافحة الهلوسة الصارمة.

2. **⚖️ حاسبة ومُدقق جودة الأوامر (Dynamic Prompt Auditor):**
   - فحص وتشريح أي أمر ولصقه للتدقيق الفوري.
   - تقييم درجة الجودة من 100 وفق 5 معايير حاسمة.
   - كشف الثغرات ونقاط الضعف مع زر **الإصلاح الفوري والترقية التلقائية (Instant Auto-Fix)**.

3. **🗄️ خزانة البرومبتات التخصصية (The Master Prompt Vault):**
   - مكتبة مصنفة قابلة للبحث الفوري تضم برومبتات استخراج البيانات OCR إلى JSON، تلخيص الكتب، تحليل الفيديو والسينما، صناعة المناهج والحملات التسويقية.

4. **📐 دليل أطر العمل العالمية (Frameworks Guide):**
   - قوالب جاهزة للنسخ لأشهر أطر هندسة الأوامر (RTF, TAG, CARE, APE, COAST).

5. **⚙️ مسار التشغيل الاستراتيجي (7-Stage Pipeline):**
   - `PLAN` ➜ `ACCESS` ➜ `ANALYZE` ➜ `EXECUTE` ➜ `DECIDE` ➜ `MEASURE` ➜ `IMPROVE`.

---

## 📁 هيكل مجلدات المشروع

```text
ai-navigators-prompt-studio/
├── index.html              # الصفحة الرئيسية للمنصة (Entry Point)
├── README.md               # دليل التشغيل والرفع على GitHub
├── assets/                 # مجلد الوسائط والهوية البصرية
│   ├── banner.jpg          # البانر الرسمي لمجتمع AI Navigators
│   ├── identity_bg.jpg     # خلفية الهوية البصرية المستقبلية
│   ├── character.png       # صورة وأفاتار المؤسس (أبو آيسل)
│   └── logo.png            # شعار AI Navigators البوصلة الذهبية
├── css/
│   └── style.css           # ملف التنسيقات والمؤثرات النيون والزجاجية
└── js/
    ├── data.js             # قاعدة بيانات البرومبتات والأطر
    ├── engine.js           # محرك توليد الأوامر ومحرك التدقيق
    └── app.js              # المنطق التفاعلي وتحديث الواجهة
```

---

## 🌐 خطوات رفع الموقع وتشغيله على GitHub Pages مجاناً (في دقيقتين)

بما أن المنصة تم بناؤها كـ Static Single Page Application، فهي **جاهزة 100% للعمل مباشرة على GitHub Pages أو Vercel أو Netlify دون الحاجة لأي خادم أو تكاليف استضافة**:

### الطريقة الأولى: عبر واجهة موقع GitHub (الأسهل بدون أوامر):

1. ادخل على حسابك في [GitHub.com](https://github.com) وأنشئ مستودعاً جديداً (New Repository) وسمّه مثلاً: `prompt-studio` واجعله **Public**.
2. داخل المستودع، اضغط على زر **Add file** ثم **Upload files**.
3. اسحب كامل محتويات مجلد `ai-navigators-prompt-studio` (الملفات: `index.html`, `README.md` والمجلدات: `assets`, `css`, `js`) وافلتها في المتصفح، ثم اضغط **Commit changes**.
4. ادخل إلى إعدادات المستودع **Settings** في الأعلى.
5. من القائمة الجانبية اليسرى اختر **Pages**.
6. تحت قسم **Build and deployment**:
   - في خانة **Branch** اختر `main` (أو `master`).
   - في خانة المجلد اختر `/ (root)`.
   - اضغط **Save**.
7. انتظر 60 ثانية، وستظهر لك رسالة باللون الأخضر تحتوي على رابط موقعك المباشر:  
   `https://<your-username>.github.io/prompt-studio/` 🎉

---

### الطريقة الثانية: عبر سطر الأوامر (Git Terminal):

افتح الطرفية داخل مجلد `ai-navigators-prompt-studio` ونفّذ الأوامر التالية:

```bash
git init
git add .
git commit -m "Initial commit - AI Navigators Prompt Studio"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/prompt-studio.git
git push -u origin main
```
ثم فعّل GitHub Pages من إعدادات المستودع كما في الخطوات 4-6 أعلاه.

---

## 📞 التواصل والدعم
* **المطور والمشرف العام:** أبو آيسل (Abo Aisel)
* **واتساب:** `01037489146` (+201037489146)
* **المجتمع:** AI Navigators — Guiding Intelligent Future & Community
