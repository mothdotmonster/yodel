# yodel

[![asciicast](https://asciinema.org/a/GRRtpJSsPYYwcDVydH5OvhY5O.svg)](https://asciinema.org/a/GRRtpJSsPYYwcDVydH5OvhY5O)

yodel is a script to make the outputting of formatted text easier, primarily intended for use in other scripts to make them more readable.

***

### INSTALLATION:

For casual users, just get the [latest release from the Releases section](https://github.com/mothdotmonster/yodel/releases/latest/download/yodel).

If youd like to embed it as a function into your own scripts to avoid external dependencies, a minified version is available in the scripts folder as yodel-mini. Simply copy it from there and add is as a function into your shell script.

***

### USAGE:

-b / --bold - print bold text  
-l / --light - print light text  
-i / --italic - print italic text  
-u / --underline - print underlined text  
-c / --color (red,green,yellow,blue,magenta,cyan) - print colored text  
-x / --color-indexed [0-255] - print 255-color text  
-r / --color-rgb [0-255] [0-255] [0-255] - print full RGB text  
-n / --no-newline - disable trailing newline  
