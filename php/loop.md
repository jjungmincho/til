# Loop 
```php
<?php

  while(have_posts()) {
    the_post(); ?>
    <h2><a href="<?php the_permalink(); ?>"><?php the_title(); ?></a></h2>
    <?php the_content(); ?>
    <hr>
  <?php }

?>
```

### `have_posts():`

Determines whether current WordPress query has posts to loop over.

### `the_post()`

Iterate the post index in the loop.

### `the_content( *string* $more_link_text = null, *bool* $strip_teaser = false )`

Display the post content.

## Source
[WordPress.org: have_posts](https://developer.wordpress.org/reference/functions/have_posts)

[WordPress.org: the_post](https://developer.wordpress.org/reference/functions/the_post/)

[WordPress.org: the_content](https://developer.wordpress.org/reference/functions/the_content/)

[Udemy: Become a WordPress Developer](https://www.udemy.com/course/become-a-wordpress-developer-php-javascript/)