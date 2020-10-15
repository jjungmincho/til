# Box-sizing

## content-box

- gives you the default CSS box-sizing behavior. If you set an element's width to 100 pixels, then the element's content box will be 100 pixels wide, and the width of any border or padding will be added to the final rendered width, making the element wider than 100px.

## border-box

```css
* {
  box-sizing: border-box;
}
```

- The code in the example above resets the box model to `border-box` for all HTML elements. This new box model avoids the dimensional issues that exist in the former box model you learned about.

In this box model, the height and width of the box will remain fixed. The border thickness and padding will be included inside of the box, which means the overall dimensions of the box do not change.

- Width now means 'content + padding + border'

## Reference

[Codecademy: CHANGING THE BOX MODEL](www.codecademy.com)
[Codecademy: The Box Model in Chrome DevTools](https://www.youtube.com/watch?v=uQi8TK-GDO4&feature=emb_title&ab_channel=Codecademy)
[MDN box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
