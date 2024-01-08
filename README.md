# Color picker
## Intro
This is the sexithg project of my 30-day coding challenge. The project includes following tech stuff: HTML, CSS, JavaScript.

## Idea
The goal was to make a color picker. After clicking the botton, we get a random color. The background is changing to the new color and we also see the # code which represents the particular color.

## Breaking down the code
The 'get color' function generates a random hexadecimal color code and sets the background color for the body, updates the text content of an element with the ID "color-code" to display the generated color code. I also added an element circle, and it's background also switches to that color. 

`Math.random()` generates a random float.
`Math.floor()` rounds the result down to the nearest number.

There is an event listener added to the HTML element (button) with the ID "btn". When the button is clicked, the 'getColor' function is called. 

The reason 16777215 is chosen here is because it represents the decimal value of FFFFFF in hexadecimal. 

`randomNumber.toString(16)` converts the randomly generated decimal number to its hexadecimal representation. Hexadecimal is a base-16 numeral system that uses the digits 0-9 and the letters A-F to represent values. 

## Demo
Click <a href="https://relaxed-narwhal-ebd84f.netlify.app">here</a>.