# grid

- three major components: columns, gutters, and margins
  - column: the vertical sections that span the width of a page (12-16 columns)
  - gutter: the negative space between each column ensuring the columns don’t run together
  - margin: appear on the left and right sides of the column-based grid to ensure the content of your designs doesn’t match up to the edges of the browser window
    <br>
- `grid-template-columns` defines the number and sizes of the columns of the grid
- `grid-template-rows` defines the number and sizes of the rows of the grid
- `grid-template` is a shorthand for defining both `grid-template-columns` and `grid-template-rows` in one line
- `grid-gap` puts blank space between rows and/or columns of the grid
- `grid-row-start` and `grid-row-end` makes elements span certain rows of the grid
- `grid-column-start` and `grid-column-end` makes elements span certain columns of the grid
- `grid-area` is a shorthand for `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end`, all in one line
  <br>
- `grid-template-areas` specifies grid named grid areas
- grid layouts are two-dimensional: they have a row, or inline, axis and a column, or block, axis.
- `justify-items` specifies how individual elements should spread across the row axis
- `justify-content` specifies how groups of elements should spread across the row axis
- `justify-self` specifies how a single element should position itself with respect to the row axis
- `align-items` specifies how individual elements should spread across the column axis
- `align-content` specifies how groups of elements should spread across the column axis
- `align-self` specifies how a single element should position itself with respect to the column axis
- `grid-auto-rows` specifies the height of rows added implicitly to the grid
- `grid-auto-columns` specifies the width of columns added implicitly to the grid
- `grid-auto-flow` specifies in which direction implicit elements should be created

## Reference

[Codecademy: GRIDS AND SPACING / Grid Anatomy](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-making-a-website-responsive/modules/fecp-learn-responsive-design-grids-and-spacing/lessons/grids-spacing/exercises/grids-spacing-anatomy)
[Codecademy: CSS GRID ESSENTIALS / Review](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-making-a-website-responsive/modules/fecp-learn-css-grid/lessons/css-grid-i/exercises/review)
[Codecademy: ADVANCED CSS GRID / Review](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-making-a-website-responsive/modules/fecp-learn-css-grid/lessons/css-grid-ii/exercises/review-ii)
