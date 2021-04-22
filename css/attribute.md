# Attribute in CSS

The attribute selector can be used to target HTML elements that already contain attributes. Elements of the same type can be targeted differently by their attribute or attribute value. 

`type[attribute*=value]`

```html
<img src='/images/seasons/cold/winter.jpg'>
<img src='/images/seasons/warm/summer.jpg'>
```

```css
img[src*='winter'] {
  height: 50px;
}
 
img[src*='summer'] {
  height: 100px;
}
```

## Reference
[CSS Selectors | Codecademy](https://www.codecademy.com/paths/front-end-engineer-career-path)