```js
const texts = {
  de: {
    texts: [
      { text: "Das Bot", location: ".header" },
      { text: "Das Ro-Bot", location: ".footer" },
    ],
  },
  da: {
    texts: [
      { text: "Båden", location: ".header" },
      { text: "Robotten", location: ".footer" },
    ],
  },
};
const locale = "da"; //skal kunne udskiftes i V(X)

//solution
texts[locale].texts.forEach((obj) => {
  document.querySelector(obj.location).textContent = obj.text;
});
```

```html
<html>
  <header class="header">UDSKIFTES</header>
  <p>bla, bla</p>
  <div class="footer"></div>
</html>
```

## V1

???
