# Changing theme colors

Lanyon had the option to add a class to the `<body>` to change the site's theme color. 
To replace that feature, I added some color variables to the file `assets/css/main.scss`. 
This gives you more options to tweak the colors.

To change the colors, edit the `assets/css/main.scss` file:

- `$theme-color:` will set the color of all links, button outlines, and sidebar background.
- `$sidenav-link-color:` sets the color of links in the sidenav, for example the lesson titles.
- `$sidenav-text-color:` sets the text color in the sidenav, for example the chapter names.
- `$sidenav-active-bg:` sets the background color for the current chapter or nav item, to make it stand out. 

The colors are HTML color codes. 
Try a [color picker](https://www.w3schools.com/colors/colors_picker.asp) to find color codes. 
I usually use the hex codes that start with `#`, for example `#fff` is white, `#000000` is black, `#cdcdcd` is a grey, `#F1B300` is Pride Gold (see [official UI colors](https://www.uidaho.edu/brand-resource-center/visual-style-guide/color-identity)). 
The Lanyon themes used transparency for the backgrounds, for example `rgba(255,255,255,.1)` is a very transparent white, thus lightens the color it is on top of. 
However, that is unnecessary, and can be replaced with a normal color if desired.

Just make sure there is good contrast between the text/links and the background!
