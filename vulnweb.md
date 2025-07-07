# 🚨 Exploiting Vulnweb – Reflected XSS on `index.php`

## 🧠 Description

While exploring [Vulnweb](https://testphp.vulnweb.com), I encountered a **reflected Cross-Site Scripting (XSS)** vulnerability on the `index.php` page. After clicking the first link on the homepage, I noticed a **search bar** that accepts user input.

To test for XSS, I injected a simple payload into the search input field:

```html
<script>alert(8)</script>

📩 Contact
Feel free to connect with me for collaboration or discussion:
📧 kmahathir76@gmail.com
