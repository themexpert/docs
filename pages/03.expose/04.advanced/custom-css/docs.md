---
title: Adding CSS
taxonomy:
    category: docs
visible: true
---

## From admin panel

1. Go to *Extensions->Template Manager->Open Template (like: Tx_Appy)*
1. Click on *__Developer__* tab, Add your own CSS code to *__Custom CSS__* Box, click to save from right top and You are done!

![Custom CSS box](custom-css1.png)

## From file manager
We write all the styles for our template in LESS files which you'll get inside *template_folder => less*. If you are capable of writing LESS code you can edit LESS files here.

![LESS files](less-usage1.jpg)

But remember to enable LESS compiler from admin panel to compile this LESS codes into CSS. To enable go to template's admin panel's Developer tab where you'll find *__Compile less__* option, just make this enable.

![LESS compiler](less-usage2.jpg)

But if you are not familiar with LESS then there is css folder where you'll get all the compiled css files. You can make your style adjustments here also, but in this case *__LESS Compiler__* should remain *Disable*.

### Adding new LESS/CSS file

1. At first create new LESS file inside LESS folder. For example __new.less__
1. Open *__index.php__* Find this line ```$expose->addLink(array('typography.less','template.less'),'less');```
1. Add your file name into that line, for example ```$expose->addLink(array('typography.less','template.less','new.less'),'less');```

![Adding New Less file](custom-css2.png)

For CSS file just create it inside CSS folder, no need to add this file anywhere else.