## Updates to Mini Finance Project

### Day 1: Implement Footer

Implemented footer (HTML/CSS):

```html
<p>Mini Finance v1.0 — Deployed on November 9, 2025 - By Ntando Mvubu</p>
```


### Day 2: Dynamic Date Display

Changed the date from static to dynamic:

```html
<p>Mini Finance v1.0 — Deployed on <span id ="date"></span> - By Ntando Mvubu</p>
```

### Day 3: Polish & Accessibility

Tweaked footer font size/spacing; ensured contrast ≥ AA

```css
.footer-text {
  font-size: 0.85rem;
  line-height: 1.5;
  color: #333;
  margin: 5px 0;
}
```

### Day 4: Health Page

Added a simple /healthz page returning “OK” : [health.html](health.html)


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Health Check</title>
</head>
<body>
  OK
</body>
</html>
```

---