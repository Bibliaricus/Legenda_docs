To make theme compatible with the [WooCommerce Additional Variation Images plugin](https://woocommerce.com/products/woocommerce-additional-variation-images/) add the following code in child theme functions.php:
```
add_action('after_setup_theme', 'etheme_wc_image_slider_support', 2);
function etheme_wc_image_slider_support () {
    add_theme_support( 'wc-product-gallery-slider' );
}
```