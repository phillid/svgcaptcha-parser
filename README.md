svgcaptcha-parser
=================
This is a utility to demonstrate the vast stupidity of human kind by easily parsing an SVG captcha as provided by [SVGCaptcha](http://svgcaptcha.com)

I suppose you could call it an SVG captcha 'cracker' if you're a total tool.

Note that it doesn't crack beizer curve SVG captchas, because I'm a lazy prick.

Dependencies
------------
* wget
* curl
* XML::Simple

Invocation
----------
Example:

    $ ./svgcaptcha-parser 
    Saved 3f45kx9.svg
    $ ls *.svg
    3f45kx9.svg
    $ 

