![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/promo-popup.png)

To recreate such popup window on your site, you will need first to create [Static Block](Widgets_and_Static_Blocks/Static_Blocks) (content for this area actually), next - enable this function in Theme Options (Theme Options > Promo popup) and specify that we will show just created block. So go to Static blocks > Add new. 

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/popup-example.png)

\- Add row and select custom row layout 2/3+1/3. <br />
\- Add Text Block element to first column. We have used following code for this element: <br />
```
<h4><span class="active">Merry Christmas</span> from 8theme</h4>
May the wonder of Christmas shine in your hearts and bring warmth to those you love.[contact-form-7 id="7863" title=""]	
```

**Note:**
*To create form for this window we have used additional plugin [Contact Form 7](http://wordpress.org/plugins/contact-form-7/)*

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/contact-form-example.png)

Once static block was created go to Theme Options > Promo popup. Enable Promo popup and add the static block by using shortcode ```[block id= " "]```.