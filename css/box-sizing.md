# Inheriting box-sizing

```css
html {
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: inherit;
}
```

The CSS box model is a box that wraps around an HTML element and controls the design and layout.

The property `box-sizing` controls which aspect of the box is determined by the height and width properties. The default value of this property is `content-box`, which renders the actual size of the element including the content box; but not the paddings and borders.

The value `border-box`, on the other hand, renders the actual size of an element including the content box, paddings, and borders. The value `border-box` is recommended when it is necessary to resize the padding and border but not just the content.

## Reference

[Codecademy: Cheatsheets / Learn CSS / The Box Model](https://www.codecademy.com/learn/learn-css/modules/learn-css-box-model/cheatsheet)
[Codecademy: The Box Model in Chrome DevTools](https://www.youtube.com/watch?v=uQi8TK-GDO4&feature=emb_title&ab_channel=Codecademy)
[MDN box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
[CSS-TRICKS: Inheriting box-sizing Probably Slightly Better Best-Practice](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)
