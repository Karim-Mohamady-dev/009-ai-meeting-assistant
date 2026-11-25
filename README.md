# Meetnote — 009-ai-meeting-assistant

يسجل Meetnote الاجتماعات، ويكتب ملخصا واضحا، ويحول القرارات إلى مهام بأسماء أصحابها ومواعيدها.

## ما هذا المشروع؟

صفحة هبوط ثنائية اللغة (العربية RTL والإنجليزية LTR) لـ Meetnote. Meetnote records meetings, writes a clear summary, and turns decisions into action items with owners and dates.

## التشغيل محليا

```bash
npm install
npm run dev
npm run build
```

## المزايا

- مبدل لغة ظاهر، والتفضيل محفوظ في localStorage
- الترجمات في `locales/en/common.json` و `locales/ar/common.json`
- نموذج تجربة مجانية مع تحقق من البريد
- أقسام: البطل، المزايا، كيف يعمل، آراء نموذجية، الأسعار، الأسئلة الشائعة، الدعوة الأخيرة
- قسم كشف الشعار (tagline reveal) مع تحريك كلمة بكلمة
- الأسعار غير المؤكدة تظهر كعناصر نائبة `{{price}}`

## ملاحظات

- البيانات المعروضة تجريبية وموسومة كعينات.
- لا توجد أرقام أو شهادات مخترعة.
