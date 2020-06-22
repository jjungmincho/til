# Switch statement

- Use for multiple if checks
- Use for enum-like value check
- Use for multiple type checks in TS

```jsx
const browser = 'IE':
switch (browser0 {
	case 'IE':
		console.log('go away!');
		break;
	case 'Chrome':
	case 'Firefox':
		console.log('love you!');
		break;
	default:
		console.log('same all!');
		break;
}
```

It means if the browser is IE, console shows 'go away' and then stops. If the browser is Chrome, console will show 'love you' then stops. If the browser is something else, the console will show 'same all' and then stops.
