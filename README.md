# Paradigm Shift for Jekyll
Jekyll version of Paradigm Shift by [ajlkn/HTML5 UP](https://html5up.net/). 
You can see how it looks [here](https://vrmiguel.github.io/paradigm-shift-jekyll-theme/).

## Usage

You can use this theme locally by commenting `gem "github-pages", "~> 3.8.5"` on `Gemfile` and, uncommenting `gem "jekyll"`.
As it stands, it's ready to use on GitHub Pages.

To add your own text to the site, you've got to edit `_layout/default.html` (Markdown editing to be added soon, hopefully).


Add images to the site on `images`. 

### Added features

* [Formspree](https://formspree.io/) integration should work automatically as soon as your email is added to the config file.


* You can now edit the page's content through the Markdown files on the project's root directory, starting by `first.md`.


* Pages are now ordered. You can decide which page gets included first by setting the `order` priority on the Markdown files.


* [WhatsApp](https://api.whatsapp.com) integration works as soon as your phone is added to the config file.
   If you wish to remove either of these, Formspree integration can be removed on line 7 of `include/message.html`, while the WhatsApp link to your number can be removed on line 9.


* Add your social profiles to `_config.yml`. Only the ones you add to the config file will show up on the site footer. Credits to [Andrew Banchich](https://github.com/andrewbanchich) for this idea.


# Credits / License

README by HTML5 UP:
```
Forty by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
This is Forty, my latest and greatest addition to HTML5 UP and, per its incredibly
creative name, my 40th (woohoo)! It's built around a grid of "image tiles" that are
set up to smoothly transition to secondary landing pages (for which a separate page
template is provided), and includes a number of neat effects (check out the menu!),
extra features, and all the usual stuff you'd expect. Hope you dig it!
Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.
(* = not included)
AJ
aj@lkn.io | @ajlkn
Credits:
	Demo Images:
		Unsplash (unsplash.com)
	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)
	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

As per the original HTML5 UP theme, this code is free under the Creative Commons for personal and commercial use, as long as credit is given.

All images here provided are licensed under [Unsplash](https://unsplash.com/license).
