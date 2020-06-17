# toggle

toggle ( String [, force] ): a function

```jsx
const title = document.querySelector("#title");

const CLICKED_CLASS = "clicked";

function handleClick() {
	title.classList.toggle(CLICKED_CLASS);
}

function init() {
	title.addEventLisner("click", handleClick;
}
init();
```

This means to check:

if the class is there, you will add it

if the class is not there, you will remove it
