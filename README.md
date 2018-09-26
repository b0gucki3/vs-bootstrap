# vs-bootstrap
WordPress Visual Composer and Bootstrap integration.

Point WordPress to the new styles in functions.php
```
wp_enqueue_style('bootstrap', get_template_directory_uri() . '/bootstrap/css/bootstrap.min.css');
wp_enqueue_script('bootstrap', get_template_directory_uri() . '/bootstrap/js/bootstrap.min.js', array('jquery'), false, false);

wp_enqueue_style('font1', 'https://fonts.googleapis.com/css?family=Merriweather');
wp_enqueue_style('nasc', get_template_directory_uri() . '/styles/css/style.css');
```
