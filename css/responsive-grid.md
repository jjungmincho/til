# Responsive grid

```scss
.career__image-container {
  display: grid;
  grid-template-columns: repeat(3, 26vw);
  /* Use vmin(vw) for an equal sized box layout */
}

.career__image {
  object-fit: cover;
  width: 100%; /* Set the width to percentages, not px */
  height: 350px;
  padding: 10px 5px;
}
```

## Reference

[Things I’ve Learned About CSS Grid Layout](https://css-tricks.com/things-ive-learned-css-grid-layout/)
[Responsive grid in 2 minutes with CSS Grid Layout](https://travishorn.com/responsive-grid-in-2-minutes-with-css-grid-layout-4842a41420fe)
