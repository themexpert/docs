---
title: Disable Module Height Calculation
taxonomy:
    category: docs
visible: true
---

Expose has a built-in module height calculation feature. It calculate maximum height of module on given position and assign the height to all modules on that position. This is a very useful feature styling, however some of your project might need to turned it off completely or for specific position.

Before doing any modification copy the file `equalheight.php` form `libraries/expose/widgets` to your `templates/widgets` folder.

## Turned off completely
Open `equalheight.php` file and add this code to line#19
```
protected $enabled = 0;
```

## For specific position
Example, you want to disable height calculation of Top module position. <br/> Find this line:
```
$js .= "jQuery('#top .column').equalHeight('.block');";
```
Comment this line by just adding `//` prefix and it will look like:
```
// $js .= "jQuery('#top .column').equalHeight('.block');";
```
Following this method you can turn off height calculation as many position you want.