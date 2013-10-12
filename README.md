DAY 1
========

Cheap Sass Tricks - John Long (@johnwlong | uservoice)
-------------------------------------------------------

@TheSassWay

& + &: having two elements next to each other
.button {
	& + & {}
}

%placeholder classes

css-spinners.com

sass.js: compile sass in the browser like less

Sass at Github - Ben Bleikamp (@bleikamp | Github)
-----------------------------------------------------

Stack:
	- Rails "2.3" (Backported features from newer versions)
	- HTML ERB + View Models
	- CoffeeScript
	- Sass (Scss)

Teams on GitHub
Stop writing new css
The Styleguide: 
	- https://github.com/styleguide
	- KSS: http://github.com/kneath/kss
	- Comments that generate style guides
		+ Explanation
		+ Modifiers
		+ Reference

Primer: Node JS module to share styles across projects
Jon Rohan @jonrohan

performance problems:
	- overqualifying selectors
	- chaining selectors -> moved to single classes
	- attribute selectors

tools:
	- Graphite
	- Campfire
	- CSS Explain: https://github.com/josh/css-explain
	- Dev tools timeline: Big purple & Green bars
	- Dev tools Audit

It Takes a Village to Raise a Website - Chris Eppstein (@chriseppstein | Linkedin)
-------------------------------------------------------------------

- maptastic maple
- plugin repo
- linter
- installer

Sass: Bridging the Designer/Developer Gap - Bermom Painter (@bermonpainter | UX/Web Professional)
----------------------------------------------------------------------------------

- styletiles
- element collages
- style guides
- kss/dss/styledocco

Clean out your Sass Junk-Drawer - Dale Sande (@anotheruiguy | CodeFellows)
------------------------------------------------------------

MVC for Sass?
Where do I put the abstracted code?

Nesting Abuse. Following html nesting

Outside In Comp Approach. Comps with tons of red arrows and lines.
Decompose the UI:
	- Buttons
	- Borders and line widths
	- Icons
	- Color pallettes 

file structure:
	- /buttons
		+ _mixins.scss
		+ _extends.scss
	- /color
	- /forms
	- /layouts
	- /modules
		+ /registration (Application UI Module)
			- _extends.scss
			- _functions.scss
			- ...
		+ /purchase
			- _extends.scss
			- _functions.scss
	- /typography
	- /ui_patterns
	- /vendor
	- _buttons.scss
	- _config.scss (All logic NO CSS!)
	- _forms.scss
	- style.scss -> style.css

Make use of manifests.
Your Foundational UI has no logic only CSS
Use Module Namespaces.

Junk Drawers:
	- Partials

http://www.manning.com/dsande/
promo code - mldsandeau

Sassmeister:
	- app like JS Fiddle for hacking with Sass, Compass, etc

coderecipez.roughdraft.io

Show Your Work & Share Your Toys - Eric Meyer (@eriiicmeyer | Oddbird)
------------------------------------------------------------------------

Natalie Down CSS Systems

target/context = multiplier

Susy grid system

True - Sass Test Library
