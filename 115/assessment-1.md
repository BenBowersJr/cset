
I think I will adapt without many issues. Ive been okay with working on large projects because I try to tackle each project in small pieces. Most of my projects in highschool took many weeks to work on so im used to having large projects to work on.

The button would probually find the specific p element with .querySelector, or any other element related, that is displaying the current scene. Then update that element to display the next scene. there can be a main SCENE object or array that holds each scene's data like textContent or related images then javascript could grab the scene the user choose, and update the corresponding HTML element.

All different data structures have there own unique strengths. Arrays are good for holding values in a certain order and at indexes, objects are great for holding specific data at keys, and trees are great for holding data that has lots of nested elements and different generations of children elements. The DOM wouldnt work well as any other data structure than a tree because of how HTML elements are frequently nested inside of each other.
