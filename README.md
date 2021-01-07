Pop Balloons game using Javascript, HTML/CSS 🎈🎊
This is an amazing game to practice HTML, CSS and a little Javascript. The game goal is to POP al the balloons by clicking on them.

📝 Instructions
Balloon Pop Game with HTML/CSS and Javascript

Build a game with the following workflow:

When the website loads (window.onload) you have to render all the ballons.
Every ballon needs to have an onClick attached to listen to when the user clicks on it.
When the user clicks on it the balloon disappears (pops) from the screen.
When all the 20 balloons have disappeared the website reloads and the game starts again.
💪 Strategy
Strategy to complete the pop balloons

First, declare an array of 20 colors, each color will represent a balloon, the colors can repeat.
To pop a balloon, you will have to turn the value on that balloon position on the array equal to null.
Loop all the colors and make the html string for each balloon, you should generate a big html string like this, and add it into the DOM:
<div class="balloon active"></div> <div class="balloon popped"></div> <div class="balloon active"></div> <div class="balloon active"></div>
Add that string to the innterHTML of the <div id="balloon-map">element using document.querySelector.

Update your function that renders the ballons to add also an onClick on each balloon div to listen to the click.

When a balloon is clicked, go the array of colors and turn the color back to null.

