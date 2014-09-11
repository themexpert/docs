---
title: Adding New Social icons in Social Widget
taxonomy:
    category: docs
visible: true
---

Open *__templateDetails.xml__*, scroll down to *__widgets settings__* and search for the following line

	<field name="spacer-social" type="spacer" text="SPACER_SOCIAL_WIDGET_LABEL" description="SPACER_SOCIAL_WIDGET_DESC" />

Here copy and paste any of the social-twitter, social-facebook and make required changes for your social media.

Copy *__social.php__* from 
```libraries => expose => widgets```
Paste it into *__template’s widget folder__*. Open it, copy & paste any of the li and make required changes.

Upload image for your social media into ```templates images folder => social-icons``` Go to ```templates folder => less => widgets.less```
open it and scroll down to *__social section__*. Now add code to link the image you’ve uploaded.

Now login to your admin panel and go to ```Template’s settings => Developer => Compile Less``` Enable this option, now the changes you’ve made into widgets.less will be compiled into CSS.
