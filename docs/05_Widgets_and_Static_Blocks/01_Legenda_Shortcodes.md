There are several shortcodes which can be used in Legenda theme inside posts and pages. You can look at examples, grab the code and learn more on each shortcode’s individual page of our demo [here](http://8theme.com/demo/legenda/shortcodes/).

`[alert]` insert the alert block with custom title and message; 

`[block id= " "]` inserts statick block;

`[dropcap]` inserts dropcap;

`[button]` inserts the button;

`[blockquote]` inserts the blockquote;

`[counter init_value=" " final_value=" "]` displays counter;

`[etheme_products title=" " ids="" skus="" type=" "  products=" " limit=" " columns=" " categories="" desktop="" notebook="" tablet="" phones=""]` displays products. Depending on attributes displays products as slider or grid;

`[gmaps]` inserts map with assigned attributes;

`[googlechart]` inserts chart with assigned attributes;

`[hr]` shortcodes to add divider;

`[icon]` inserts the icons;

`[checklist]` inserts the unordered list. Should be used together in a specific order;

`[portfolio]` inserts Recent Projects slider;

`[qrcode]` inserts the qrcode;

`[recent_posts]` inserts the slider of recent posts;

`[row][column]` insert a column. You can put any content inside column, using opening and closing shortcode. Should be used together in a specific order. Attribute size specifies size of column (one_half, one_third, one_fourth, two_third, three_fourth);

`[share]` inserts social icons (facebook, twitter, mail, pinterest, google+);

`[testimonials]` inserts the testimonials;

`[title subtitle=""]` inserts the title and subtitle line;

`[toggle_block][toggle]`shortcodes to create block with toggles. Should be used together in a specific order;

`[vimeo]`, `[youtube]` inserts the video from vimeo or youtube.


You can also use Visual Editor.
![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/shortcodes.png)
<br /><br />

**Pricing tables**

To create pricing tables you may add following code:
```html
<div class="pricing-table columns4">
	<ul>
		<li class="row-title">Free</li>
		<li class="row-price">$19</li>
		<li>512 mb</li>
		<li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
		<li><a href="#" class="button">Add to Cart</a></li>
	</ul>
	<ul>
		<li class="row-title">Econom</li>
		<li class="row-price">$29</li>
		<li>1 gb</li>
		<li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
		<li><a href="#" class="button">Add to Cart</a></li>
	</ul>
	<ul class="selected-column">
		<li class="row-title">Premium</li>
		<li class="row-price">$59</li>
		<li>2 gb</li>
		<li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
		<li><a href="#" class="button">Add to Cart</a></li>
	</ul>
	<ul>
		<li class="row-title">Advanced</li>
		<li class="row-price">$79</li>
		<li>4 gb</li>
		<li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
		<li><a href="#" class="button">Add to Cart</a></li>
	</ul>
</div>
```

Key lines of code are explained below:

`<div class="pricing-table columns4">` - general view of your table: namber of culumn, design. You may also use: columns3, columns5, style3, style2.

`<ul class="selected-column">` - hightlights column.

`<li class="row-title">` - add this class to set title for your column.

`<li class="row-price">` - add this class to add row with price.

You can also use WPBakery Page Builder element Pricing Table, select desired style and following code as content:
```
<ul>
<li class="row-title">Free</li>
<li class="row-price"><sup class="currency">$</sup>19<sup>00</sup><sub>per month</sub></li>
<li>512 mb</li>
<li>0.6 GHz</li>
<li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
<li><a class="button" href="#">Add to Cart</a></li>
</ul>
```