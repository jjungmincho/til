# Nested Elements

CSS also supports selecting elements that are nested within other HTML elements

```html
<ul class="main-list">
  <li>...</li>
  <li>...</li>
  <li>...</li>
</ul>
```

The nested `<li>` elements are selected with the following CSS:

```css
.main-list li {
}
```

**Because of the more specific CSS selector (.description h5), the more general selector of h5 will not take hold.**

## Reference

[Codecademy CSS SETUP AND SELECTORS](www.codecademy.com)
