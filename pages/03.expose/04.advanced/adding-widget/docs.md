---
title: Adding New Widget
taxonomy:
    category: docs
visible: true
---
In the Expose framework, we use the term __Widget__ to mean a specific bit of functionality. Widgets are flexible enough that they can be used to perform almost any type of logic you would need. The base ``ExposeWidget`` class contains methods that can be implemented to control how your widget functions. Those methods are:

##API
|`isEnabled()`|
|------------- |
| By default, this gets its state from the enabled toggle in the admin. You can override this to force the enabling of a feature without any UI interaction.|
| Returns `boolean` [true or false]|

|`getPosition()`|
|-------------- |
| This gets its position from the position element in the admin by default. Again, you can override this to force a position without any UI interaction. |
| Returns `string` [position name] |

|`isInPosition()`|
|--------------- |
| This is a method to determine if the widget is located in a specified position.
| Returns `string` [position name] |

| `get($param [, $default = NULL])`
|:---------------------------------------------------------------------------------------------------------------------------------------------------------
| This gets a param from the widget's configuration. It can also take a prefix for more specificity.
| Argument `string` [filed name]
| Argument[optional] `string` [default value]
| Returns `mixed` [current value of the field]

| `init()`
|:-------------------------------------------------------------------------------------------------------------
| Empty by default. It's the first method called on initialization of a widget. Used for setup or initialization

| `render()`
|:----------------------------------------------------------------
| This is used to render output in a particular position. It is empty by default.

## New Social Widget

Open *__templateDetails.xml__*, scroll down to *__widgets settings__* and search for the following line

	<field name="spacer-social" type="spacer" text="SPACER_SOCIAL_WIDGET_LABEL" description="SPACER_SOCIAL_WIDGET_DESC" />

Here copy and paste any of the social-twitter, social-facebook and make required changes for your social media.

Copy *__social.php__* from 
```libraries => expose => widgets```
Paste it into *__template’s widget folder__*. Open it, copy & paste any of the li and make required changes.

Upload image for your social media into ```templates images folder => social-icons``` Go to ```templates folder => less => widgets.less```
open it and scroll down to *__social section__*. Now add code to link the image you’ve uploaded.

Now login to your admin panel and go to ```Template’s settings => Developer => Compile Less``` Enable this option, now the changes you’ve made into widgets.less will be compiled into CSS.
