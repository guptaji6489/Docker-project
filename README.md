# TLG_JoinCaptchaBot

Bot to verify if a new user, who joins a group, is a human.
The Bot sends an image captcha for each new user, and kicks any of them that can't solve the captcha in a specified amount of time. Also, any message that contains an URL sent by a new "user" 

## Installation

Note: Use Python 3 to install and run the Bot, Python 2 support could be broken.

To generate Captchas, the Bot uses [multicolor_captcha_generator library](https://github.com/J-Rios/multicolor_captcha_generator), wich uses Pillow to generate the images.

