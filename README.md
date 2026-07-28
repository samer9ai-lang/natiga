# 🎓 نتيجة الثانوية العامة
**Developed by: Samer Hassan** | [Instagram](https://www.instagram.com/samer9ai)

---

## 📁 الملفات

| الملف | الوظيفة |
|-------|---------|
| `index.html` | الموقع (Cloudflare Pages) |
| `data.json` | بيانات الطلاب (JSON) |

---

## 🚀 خطوات التركيب

1. روح على [dash.cloudflare.com](https://dash.cloudflare.com)
2. من القائمة الجانبية: **Workers & Pages** → **Create application** → **Pages** → **Upload assets**
3. ارفع الملفات (`index.html` + `data.json`)
4. اضغط **Deploy site**
5. هتاخد لينك زي: `https://your-site.pages.dev`

---

## 📝 إضافة بيانات الطلاب

افتح ملف `data.json` وعدل فيه:
```json
{
  "headers": ["رقم الجلوس", "الاسم", "المجموع", "النسبة", "الحالة"],
  "rows": [
    ["12345", "أحمد محمد", "380", "95%", "ناجح"],
    ["12346", "محمد علي", "250", "62%", "راسب"]
  ]
}
```

أو حوّل Excel لـ JSON من [convertcsv.com](https://www.convertcsv.com/)

---

## 📸 تابعني

- [Instagram - @samer9ai](https://www.instagram.com/samer9ai)

---

© 2026 **Samer Hassan** - جميع الحقوق محفوظة
