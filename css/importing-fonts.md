# @font-face

a way to import fonts directly into stylesheets

- Instead of using the font’s link in the HTML document, enter the link into the URL bar in the browser:

1. Go to 'Google Font'
2. Select this style
3. In selected family, go to 'Embed'
4. Either in `<link>` or `@import`, you will see the url link (starting as https://...)
   `<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">`
   `@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');`
5. Copy and past the link in the new tab
6. The browser will load the CSS rules. You will need to focus on the rules that are directly labeled as `/_ latin _/`. Some of the latin rules are on separate lines. You will need each of these.
7. Copy each of the CSS rules labeled latin, and paste the rules from the browser to the top of style.css.

- Loading an external font:

```css
@font-face {
  font-family: "Glegoo";
  src: url(../fonts/Glegoo-Regular.ttf) format("truetype");
}
```

`woff2` = `format('woff2')`
`tff` = `format('truetype')`

## Reference

[Codecademy: CSS TYPOGRAPHY Font-Face](www.codecademy.com)
[CSS Tricks: Using @font-face](https://css-tricks.com/snippets/css/using-font-face/)
