# colemaq-xkb
This repository includes xkb configuration files for the ColemaQ keyboard layout

Credit to Nyfee for creating the layout

# Installation
Copy the file to /usr/share/X11/xkb/symbols/

Load the layout using `setxkbmap -layout colemaq`

You can change the variant using the `-variant` option

versions included:
* ColemaQ-F `-variant f`
* ColemaQ-ID (Indonesian) `-variant id`
* ColemaQ Widemod `-variant wide`

The file also includes support for ISO keyboards

These configurations can be loaded by appending `_iso` to the end of the variant name

For example to load ColemaQ-F for an ISO keyboard use `setxkbmap -layout colemaq -variant f_iso`
