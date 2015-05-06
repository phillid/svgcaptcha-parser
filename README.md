svgcaptcha-parser
=================
This is a utility to demonstrate the vast stupidity of human kind by easily parsing an SVG captcha as provided by [SVGCaptcha](http://svgcaptcha.com)

I suppose you could call it an SVG captcha 'cracker' if you're a total tool.

Note that it doesn't do beizer curve SVG captchas, because I'm lazy.
This targets a very small subset of all possible types of SVG captchas.

Dependencies
------------
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

