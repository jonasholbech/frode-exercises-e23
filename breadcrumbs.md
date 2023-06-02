breadcrumb generator

- sidste er ikke et link
- de får et array med name/link objekter

```js
const bc = [
  { name: "Hvidevarer", link: "/hvidevarer" },
  { name: "Vaskemaskiner", link: "/hvidevarer/vaskemaskiner" },
  { name: "Bosch", link: "/hvidevarer/vaskemaskiner/bosch/" },
];
```

```html
<ol>
  <li><a href="/hvidevrarer">Hvidevarer</a></li>
  <li><a href="/hvidevarer/vaskemaskiner">Vaskemaskiner</a></li>
  <li>Bosch</li>
</ol>
```
