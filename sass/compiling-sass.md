# Compiling Sass

### [1] Using Sass Extension

1. You need to download Sass extension in VS Code
2. Save <\_style.scss> in <styles> folder ←tells Sass to hold off on compiling the file individually and instead import it.
3. Click 'watch sass' button at the bottom of the screen
4. To import a file named **`_variables.scss`** in the main/global SCSS file, add the following line of code:

```scss
@import "variables";
```

### [2] how to compile it to CSS by typing the following command in the terminal and pressing enter:

```bash
sass main.scss main.css
```

The `sass` command above takes in two arguments:

1. The input (**main.scss**)
2. The location of where to place that output (**main.css**)
