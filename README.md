## Website Performance Optimization portfolio project

###How to run:
2 ways
1. Download the *nisharose.github.io-master* folder.and open the file named *index.html*
2. Browse https://nisha-rose.github.io/nisharose.github.io/

##Changes made to meet Project specification

###For page speed insights :
1. inlined CSS
2. compressed images
3. asyc attributed added to script tags
4. added media tags
5. removed font API call
6. minified index.html

Optimized url:  https://nisha-rose.github.io/nisharose.github.io/
PageSpeed insights scores:
Mobile: 90
Desktop: 92

###Changes made to meet Frame Rate specifications:
1. changed the scope of variable items into global
2. Gets all moving pizza objects from the DOM and puts them into one array to reduce DOM access
3. instead of .querySelector, .getElementByClassName or .getElementById selector are used
4. Calculated the five phases that animate the scrolling background pizzas outside the For Loop
5. limiting DOM access by caching value of length in variable
6. Using backface visibility:hidden in css

###Changes made to Computational Efficiency:
1. In changeSliderLabel() limiting the call to DOM tree by caching the pizzaSize element in variable 'element'
2. Removed the determinDx method and adjusted their function in changePizzaSizes
3. In changePizzaSizes : accessed DOM outside the for loop by caching the elements in randomPizzas
