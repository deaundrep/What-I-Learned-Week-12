# What-I-Learned-Week-12

## DATASAUR

Practiced .filter, .map, and .sort.
* The filter() method creates a new array with all elements that pass the test implemented by the provided function.
* The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.
* The sort() method sorts the elements of an array in place and returns the sorted array. 

EX. const notTriassic = function (dino) { return dino.filter(isNotTriassic); }

const bySpecies = function (dino) { const newDino = [...dino]; return newDino.sort(isFirstAlphabeticallyBySpecies); }


## This Might Be A DOMb Idea

Task is to manipulate the DOM. 
* Change the font color of the paragraph to light blue.
* Change the font size of the heading to 5 em.
* Change that image's size to be 300 pixels high.

EX. const paragraph1 = document.querySelector
('p')
paragraph1.style.color = 'lightblue';

const header = document.querySelector
('h1')
header.style.fontSize = '5em'


## Just How We Roll

### Tools Practicing With

* event listeners - The addEventListener() method attaches an event handler to an element without overwriting existing event handlers.
* string building/interpolation
* array management and iteration
* maths


EX. 
const sixes = [];
const sixRoll = function(){
let result = getRandomNumber(6);
document.querySelector('#d6-roll').scr = `images/d6/${result}.png`
sixes.push(result)
document.querySelector("#d6-button").addEventListener("click", sixRoll);




