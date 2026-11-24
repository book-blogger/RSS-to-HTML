# RSS-to-HTML
live previews on my website's [changelog](https://horse.jp.net/feeds/history) & [microblog](https://horse.jp.net/feeds/microblog)

credit to [bloople.net](https://rss.bloople.net/) for the idea as I wanted something more locally stored.

## Features:
* Post titles are converted to h3 html elements
* dates are loaded under titles & before descriptions: presented as month:"long" day:"numeric", year:"numeric"
* descriptions are converted to ul style lists automatically and turn manual line breaks into new bullets
## How To Use
* make sure to store files locally to your website or where ever is easiest to link
* you can use the script file in the head attribute if you use defer in the tag, otherwise place it before the ending body tag
* place the html anywhere you want as it does not require a parent container
* style the css however you want, can be put into a main css file along side other code as it will style the feeds independently!
* have fun!
