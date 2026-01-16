# 🚀 Automated Bug Bounty Suite (n8n Workflows)
                                                                                                                                                                                                                            
<img width="1727" height="951" alt="Screenshot 2026-01-16 002733" src="https://github.com/user-attachments/assets/4d74925c-d6fc-438e-b2cb-105aa3a60ef9" />
<img width="1737" height="943" alt="Screenshot 2026-01-16 002547" src="https://github.com/user-attachments/assets/76e35e1a-8a90-4f48-9612-3a04ef4a11ab" />
<img width="1720" height="942" alt="Screenshot 2026-01-16 002439" src="https://github.com/user-attachments/assets/f5256e51-fe87-4509-8492-863ced6451f4" />
<img width="1696" height="946" alt="Screenshot 2026-01-16 002333" src="https://github.com/user-attachments/assets/116a8a81-b69a-4edf-9d58-3b34a0036124" />
<img width="1698" height="941" alt="Screenshot 2026-01-16 002144" src="https://github.com/user-attachments/assets/addafd46-0f28-46e0-a20c-455a7117f6bd" />
<img width="1732" height="948" alt="Screenshot 2026-01-16 001709" src="https://github.com/user-attachments/assets/e1514d1d-ed05-4150-9f80-b94e7b9c2964" />


مجموعة أدوات متكاملة لأتمتة صيد الثغرات باستخدام n8n وذكاء Gemini الاصطناعي.

## 📋 محتويات المشروع (Workflows)
1. **The Warden: Scope Monitor** - مراقبة تحديثات HackerOne عبر Discord.
2. **The Sword: Nuclei Generator** - توليد قوالب Nuclei تلقائياً.
3. **The Herald: H1 Summarizer** - تلخيص تقارير الثغرات باستخدام AI.
4. **CVE Shoten** - متابعة أحدث الثغرات وتقييمها.
5. **Tip Harvestor** - تجميع نصائح الـ Bug Bounty في Google Sheets.

## ⚙️ متطلبات التشغيل
* تثبيت [n8n](https://n8n.io/).
* مفاتيح API لـ (Gemini, HackerOne, Discord Webhook) حسب الحاجة.

## 🚀 كيفية الاستخدام
1. قم بتحميل ملف الـ JSON الخاص بالأداة التي تريدها.
2. افتح واجهة n8n الخاصة بك.
3. اختر **Import from File** وارفع الملف.
4. قم بإعداد الـ Credentials الخاصة بك داخل العقد (Nodes).
