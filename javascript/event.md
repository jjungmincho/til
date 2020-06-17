# Events and event handlers

An event is anything that happens in the website such as click, resize, submit, input change, load, before, closing etc. You can intercept this event.

```js
const title = document.querySelector9"#title");

function handleResize(){
	console.log("I have been resized")
}

window.addEventListener("resize', handleResize());
```

`()` will call the function immediately. Super important not to do this way!
