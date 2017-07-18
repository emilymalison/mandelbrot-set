# Mandelbrot and Julia Set Project

This project uses JavaScript and HTML/CSS to draw the Mandelbrot set and a Julia set on a webpage (go here - https://en.wikipedia.org/wiki/Mandelbrot_set - to learn more about the Mandelbrot set and here - https://en.wikipedia.org/wiki/Julia_set - for the Julia sets). User can change which Julia set is displayed by manually entering a complex number or by clicking on a point in the Mandelbrot set to set the c value for the Julia set. The user can also change other factors like zoom or the number of 'iterations' (number of terms the program checks to see if each sequence goes to infinity), as well as the color scheme. The color of each pixel is determined by whether the recursive sequence with that c value remains bounded or not (black = bounded) and if it doesn't, how fast it goes to infinity. The program loops through a color array to color based on how fast each sequence goes to infinity, causing the gradient effect.


## Built With

* Brackets (IDE) - http://brackets.io/

