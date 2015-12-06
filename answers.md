Madlibs of the Amazon
---------------------

```js
// Put this sentence in a pop up:
// If you find yourself having to cross a piranha-infested river, here's how to do it...
alert("If you find yourself having to cross a piranha-infested river, here's how to do it...");
// Get the user to enter an adjective
var adjective = prompt("Please enter an adjective.",  "AGGRESSIVE");
// Get the user to enter a type of liquid
var liquid = prompt("Please enter an liquid.",  "LEMONADE");
// Get the user to enter a body part
var bodypart = prompt("Please enter an bodypart.",  "CHIN");
// Get the user to enter a verb
var verb = prompt("Please enter an verb.",  "GALLOP");
// Get the user to enter a place
var place = prompt("Please enter an place.",  "DISNEYLAND");

// Fit the user's words into this sentence, and save it in a String:
// Piranhas are more [adjective] during the day, so cross the river at
// night. Piranhas are attracted to fresh [type of liquid] and will most
// likely take a bite out of your [body part] if you [verb]. Whatever
// you do, if you have an open wound, try to find another way to get
// back to the [place]. Good luck!
var madlib =
    "Piranhas are more " + adjective +
    " during the day, so cross the river at night. Piranhas are attracted to fresh " + liquid +
    " and will most likely take a bite out of your " + bodypart +
    " if you " + verb +
    ". Whatever you do, if you have an open wound, try to find another way to get back to the " + place +
    ". Good luck!"

// Make a pop-up for the final story. You can use \n to go to the next line.
alert(madlib);
```

World Domination
----------------

```js
// 1. Ask the user if they know how to write code.
var answer = prompt("Do you know how to write code?");
// 2. If they say "yes", tell them they will rule the world.
if(answer == "yes"){
    alert("You will rule the world!!");
} else {
// 3. Otherwise, wish them good luck finding a job.
    alert("Good luck finding a job");
}
```


Magic 8 Ball
------------

```js
// 1. Make a variable that will hold a random number and put a random number into this variable using "Math.floor(Math.random() * 4);"
var random_num = Math.floor(Math.random() * 4);

// 2. Print out this variable
alert(random_num);

// 3. Get the user to enter a question for the 8 ball
var question1 = prompt("Enter your question.");

// 4. If the random number is 0

// -- tell the user "Yes"

// 5. If the random number is 1

// -- tell the user "No"

// 6. If the random number is 2

// -- tell the user "Maybe you should ask Google?"

// 7. If the random number is 3

// -- write your own answer

if (random_num === 0) {
    alert("Yes");
}

if (random_num === 1) {
    alert("No");
}

if (random_num === 2) {
    alert("Maybe you should ask Google?");
}

if (random_num === 3) {
    alert("Absolutely");
}

// ANOTHER WAY:

if (random_num === 0) {
    alert("Yes");
} else if (random_num === 1) {
    alert("No");
} else if (random_num === 2) {
    alert("Maybe you should ask Google?");
} else {
    alert("Absolutely");
}
```
