# Front-End Implementation Test

## Instructions

Please build the supplied design into well-formed HTML/CSS. 

The objectives are to:

* Replicate the supplied design accurately, taking into account any changes you may need to implement to make this work on different devices.
* Build a standards-based, accessible and responsive web page.
* Deliver this as a single HTML page with assets (e.g. images, CSS) loaded from a sub-folder (e.g. `assets/`).

Constraints of this task are:

* Write vanilla HTML, CSS and JavaScript. No frameworks or build tools can be used (that means no Bootstrap, Foundation, SASS or similar tools). 
* Your work must be responsive and accessible. 
* Use relative links so the web page works if you just load it in a web browser without a local hostname.

We will test this by viewing the web page via a URL on http://localhost to ensure the web fonts load. We'll test this on:

* Firefox and Chrome on desktop
* IE11 on a Windows PC
* iOS Safari and Android Chrome on mobile

It is expected this test will take around half a day to complete. 

# Design reference

See the *Design layout* folder.

* Mobile.png
* Mobile-320-grid.png (showing the underlying grid)
* Desktop.png
* Desktop-1200-grid.png (showing the underlying grid)

## Typography 

* [FF Tisa Web Pro](https://typekit.com/fonts/ff-tisa-web-pro)

Please use the following TypeKit code for web fonts, this is intended to work on any of the following URLs: test.dev, localhost, and 127.0.0.1

```
<script src="//use.typekit.net/plb1jth.js"></script>
<script>try{Typekit.load();}catch(e){}</script>
```

Example CSS:

```
font-family: "ff-tisa-web-pro", serif;
```

## Text reference

Font sizes as defined in the original Photoshop design files. Use whatever CSS font sizing you believe is most appropriate in the browser.

### Mobile

* Telephone number: 22px
* Hero image title: 37px, link to craftsmen.html
* Hero image sub-title: 23px
* Navigation title: 20px, link navigation to nav.html

### Desktop

* Telephone number: 26px
* Hero image title: 49px, link to craftsmen.html
* Hero image sub-title: 34px
* Navigation title: 24px, link navigation to nav.html
* Navigation sub-title: 22px

## Photography
You will find the image of the craftsman inside the *assets* folder.
