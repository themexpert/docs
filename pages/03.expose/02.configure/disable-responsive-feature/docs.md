---
title: Disable Responsive Feature
taxonomy:
    category: docs
visible: true
---

## Editing XML File
Open *__templateDetails.xml__*, find this line
    <field name="responsive-enabled" type="hidden" default="1" pretext="ENABLE" label="RESPONSIVE_LABEL" description="RESPONSIVE_DESC" />

replace it with the following one
    <field name="responsive-enabled" type="toggle" default="1" pretext="ENABLE" label="RESPONSIVE_LABEL" description="RESPONSIVE_DESC" />

Go to*__Template Manager__*, Select the template, inside *__Template Configuration__*page's *__Layout__*tab find *__Responsive Layout__*option and disable this.

## Editing PHP File
Open *__index.php__*, go to the bottom of the file, search for the following lines and delete or comment
    <?php /** Begin Off-canvas **/ if($expose->countModules('offcanvas')): ?>
        <div id="offcanvas" class="uk-offcanvas">
            <div class="uk-offcanvas-bar">
                <?php $expose->renderModules('offcanvas'); ?>
                </div>
        </div>
    <?php /** End Offcanvas **/ endif;?>


## Editing Less File
Open *__responsive.less__*, comment all lines except the following one
    @import "../../../libraries/expose/interface/less/responsive-utilities.less";
    
Finally delete the *__cache__* and full refresh your browser.