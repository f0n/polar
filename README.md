# Polar Calculation for Hang Gliders
Web tool to determine sink rate based on airspeed. It uses JavaScript for the calculation. 

The stylesheet has been optimized for mobile devices to make the tool an in-flight aid. 

The equations are based on the article [Polar Data for Wills Wing Hang Gliders](https://www.willswing.com/polar-data-for-wills-wing-hang-gliders/). Note that the tool provides sink rates similar to the ones reported by [Wills Wing](https://www.willswing.com) on the table but the numbers will be updated as real flight data becomes available. 

![alt text](https://www.willswing.com/wp-content/uploads/2013/07/polarchart_1.gif "Polar Image")

Future development includes: 
* Discrimination between mobile and desktop browser stylesheets
* Selection of glider parameters with [StackOverflow](https://stackoverflow.com/questions/11943436/javascript-if-statement-based-on-dropdown-menu-value) and [Selection](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_select)
* Integration with microcontroller and/or variometer

The idea is to find parameters a, b, and c for the polar equation such that:

<img src="https://latex.codecogs.com/gif.latex?V_{sink}&space;=&space;a&space;{V_{air}}^2&space;&plus;&space;b&space;V_{air}&space;&plus;&space;c" title="V_{sink} = a {V_{air}}^2 + b V_{air} + c" />
