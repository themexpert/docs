---
title: Nefario
taxonomy:
    category: docs
visible: true
---

##Installation

![Nafario HomePage](module-position.jpg)

##Layout Configuration and Template Manager

Before starting with Nefario please take a look with the power of T3V3 framework and its Layout Configuration.

- [Backend Overview](https://www.youtube.com/watch?v=BhRBVcd-BTQ)
- [Layout Overview](https://www.youtube.com/watch?v=cqfRrWV-IPY)
- [Mega Menu](https://www.youtube.com/watch?v=cqfRrWV-IPY)
- [Adding Animation Effect for Megamenu](https://www.youtube.com/watch?v=2jIEfewSCRg)
- [How to install Google Analytics](https://www.youtube.com/watch?v=yiY7RlzA6kM)

###Slideshow

Home page slideshow comes with Revolution Slider. Please, see this video tutorial to understand revolution slider.

###Feature

![Nafario Feature](feature.jpg)

Title part comes with `ITL Feature` module along with font awesome and published on position name `feature-1, feature-2, feature-3, feature-4.` Just type the icon name (exclude: fa fa-), Title and Description. If you leave read more link blank then (read more) button will not visible on front-end.

![Nafario Feature Backend](feature-backend.jpg)

###Feature-Bottom

![Nafario Feature Bottom](feature-bottom.jpg)

Title part comes with custom html module and published on position name `feature-bottom.` Check the html code:

<textarea style="width: 550px; height: 180px";>
<div class="feature-list">
	<span class="fa fa-paper-plane-o fa-3x"> </span>
	<div class="feature-content">
		<h3>Best features ready to be used</h3>
		<p>Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus</p>
	</div>
</div>
</textarea>
###Portfolio

![Nafario Porftfolio](portfolio.jpg)

This parts comes by great Roksprocket module with Joomla article. At first create some article with category `Portfolio.` Put images on intro image box from Images and links tab. Image dimension I used 600px X 600px.

See the below configuration of Roksprocket module style `Mosaic`.

![Nafario Porftfolio Config](portfolio-config.jpg)

###Service

![Nafario Porftfolio Config](service.jpg)

Title part comes with `ITL Feature` module along with line icons and published on position name `service-1, service-2, service-3`. Just type the icon name (exclude: fa fa-), Title and Description.

Then click on `Advanced Ta`b and change `Alternative Layout` from `Default` to `service` and you're done.

![Nafario  Config](service_backend.jpg)

###About Us

![Nafario  About Us](about-us.jpg)

This part also comes by great Roksprocket module (list layout) with Joomla article. Category `service`.

![Nafario  About Us config](about-us-config.jpg)

###What Our Client's Say

![What Our Client's Say](testimonial.jpg)

This parts also comes by great Roksprocket module (features layout's showcase theme & module class suffix is testimonial) with Joomla article. Category `testimonial`.

![Testimonials Config](testimonials-config.jpg)

###Subscribe

![Nafario subscribe](subscribe.jpg)

###Our Clients

![Nafario our-client](our-client.jpg)

Our Clients made by Roksprocket module and style type strips. Need to create joomla article with category Partners. Use joomla intro image option to attach partners logo. Then see the configuration:

![Nafario our-client config](our-client-config.jpg)

###Latest From Blog

![latest-blog](latest-blog.jpg)

We used News Show Pro Gk5 to present Latest News from K2 with module class suffix `nefario-latest-post`.

###Photo Gallary

This part comes by shortcode. Image dimension is 600px X 600px. Below the html of shortcode:

<textarea style="width: 550px; height: 80px";>
{gallery}itl_demo/gallery{/gallery}
</textarea>

###Feature Tab

![feature-tab](feature-tab.jpg)

It comes by RokSprokcet module with Joomla article. At first create a category Main tab and publish 3 article with some text and images.

![feature-tab](feature-tab-article.jpg)

`Configuration:` Tab tables, icon and text comes by custom field. See the image below and on the right side you can see module configuration. You have to use module class suffix `feature-tab` to see the styles as in demo.

![feature-tab-config](feature-tab-config.jpg)

<textarea style="width: 450px; height: 100px";>
<span class="fa fa-magic main-tab-icon">&nbsp;</span>
<span class="main-tab-content">
<h3>Easily Customizable Theme</h3>
<p>Quisque vestibulum posuere gnissim tincidunt</p>
</span>
</span>
</textarea>

###Team Members

Its an article in nefario-demo category.See the shown code below

<textarea style="width: 650px; height: 500px";>
<div class="col-xs-12 col-sm-6 col-md-3">
<div class="staff-member">
<div class="staff-member-image"><img class="img-responsive" src="images/itl_demo/team/team-member5-big.jpg" border="0" alt="Staff Member" /></div>
<div class="staff-member-name">
<h4>Lance Dorgan</h4>
<p>Art Director</p>
</div>
<div class="staff-member-description">
<p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
</div>
<div class="staff-member-social">
<ul class="list-inline">
<li>
<div class="icon-wrapper"><a class="tooltip-on" href="http://www.facebook.com" title="Facebook"><em class="fa fa-facebook"> </em></a></div>
</li>
<li>
<div class="icon-wrapper"><a class="tooltip-on" href="http://www.twitter.com" title="Twitter"><em class="fa fa-twitter"> </em></a></div>
</li>
<li>
<div class="icon-wrapper"><a class="tooltip-on" href="http://www.google.com" title="GooglePlus"><em class="fa fa-google-plus"> </em></a></div>
</li>
<li>
<div class="icon-wrapper"><a class="tooltip-on" href="http://www.linkedin.com" title="Linkedin"><em class="fa fa-linkedin"> </em></a></div>
</li>
</ul>
</div>
</div>
</div>
</textarea>


###Pricing Table

Its an article in nefatio-demo category. See the shown code below

<textarea style="width: 650px; height: 350px";>
<div class="col-md-3 col-xs-12">
<div class="package">
<div class="package-header bg">
<h5>Basic</h5>
</div>
<div class="price">
<h4><span class="dollar-sign">$</span>15</h4>
<span class="price-meta"> / mo </span></div>
<ul>
<li><span class="fa fa-check"> </span>100GB Storage</li>
<li><span class="fa fa-check"> </span>All Themes</li>
<li><span class="fa fa-times"> </span>Access to Tutorials</li>
<li><span class="fa fa-times"> </span>Auto Backup</li>
<li><span class="fa fa-times"> </span>Extended Security</li>
</ul>
<a class="btn btn-primary pricing-btn" href="#"> Sign Up </a></div>
</div>
</textarea>


###T3 Documenation with video link
Here is the [documenation link](http://t3-framework.org/documentation.html) of T3 Framework.

At a galance [video](http://t3-framework.org/video-series.html) of T3 framework