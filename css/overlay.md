# overlay

```css
footer {
  position: relative;
  height: 30rem;
  padding: 7.8125rem 30% 0 30%;
  background: url("https://content.codecademy.com/courses/freelance-1/unit-6/footer.png")
    center center no-repeat;
  background-size: cover;
  text-align: center;
  font-size: 1.125rem;
  line-height: 1.4;
  color: white;
}

footer:before {
  /* Overlay */
  position: absolute;
  content: "";
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(255, 128, 0, 0.75);
}

footer * {
  position: relative; /* Makes elements display above overlay. */
}
```

## Reference

[Codecademy: Code Challenge "Paint Store"](www.codecademy.com)
