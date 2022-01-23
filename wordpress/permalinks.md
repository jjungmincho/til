# Permalinks in WordPress Admin Dashboard

- When you make a new plugin in the WordPress Admin using PHP, you need to manually update the WordPress site that you made a new post type.
- How?
1. Create a folder named 'mu-plugin' (means A must-use plugin that will always be activated by default)
2. Create a php file 
3. Write a function 
- Here is the example:
```php
<?php
 
function university_post_types() {
  // Program Post Type
  register_post_type('program', array(
    'show_in_rest' => true,
    'supports' => array('title', 'editor'),
    'rewrite' => array('slug' => 'programs'),
    'has_archive' => true,
    'public' => true,
    'show_in_rest' => true,
    'labels' => array(
      'name' => 'Programs',
      'add_new_item' => 'Add New Event',
      'edit_item' => 'Edit Program',
      'all_items' => 'All Program',
      'singular_name' => 'Program'
    ),
    'menu_icon' => 'dashicons-awards'
  ));
}
 
add_action('init', 'university_post_types');
```
4. Add new pages in the WordPress Admin
5. Go to "Settings > Permalinks"
6. Click "Save Changes" 
7. Refresh the website and check the page is now loaded 

## Source
[Udemy: Become a WordPress Developer](https://www.udemy.com/course/become-a-wordpress-developer-php-javascript/)
