# breadcrumb

- a way for users to visualize their location on a website
- a secondary navigation bar that typically appears as horizontal text links, separated by the "greater than" symbol (>)
- Three types of breadcrumbs exist:
  - location - based on hierarchical structure of site
  - attribute - based on attributes of current page or item
  - path - unique to a user’s journey on the site
    <br>
- How to make a secondary navigation(aka breadcrumb navigation)?

```html
<!DOCTYPE html>
<html>
  <link rel="stylesheet" type="text/css" href="./styles.css" />

  <ul class="breadcrumb">
    <li>
      <a href="shopping">Shopping</a>
    </li>
    <li>
      <a href="fashion">Fashion</a>
    </li>
    <li>
      <a href="shoes">Shoes</a>
    </li>
    <li>
      <a href="flats">Flats</a>
    </li>
    <li>
      <a href="brown">Brown</a>
    </li>
  </ul>
</html>
```

```css
.breadcrumb > li {
  display: inline;
}

.breadcrumb li + li::before {
  padding: 10px;
  content: ">"; /* The code above adds a “/“ symbol inbetween all adjacent breadcrumbs. */
}

.breadcrumb a {
  text-decoration: none;
}

.breadcrumb a:hover {
  color: red;
}
```

## Reference

[Hubspot: 9 Breadcrumb Tips and Examples to Make Your Site Way Easier to Navigate](https://blog.hubspot.com/marketing/navigation-breadcrumbs)
[Codecademy: LEARN SECONDARY NAVIGATION / Simple Example of Breadcrumbs](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-improved-styling-with-css/modules/fecp-learn-secondary-navigation/lessons/ui-breadcrumb-nav/exercises/ui-breadcrumb-simple)
