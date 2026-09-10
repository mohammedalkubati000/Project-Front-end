# 🌐 BOM - Browser Object Model

**إذا فهمت DOM، فالخطوة التالية المنطقية هي معرفة BOM.**

---

## 📘 ما هو BOM؟

**BOM** اختصار لـ **Browser Object Model**  
ويُقصد به: **نموذج كائني للمتصفح** – أي الأجزاء التي توفرها المتصفحات مثل Google Chrome و Firefox والتي **ليست جزءًا من HTML** لكن JavaScript تتفاعل معها.

---

## 🧠 الفرق بين DOM و BOM:

| DOM                                                      | BOM                                                       |
| -------------------------------------------------------- | --------------------------------------------------------- |
| يتعامل مع محتوى الصفحة (HTML)                            | يتعامل مع خصائص المتصفح                                   |
| يسمح لك بالتعديل على العناصر مثل `<div>`, `<input>`, ... | يسمح لك بالتعامل مع النافذة، العنوان، الروابط، الوقت، إلخ |
| مثال: `document.getElementById("title")`                 | مثال: `window.alert("Hi!")`                               |

---

## 🌐 أشهر كائنات BOM:

| الكائن                               | وظيفته                                       |
| ------------------------------------ | -------------------------------------------- |
| `window`                             | الجذر الرئيسي لكل شيء في المتصفح             |
| `navigator`                          | معلومات عن المتصفح (الاسم، اللغة، الجهاز...) |
| `screen`                             | معلومات عن الشاشة (الطول والعرض...)          |
| `location`                           | معلومات عن رابط الصفحة الحالي                |
| `history`                            | التنقل بين الصفحات التي زارها المستخدم       |
| `alert()` / `confirm()` / `prompt()` | نوافذ منبثقة للتفاعل مع المستخدم             |
| `setTimeout()` / `setInterval()`     | تشغيل وظيفة بعد وقت معين أو بشكل متكرر       |

---

## 🎯 أمثلة على BOM:

### ✅ عرض رسالة:

```javascript
alert("Welcome!");
```
---

#### ✅ Examples of BOM usage:

* Alert message: alert("Welcome!")
* Redirect: location.href = "https://google.com"
* Open new window: window.open("https://example.com")
* Get screen size: console.log(screen.width, screen.height)

#### 🔧 Common BOM Objects:

* window – The global browser window
* navigator – Info about the browser/device
* location – URL and redirection
* history – Browsing history navigation
* screen – Screen size and resolution
* alert(), confirm(), prompt()
* setTimeout(), setInterval()

---




