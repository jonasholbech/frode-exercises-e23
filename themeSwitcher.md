# Theme Switcher

```html
<body data-theme="hawaii"></body>
```

```css
[data-theme="hawaii"] {
  --bg: hotpink;
}
[data-theme="light"] {
  --bg: white;
}
[data-theme="dark"] {
  --bg: black;
}

header {
  background: var(--bg);
}
```
