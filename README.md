# CTFd Google reCaptcha Plugin

A plugin which adds the Google reCaptcha v2 invisible code to the user registration and login function

1. Set up your account with Google reCaptcha [here](https://www.google.com/recaptcha/)
2. Select Ivisible reCAPTCHA that can validate in the background
![reCAPTCHA](http://i.imgur.com/kJz5jml.png)
3. Clone this repo into a folder in the plugin folder of your CTFd
4. Set the `RECAPTCHA_SECRET` and `RECAPTCHA_SITE_KEY` environment variables or edit the config.py file in this repo to include your reCaptcha keys
5. Set `RECAPTCHA_INSERT_TAGS` to False in Test config if you still need CTFd unittest