# 📘 ما هو DOM؟

**DOM** اختصار لـ **Document Object Model** ويُقصد به "نموذج كائني للوثيقة" — يعني ببساطة:

> هو تمثيل هيكلي للصفحة HTML (كأنك شايف الصفحة على شكل شجرة من العناصر - شجرة DOM).

---

## 🧠 تخيل الصفحة هكذا:

لو عندك صفحة HTML مثل:

```html
<html>
  <body>
    <h1>Hello</h1>
    <p>Welcome</p>
  </body>
</html>
```

فـ JavaScript ترى الصفحة ككائن يحتوي على:

```
document
 └── html
     └── body
         ├── h1
         └── p
```

كل عنصر في الصفحة (مثل `h1`, `p`, `div`, `form`, ...) يعتبر **Node** أو **عنصر في الشجرة**.

---

## 🎯 لماذا نستخدم DOM في JavaScript؟

للتفاعل مع الصفحة! مثل:

| ما تريد فعله        | كيف يتم بالـ DOM                           |
| ------------------- | ------------------------------------------ |
| قراءة قيمة من input | `document.getElementById("myInput").value` |
| تغيير نص في عنصر    | `element.innerText = "New Text"`           |
| إخفاء/إظهار عنصر    | `element.style.display = "none"`           |
| إنشاء عنصر جديد     | `document.createElement("div")`            |
| حذف عنصر            | `element.remove()`                         |

---

## 💡 مثال عملي:

```html
<p id="demo">Hello</p>
<script>
  document.getElementById("demo").innerText = "Changed using DOM!";
</script>
```

---

## 🛠️ أدوات DOM الأساسية:

| الوظيفة     | الطريقة                                        |
| ----------- | ---------------------------------------------- |
| اختيار عنصر | `getElementById`, `querySelector`              |
| قراءة نص    | `innerText`, `textContent`                     |
| تغيير HTML  | `innerHTML`                                    |
| الانتقال    | `parentNode`, `children`, `nextElementSibling` |


