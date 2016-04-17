# tech.modernfactory.pl

![Ghost version](https://img.shields.io/badge/Ghost-0.7.x-brightgreen.svg?style=flat-square)

> A simple theme for Ghost made for geeks, hackers and developers (forked from Odin).

## Configuration
No need to configure ***Prism*** or ***RRSSB*** buttons.

To add Homepage Navigation Menu Buttons simply add the links in your Navigation Admin Area. They may be useful for static pages (*AboutMe* for example) or for shortcut to your (best) post tags.  

Odin comes with a default ***favicon*** generated with [Real Favicon Generator](http://realfavicongenerator.net). If you want to add your *favicon* you can generate your own (with [Real Favicon Generator](http://realfavicongenerator.net)) and place downloaded files inside the ***assets/img/favicons*** Odin directory.

***Disqus*** comments, ***Google Analytics***  and ***Font Awesome Home Page Social Link Icons*** are disabled by default, but they are easily configurable with *Blog Header Code Injection* inside your Ghost Admin Area.

```html
<script>
// to enable Google Analytics
var ga_id = 'YOUR-UA-ID_HERE';

// to enable Disqus
var disqus_shortname = 'YOUR_DISQUS_SHORTNAME'


// to enable Social Link Icons add the social_link object
// with the pair key/value -> social_network/link
// NB: the key is used to include the right icon from Font Awesome
// (you can include any Font Awesome icon)

// Example1: default social network icons
var social_link = {
    'twitter': 'https://twitter.com/h4t0n',
    'linkedin': 'https://it.linkedin.com/in/andreatarquini',
    'github': 'https://github.com/h4t0n',
    'rss':'https://blog.h4t0n.com/rss/'
    // you can add more icons
}

// Example2: squared social network icons
var social_link = {
    'twitter-square': 'https://twitter.com/h4t0n',
    'linkedin-square': 'https://it.linkedin.com/in/andreatarquini',
    'github-square': 'https://github.com/h4t0n',
    'rss':'https://blog.h4t0n.com/rss/'
    // you can add more icons
}

</script>


```


## Copyright & License

Released under the MIT License.  
Copyright (c) 2016 [Modern Factory](http://tech.modernfactory.pl)
Copyright (c) 2016 [Andrea Tarquini](https://blog.h4t0n.com) aka [@h4ton](https://twitter.com/h4t0n)
Copyright (c) 2013-2015 Ghost Foundation (for Casper theme substantial portions of code)
