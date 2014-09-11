---
title: Template Modification
taxonomy:
    category: docs
visible: true
---

## Changing the template name
You can copy any template from Joomla admin panel. Follow these steps to copy the template

1. Go to *__Template Manager__*, enter into *__Templates__* section.
1. Enter into the template you want to copy.
1. From the bottom right side of this page you will find *__Copy Template__* section. Here give the name of your template and click on the *__Copy template__* button.
1. Now go back to template manager Styles section and here you will find the copied template.
1. You're Done!

<p class="alert alert-warning"><strong>Warning:</strong> After copying the new template, some module positions may need to assign/configure again and also you have to re-configure template back-end options as previous.</p>

## Adding css
Our powerful Expose framework gives you the ability to add CSS from admin panel's template settings. Just go to
```Template Settings => Developer => Custom CSS``` Or you can also write css from template folder => css and edit template.css or any other css file you want.

## Changing logo size
Logo size depends on your logo image size, so if you want bigger size, just upload a big logo image and it will calculate the size itself.
Sometimes logo doesn't take it's full width and height. For example if you publish logo in top-1 position and you publish 3 modules in top position, from default setting all the module will take width of 4 grid each. But if the logo is bigger than the width allocated then it will not take it's full width &amp; height. In this case you have to assign more grid to it.
Go to ```template settings => Layouts```. In this section you will be able to set the width of any module positions.

## Disabling component from any page
In order to disable component from any page please go to ```Template Settings => Advanced => Component Disable``` & enable this option.
Beside this option you will see a input field *__Component disable menu IDs__* here give the menu ID for that corresponding page.

## Changing container width of templates
Open *__"responsive-1200px-min.less"__* and go to this line
<pre>
// Fixed grid
#grid > .core(100px, 0px);
</pre>
Change 100 to any other value you want. It will decrease or increase the width of each grid of your template.

## Changing background image for different module positions
At first paste your image into ```template folder => images => backgrounds folder``` Now login to your site's admin panel, go to ```Template settings => Styles => Custom Style``` & enable it. Now bottom of it there is several option for specific module position. Select that image from *__Background Image__* dropdown. This way you can select different images for different positions.