
rateit
======

This is the latest release of rateit plugin from https://rateit.codeplex.com/license
mainly so we can get it from bower

License
MIT


CHANGE LOG
======
Bug fix: #1859 RateIt Stars disappear when clicking into another form field and pressing return (Thanks to hyperspacebeast)

1.0.21
Bug fix: #1828 Progressive enhancement (using select) displays incorrect amount of stars
Bug fix: #1829 Use UNIX-style (LF-only) line endings

1.0.20
Bug fix: #1817 Trigger change on backingfld when value changes

1.0.19
Feature: #1801 Added cancellable beforereset and beforerated events (Confirmation before do a rate)
Misc: added example showcasing use of SVG instead of GIF image.

1.0.18
Bug fix: #1747 Fixed bug caused by fix for: 1747

1.0.17
Bug fix: #1747 Initialization fail with data-rateit-value=0

1.0.16
Bug fix: #1741 Using arrow keys after a rating

1.0.15
Bug fix: #1728 please include simple fix for jquery mobile

1.0.14
Feature: #1712 Feature request: a .reset() method to clear out everything
Bug fix: #1711 Resize (Thanks to JoeyBradshaw)

1.0.13
Bug fix: #1648 Need to check for window.console before using it

1.0.12
Feature: ARIA support. Added basic ARIA support including keyboard navigation.
Feature: Suggestion: use span instead of div Just use <span class="rateit"></span> and the plugin will render itself using inline element.
Bug fix: #1639 Firefox showing too many stars

1.0.9
Bug fix: #1203Dynamically changing a property causes events to be re-registered

1.0.8
Bug fix: #1142 Readonly mode with backingfield is broken

1.0.7
Bug fix: #729 Setting initial value issue

1.0.6
Feature: if a backing field is disabled at instantiation, start RateIt as readonly, thanks to dgon!

1.0.5
Bug fix: #634 Setting value to 0 doesn't work
Feature: now you can reset the rating by $(SELECTOR).rateit('value', null) , thanks to jeffgman!

1.0.4
Two bug fixes:
1) #523 RateIt does not work with jQuery 1.7.2
2) #417 Bug for hover event with jQuery 1.7 -> The 'hover' event got an extra name: 'over' . Because the bug leading to this is not fixed yet in jQuery.

1.0.3
Minor change. Call to register all elements with .rateit class occurs now only on document.ready

1.0.2.1
Fixed CSS bug, when container is in text-align: right mode. (thanks to DefconDotNet)

1.0.2
Compatible with jQuery 1.6.2 . Had to drop compatibility with anything older than 1.6.0

1.0.1
Updated CSS file, to include better support for IE6 & 7 and FF 2

1.0
Added ispreset property


Contains all necessary files for RateIt, and also example document.

