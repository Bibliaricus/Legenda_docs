If you want to receive feedback from your visitors, having a Contact Us page on your site is an easy way to make that happen. Go to Pages > Add new, and create a page called "Contact Us" (or whatever you wish to call it), and set the page template (under page attributes) to Contact Page. It inserts form for feedback on page. 

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/contact-page-template.png)

There are two variant of contacts page: default and custom. You can select it in Theme Options > Contact Form > Contact Page layout.

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/contact-page-layout.png)

Add other content for page. We have used the following (add code on Text tab in Classic Editor mode):

**Default Contact Form**
```
<h3>Place for nice title</h3>
But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness.
<h6>Contact informations</h6>
30 South Park Avenue
San Francisco, CA 94108
USA
<strong>Phone:</strong> (123) 456-7890
<strong>Fax:</strong> +08 (123) 456-7890
<strong>Email:</strong> <a href="#">contact@companyname.com</a>
<strong>Web:</strong> <a href="#">companyname.com</a>
```

![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/default-contact-us-content.png)
![](//olya.8theme.com/theme-docs/legenda-docs/docs/imgs/default-contact-us-page.png)

**Note:** <br />
You need to get [API key](https://developers.google.com/maps/documentation/javascript/get-api-key) then go to Theme Options > Contact Form > Google Map API and add the key.

**Custom Contact Form**
```
[vc_row][vc_column width="1/2"][vc_gmaps type="m" zoom="13" link="https://maps.google.com/?ll=51.513331,-0.125557&spn=0.001923,0.005405&t=m&z=19" size="300" bubble="1"][vc_column_text]
<h3>London store</h3>
But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born.
<h6>Contact informations</h6>
30 South Park Avenue
San Francisco, CA 94108
<strong>Phone:</strong> (123) 456-7890
<strong>Fax:</strong> +08 (123) 456-7890
[/vc_column_text][/vc_column][vc_column width="1/2"][vc_gmaps type="m" zoom="12" link="https://maps.google.com.ua/maps?hl=uk&ll=34.060797,-118.249463&spn=0.002551,0.005405&t=m&z=19&layer=c&cbll=34.060797,-118.249463&panoid=aqQH-JKCWE3KL-2Qw5OAKQ&cbp=12,232.53,,0,9.81" size="300" bubble="1"][vc_column_text]
<h3>Los Angeles store</h3>
But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born.
<h6>Contact informations</h6>
30 South Park Avenue
<strong>Email:</strong> <a href="#">contact@companyname.com</a>
<strong>Web:</strong> <a href="#">companyname.com</a>
[/vc_column_text][/vc_column][/vc_row]
```

To add your email for contact form, navigate to Theme Options > Contact Form.

Also, you can use Default page template, and add a contact form using the [Contact Form 7 plugin](https://wordpress.org/plugins/contact-form-7/).
