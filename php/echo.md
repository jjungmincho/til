# When to use 'echo' and when to not use 'echo' in WordPress function?

```php

the_title();
get_the_title();

the_ID();
get_the_id();

```
- If a WordPress function begins with the word "get", that means it's not going to echo anything for you. It's just going to return a value and it's up to you to use that value however you see fit. 
- On the other hand, if a function begins with the word "the", that means WordPress will indeed handle echoing and outputting it onto the page for you. 


## Source
[Udemy: Become a WordPress Developer](https://www.udemy.com/course/become-a-wordpress-developer-php-javascript/)