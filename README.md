# Web-Development-day-30
CSS Variables 
CSS Variables (Custom Properties)
CSS Variables, also known as Custom Properties, allow you to store values (like colors, sizes, fonts, etc.) in reusable variables. This makes your CSS more maintainable and flexible.

🔧 Syntax
css
Copy
Edit
:root {
  --main-color: #3498db;
  --padding: 20px;
}
You define them inside a selector using -- prefix (typically inside :root to make them global).

✅ Usage
css
Copy
Edit
body {
  background-color: var(--main-color);
  padding: var(--padding);
}
Use them with the var() function.
