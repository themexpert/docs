---
title: Egan
taxonomy:
    category: docs
visible: true
---

This documentation will flip you  through the step by step how to install and setup the incredible Egan WordPress theme.  Egan is an responsive news and magazine theme for WordPress lovers, those who are looking for a indispensable media to share their discoveries and latest news.

This beautiful news WordPress theme is neat and clean, well-equipped with innumerous technologies Like Bootstrap 3, Less, Newskit, and a lot more.

## Installation

Follow our [installation guideline](../installation) if you are having problem to install the theme.

## Homepage Settings (Without Installing Demo Data)

*__Step 01__*  
If you want to install Tx Next theme in your website except demo data,  you have to first create a page from `Admin Panel >> Pagers >>  Add New Page` You can see in the image below I have created page called “Home”. 

![Create Page](create-page.png)

*__Step 02__*  
When you have created your page, now its time change the page reading for Tx News. To change the page reading for newly created page head to the `Admin Panel >> Settings >> Reading` Check the box next to A static page (select below) under Front Pager display. and select your page in which you display Tx Next content. In my turn Its Home.

![Front page display settings](frontpage-display.png)

## Homepage Settings (After Installing Demo Data)

After finishing all installation process, the very first setting, we recommend to define is Home Page. To have Homepage the same as Tx Next demo, change the following setting:

- Head over to __Admin Panel >> Settings >> Reading__
- Check the box next to __A static page (select below)__ under Front Pager display. Select __Homagepage 1__ under the Front Page title. Flip through the image below.

![Front page display settings](frontpage-display.png)

## Layout Structure

This screenshot will give a quick overview of the layout structure of Tx Next WordPress theme.

![Home Layout Structure](home.jpg)

### Header Settings

The headers contains a couple of widget. To set the header as the Demo looks, please flip through the instruction carefully: 

### Primary Menu Settings
Navigate to `Dashboard >> Appearance >> Menus` and create the primary menu. The primary Menu Look like the following.

![Primary Menu](primary-menu.jpg)

__Frontend View__  
![Primary Menu Frontend](primary-menu-front.jpg)

### Max Mega Menu Theme Import

Primary menu is using Max Mega Menu theme to give engaging megamenu. If you want to have menu like our Demo theme. Head over to `Dashboad >> Appearance >> Max Mega Menu >> Tools`. Open up  __max-megamenu.txt__ from Themes to dummy-data folder. Copy the entire code of max-megamenu.txt and paste it in __Import Theme__ text field.

![Max Megamenu](max-megamenu.png)

### Search box Settings

Navigate to `Dashboard >> Appearance >> Widgets` and place the Search widget into Search box widget area.

![Search](search.png)

### Slideshow Settings

Slide show is another interactive layout of Newskit. Just navigate to `Dashboard >> Appearance >> Widgets >> Slideshow`, then drag & drop Newskit into Slideshow as shown below:

![Slideshow](slideshow.jpg)

__Frontend View__  
![Slideshow Frontend](slideshow-front.jpg)

### Main Content – Newskit - Static Layout 1

Navigate to `Dashboard >> Appearance >> Widgets >> Main Content`, drag & drop Newskit into Main Content.

![NewsKit Static Layout 01](maincontent-st1.jpg)

__Frontend View__  
![NewsKit Static Layout 01 Frontend](maincontent-st1-front.jpg)

### Main Content –  Ads Banner

*__Step 01__*  
Go to `Dashboard >> Media >> Add New`

Back-end Settings

- Upload Image or select existing image
- Copy the link of the image

![Media Library](media1.png)

*__Step 02__*  
Head over WordPress `Administration >> Appearance >> Widgets`

- Click and drag Text Widget to Main Content

After that use the HTML code below , paste them into Text widget to display the image and the recommend size for the image on the ads banner is `770 x 140`

```
<a href="http://www.themexpert.com/joomla-templates/spaghetti" target="_blank"><img src="Your_Image_source_goes_here" /></a>
```

__Frontend View__

![MainContent Ad](maincontent-ad1.png)

### Main Content – Newskit - Static Layout 2

Navigate to `Dashboard >> Appearance >> Widgets > Main Content`, drag & drop Newskit into Main Content.

![MainContent widgets](maincontent-st2.jpg)

__Frontend View__

![Maincontent Static Layout 02 Frontend](maincontent-st2-front.jpg)

### Main Content – Newskit - Dynamic Layout 1

Navigate to `Dashboard >> Appearance >> Widgets > Main Content`, drag & drop Newskit into Main Content.

![MainContent widgets](maincontent-dy1.jpg)

__Frontend View__

![Maincontent Dynamic Layout 01 Frontend](maincontent-dy1-front.jpg)

## Sidebar Setting

The sidebar areas are used to display the widgets in the secondary column. To get the image sidebar like our demo site, please add the following widget with content and setting, I am going to describe you.

### Sidebar – Newskit: Most Popular ( Static Layout 4 )

Navigate to `Dashboard >> Appearance >> Widgets >> Sidebar` drag & drop Newskit into Sidebar.

*__Backend Settings__*  
![Sidebar Most Popular](sidebar-st4.jpg)

__Frontend View__  
![Sidebar Most Popular Front](sidebar-st4-front.jpg)

### Sidebar–  Ads Banner (Position 1,3,5)
*__Step 01__*  
Go to `Dashboard >> Media >> Add New`

- Upload Image or select existing One
- Copy the link of the image

*__Step 02__*  
Head over WordPress `Administration >> Appearance >> Widgets` Click and drag Text Widget to Sidebar.

After that use the HTML code below , paste them into Text widget to display the image and the recommend size for the image on the ads banner is `370 x 370`
```
<a href="#"><img src="Your_Image_source_goes_here" /></a>
```

__Frontend View__  
![Sidebar Ads widget](sidebar-ad.jpg)

## Footer 1

Head to `Administrator >> Appearance >> Widgets >> Footer 1` Find Text and Custom Menu Widget from the list of the Widgets, click and drag it to Footer 1.

__Backend View__  
![Footer1 section](footer1.jpg)

__Frontend View__  
![Footer1 section Front](footer1-front.jpg)

## Footer 2

Head to `Administrator >> Appearance >> Widgets >> Footer 2` Find Text and Custom Menu Widget from the list of the Widgets, click and drag it to Footer 2.

__Backend View__  
![Footer2 section](footer2.jpg)

__Frontend View__  
![Footer2 section Front](footer2-front.jpg)

## Footer 3

Head to `Administrator >> Appearance >> Widgets >> Footer 3` Find Text Widget from the list of the Widgets, click and drag it to Footer 3.

__Backend View__  
![Footer3 section](footer3.jpg)

__Frontend View__  
![Footer3 section Front](footer3-front.jpg)

## Customizer Settings

There are several customizing options in theme customizer like Logo settings, Presets, Social Links etc, to get those settings go to `Administrator >> Appearance >> Customize`

![Customizer Options](customizer.jpg)
