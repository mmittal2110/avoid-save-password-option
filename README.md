*Remove/Hide Save password option*


If we use input type="password" in HTML, browser popup a option to save the password. 

Browser identifies the input type password and show the popup. In order to avoid this we an use input type="text" and make it look like password. CSS rule for this is 

    -webkit-text-security: disc;
but this is not supported in several browsers. 

To avoid cross browser issue's we can use a font which contains only dots.

DotsFont: A font made of only dots
https://github.com/kylewelsby/dotsfont

we can include this font and apply this font family to input type="text" which we want to display as password
