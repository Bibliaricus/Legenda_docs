To create footer we have used [Static Blocks](/Widgets_and_Static_Blocks/Static_Blocks) - a great feature implemented in Legenda theme to facilitate compositing of sidebars, footer, and other areas.

You can add it using 8theme - Static Block widget or with the help of shortcode `[block id=" "]`.

Below we'll explain how to use Static Blocks in terms of Footer areas (Footer 1 and Footer 2 widget areas).

**First Footer row**

Go to Appearance > Widgets and create custom widget areas: <br />
\- Random Products - add WooCommercee Random Products widget; <br />
\- On Sale - add WooCommerce On-Sale widget; <br />
\- Flickr - add 8theme Flickr Photos. <br />

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/products-custom-widget-areas.png)

Navigate to Static Block > Add new. Name it as Footer Top or whatever you want. Using WPBakery Page Builder add row with custom layout 1/4 + 1/4 + 1/4 + 1/4. 

Add Widgetised Sidebar element into columns and select newly created custom widget areas: Random Products, On Sale, Flickr Photos and Recent Posts element.

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/footer-top-example.png)

Publish your Static Block.

Then go to Appearance > Widgets, add 8theme - Statick Block widget to Footer 1 area and select Footer Top block from drop-down list.

**Second Footer row**

Go to Appearance > Widgets and create 2 custom widget areas.The first one - About Company - includes Text widget with following content: 

``` 
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod aliqua.</p>
<h6>Contact information</h6>
30 South Park Avenue
San Francisco, CA 94108
Phone: +78 123 456 789
<br><br>
<ul class="links hidden-phone pay-icons">
   <li><a href="#"><img alt="" src="[template_url]/images/assets/paypal.png" /></a></li>
   <li><a href="#"><img alt="" src="[template_url]/images/assets/mastercard.png" /></a></li>
   <li><a href="#"><img alt="" src="[template_url]/images/assets/visa.png" /></a></li>
   <li><a href="#"><img alt="" src="[template_url]/images/assets/discover.png" /></a></li>
</ul> 
```
The second one - Twitter - includes 8theme - Twitter Feed (read more about in Widget item of this [documentation](/Widgets_and_Static_Blocks/Widgets_and_Custom_Widget_Areas)).

Now go to Static Block > Add new. Name it as Footer Bottom or whatever you want. Using Visual Composer add row with custom layout 1/4 + 1/6 + 1/6 + 1/6 + 1/4. 

Add Widgetised Sidebar element into first column and select our About Company custom widget area.

Add Widgetised Sidebar into last column and select Twitter custom widget area.

Into second, third and fourth columns you may add text blocks with following content:

``` 
<h3 class="widget-title">OUR STORES</h3>
<ul class="footer_menu">
	<li><a href="#">London</a></li>
	<li><a href="#">Singapore</a></li>
	<li><a href="#">Paris</a></li>
	<li><a href="#">Moscow</a></li>
	<li><a href="#">Berlin</a></li>
	<li><a href="#">Milano</a></li>
	<li><a href="#">Amsterdam</a></li>
</ul>
``` 

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/footer-bottom-example.png)

Publish your Static Block.

Then go to Appearance > Widgets, add 8theme - Statick Block widget to Footer 2 area and select Footer Bottom block from drop-down list.

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/footer-widgets-02.png)

Take a look on frontend. You got the same footer as on our [demo](http://8theme.com/demo/legenda/).