Add the spacelab folder to your mahara as below. It is required for the theme to fully function as a responsive theme. Everything else goes into htdocs/theme/cyborg


htdocs/js/spacelab

To change logo:

Replace site-logo.png in htdocs/theme/cyborg/static/images

To activate extra menu:

in htdocs/theme/cyborg/templates/header/topmenu.tpl, Uncomment (remove) the '<!--' in line 18 and the '-->' in line 51. This will display a menu in top left corner next to the logo. Now edit the HTML in topmenu.tpl to build your menu.

To remove 'Team Work' button:

in htdocs/theme/cyborg/templates/header/navigation.tpl, on line 38 remove '<button onclick="TogetherJS(this); return false;" style="float: right;">Team Work</button>'
in htdocs/theme/cyborg/templates/header/head.tpl, on line 4, remove '<script src="https://togetherjs.com/togetherjs-min.js"></script>'