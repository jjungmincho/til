# overflow property

```css
div.ex1 {
  overflow: scroll;
}
div.ex2 {
  overflow: hidden;
}
div.ex3 {
  overflow: scroll;
}
div.ex4 {
  overflow: visible; /*default*/
}
```

- When you want to hide scroll, you can use `overflow: hidden`

- Why do you need this? **Margin Collapse**
  Horizontal margins add, so the total space between the borders of adjacent elements is equal to the sum of the right margin of one element and the left margin of the adjacent element. Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.

## Reference

[Codecademy THE BOX MODEL](www.codecademy.com)
