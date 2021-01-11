These path components are shortcuts with specific meanings:

- `.` means the current path level (so if you're on `index.aspx` and you reference `./style.css` then the latter would have to be in the same folder as the former)
- `..` means one path level up (so if you're on `/somefolder/index.aspx` and you reference `../style.css` then the latter would have to be in the *parent folder* of `someFolder`)
- `/` means the root level (so `/style.css` is the same as `http://www.mysite.com/style.css`)
- `~` in ASP.NET means the server-side application root (so `~/index.aspx` would be translated to the URL of the `index.aspx` file that's in the application's root)