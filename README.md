#- Site Web

Bienvenue sur le site Web de Hhbatiment !  
هذا الموقع يعرض معلومات الشركة، معرض الأعمال، ورمز QR للتواصل.

---

## Structure du site

- `index.html` : الصفحة الرئيسية للموقع.
- `style.css` : ملف التنسيقات الخاص بالموقع.
- `images/` : مجلد يحتوي على جميع الصور:
  - `logo.png` : شعار الشركة
  - `work1.jpg`, `work2.jpg`, `work3.jpg` : صور الأعمال
  - `qrcode.png` : رمز QR

---

## Modifier les images

1. ضع الصور الجديدة في مجلد `images/`.
2. غيّر أسماء الصور في الكود داخل `index.html` إذا لزم الأمر:
   ```html
   <img src="images/work1.jpg" alt="Travail 1" class="zoomable">
