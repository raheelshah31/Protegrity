<b>Installation Guidelines:</b><br>
1)Host it on a server. <br>
<b>OR</b><br>
2)Install python 2.7 and start the SimpleHTTPserver from the same directory and acccess the index.html page by http://localhost:8000<br>

Development Mission for web developer:

Create simple page using:

1. Client style: Boostrap

2. Client scripting: jquery and Knockout.js

The page needs to contains, header, content area and footer using bootstrap 

(http://getbootstrap.com/examples/sticky-footer-navbar/)  :

a) Menu header with menu items: "Weather", "Clocks", "Users"

"Clocks" has submenus: "Local Date and Time", "Pretty Current Time"

b) Content area - changes to relevant menu page

 "Weather" – in middle of the screen surrounded by border (1px solid black) :

                        List Box: New York, London, Paris

           Button: on click perform Ajax call to 

                                                     Add the country selected to q= parameter Example: 

                                                    http://api.openweathermap.org/data/2.5/weather?q=New%20York

                                                    Get the Wind from it and display deg and speed on the screen under label.

                                            Response Example (the information needed is in bold and yellow 

background):

{"coord":{"lon":-

75.5,"lat":43},"sys":{"message":0.0139,"country":"US","sunrise":1429093155,"sunset":14291

41477},"weather":[{"id":800,"main":"Clear","description":"Sky is 

Clear","icon":"01d"}],"base":"stations","main":{"temp":276.091,"temp_min":276.091,"temp_

max":276.091,"pressure":1005.97,"sea_level":1038.4,"grnd_level":1005.97,"humidity":62},"w

ind":{"speed":1.32,"deg":316.001},"clouds":{"all":0},"dt":1429102847,"id":5128638,"name

":"New York","cod":200} 

          http://api.openweathermap.org/data/2.5/weather?q=

         http://api.openweathermap.org/data/2.5/weather?q=London

 "Clocks" -> "Local Date and Time": in middle of the screen surrounded by border 

 "Clocks" -> " Pretty Current Time ":  in middle of the screen surrounded by 

 "Users" - list of users with add and remove button (Must be with knockout.js).

(1px solid Green) : Client date and time, updated every time the user clicks the 

text, 20px, Bold.

border (1px solid Blue) : Use FlipClockjs (http://flipclockjs.com/faces/counter) to 

show current Hour, Minute and seconds, make sure it updates every second.

* No need to really save data anywhere in the back end.

* http://knockoutjs.com/examples/simpleList.html

c) Footer – Changes background color every 5 seconds using the colors: white, blue, yellow, 

green… the color rotates after green there is white again.

Help links:

1. Bootstrap: http://getbootstrap.com/examples/sticky-footer-navbar/

2. Knockout.js: http://knockoutjs.com/examples/simpleList.html

3. FlipClockjs: http://flipclockjs.com/faces/counter
