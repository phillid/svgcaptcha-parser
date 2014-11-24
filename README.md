svgcaptcha-parser
=================
This is a utility to demonstrate the vast stupidity of human kind by easily parsing an SVG captcha as provided by [SVGCaptcha](http://svgcaptcha.com)

I'm hoping like mad that they are a joke.
Looking at their footer, they look like they're just a site to attract attention for advertising.


Dependencies
------------
* wget
* curl

Invocation
----------
A simple

    ./svgcaptcha-parser

will use curl to fetch a random captcha and save it with a filename to describe the captcha's text.
For example, a captcha reading 'j526nyn' will be saved as `j526nyn.svg' in the working directory.
Yay.
