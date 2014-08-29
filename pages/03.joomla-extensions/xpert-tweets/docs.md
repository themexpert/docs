##Before you begin

<div class="alert alert-warning">
<strong>Heads up!</strong>
This module required <a href="http://www.php.net/manual/en/intro.curl.php">cURL</a> library installed and enabled on the server. Please contact your host to install and enabled it. If you are not seeing any error message on module admin then <strong>cURL</strong> is already installed and you don't have to worry about.
</div>

To get this module working you should create a Twitter app to get the consumer key, secret, access key and token. Please follow the steps below.

##Creating Twitter API Key

1. Visit [Twitter Developer site](http://dev.twitter.com/) and login with your Twitter account.

2. After login click *My applications* link.

![API Step-1](api1.jpg)

3.Now click Create *new application button*


4.Fill up the application form and submit

![API Step](api3.jpg)

5.You can see *consumer key* and *consumer secret* codes. Copy the codes to modules respective field. Then click the *Create my access token* button.

![API Step](api4.jpg)

6.Now you can see the *access token* and *access token secret* codes. Copy the codes to module's respective field.
![API Step](api5.jpg)

<div class="alert alert-info">
<strong>Heads up!</strong>
This module only fetch tweets from user or search term so its not required to have <i>Read/Write access</i>. Only <i>Read</i> permission is enough.
</div>

##Module Settings

- **Consumer key:** follow previous section to get the consumer key
- **Consumer secret:** follow previous section to get the consumer secret
- **Access token:** follow previous section to get the access token
- **Access token secret:** follow previous section to get the access token secret
- **Layout:** Select a layout horizontal/vertical.
- **Style:** Select any pre-build style.
- **Max# tweets:** Number of tweets you want to show.
- **Show tweets from:** You can show tweets from any user or search terms define below.
- **Tweet term:** This field is will only work if tweets source is selected is 'search'
- **Show profile:** Show profile of user. This will only work if tweets source is selected as 'user'
- **Profile image:** You can show profile image for the user.
- **Show time:** Show/hide tweets time.
- **Show source:** Show/hide tweets source.
- **Cache time:** Due to twitter api limit you must set a high - cache time(ms).