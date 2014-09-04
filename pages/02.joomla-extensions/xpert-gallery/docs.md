---
title: Xpert Gallery
taxonomy:
    category: docs
visible: true
---

##Before you begin
Xpert Gallery doesn't work without some content, so the first thing you will need to do is create some articles or K2 items. If you have a Expert Explorer package that includes Xpert Gallery, you can view the demo content for an example.

You should first create a new category or select one that you wish to display articles from. Then place new articles into it with your content. Make sure to provide intro text and image, as these are what is used to display the snippets.

Once you have your selection of content ready, you can then start to work with Xpert Gallery.

##General Settings
![general](general.jpg)

**Content Source :&nbsp;**Choose your content source from where your content will come.

**Maximum Items :** Maximum item you want to show.

**Column :** Select the no. of columns.


###Filter and Sorting
**Sort enabled :** This option allows users to sort the gallery items.

**Sort element :** Define the sort elements.

###Display Settings
**Overview :** Show or hide overview informations of an item such as Title, Intro, Date etc.

**Overview position :** Select the position of the overview.

**Overview Style :** Select an overview style from our preset.

**Overview elements :** Select the elements to show in overview panel.

**Introtext :** Show or hide introtext

**Introtext limit :** Intro text charectar limit. Leave it blank to show all characters.


###Image Settings
**Item resize :** Resize and crop image. Don't set it's size below 420px as it is the lowest device size.
 
**Image width:** Specify image width in <code>px</code> value. Do not enter px on the field.

**Image height:** Specify image height in <code>px</code> value. Do not enter px on the field.

##Joomla Article Settings
![joomla](joomla.jpg)

**Category Filter :** Set whether article will fetch from all categories or specific categories.

**Category :** This option will only show if you set select in the Category Filter option. You can specify single or multiple categories here.

**Order :** Sort your article by selected order.

**Filter by Authors :** Filter all articles by authors.

**Featured Articles :** You can disable showing featured article or featured article only.

##K2 Article Settings
![k2](k2.jpg)

**Category Filter :** Select all or specific category.

**Categories :** This option will only show if you set select in the Category Filter option. You can specify single or multiple categories here.

**Children Categories :** This option allow you to fetch item from any clildren category you've selected.

**Item Ordering :** Select your article sorting order.

**Featured Items :&nbsp;**You can disable showing featured article or featured article only.

**Time range :&nbsp;**Set time range if ordering is set to 'most popular' or 'most commented'.


##Advanced Options
![advance](advance.jpg)

**Alternative Layout :** Use a different layout from the supplied module or overrides in the template.

**Module suffix :** This allows you to apply a unique CSS style to this module, if you desire and have the style set in the template.

**Automatic Module Id :** If you have multiple Xpert Scroller module in one page this option will add a unique module id to each.

**Module Id :&nbsp;**If you want to assign module id by yourself then <code>Disable</code> Automatic Module Id and insert your own id.

**Load jQuery :&nbsp;**This option allow you to enable or disable loading jquery on your site. If your template already load jQuery then disable this option otherwise you should enable it.

**jQuery Source :&nbsp;**This option allow you to load jQuery form 2 source, Google CDN or from Module Core. We recommend to user <code>Google CDN</code> for live site because it will load faster and save your bandwidth, for local testing/development you can load jQuery <code>From Module Core</code>

**Caching :** Select whether to cache the content of the module.

**Cache Time :** The time before the module is reached.

##Documentation & Support
In this section you will get the documentation and support informations.

![support](support.jpg)


##Troubleshooting
<em>**Do i need jQuery?**</em>


Yes this module requires it.


<em>**Image not showing, why?**</em>

Make sure your image path is ok and you have no <code>/</code> beginning of your image path. For K2 article it looks for article image not image from introtext, so make sure you have article image for each article.


<em>**Text not showing, why?**</em>

Make sure you have some text in your article and you've turned on <code>show introtext</code>&nbsp;option form module settings.


<em>**I can't save or apply admin settings, why?**</em>

We recommend to use Firefox 4+/Chrome/Safari/Opera for admin management. It has some problem saving settings from <code>Internet Explorer</code>.