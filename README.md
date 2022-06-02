# PC02-Graffiti - Read thoroughly before starting!
<br>
To get started on this assignment, download or clone the files in this repository. To do so:<br>
1. Click the green button above <br>
2. Select "Download ZIP". <br>
3. Unzip the downloaded file and place the created folder into the folder your Programming Challenges folder.
<br>
<br>

## The Assignment Aims
1. Practice drawing using turtle's functions and pixel locations.
2. Practice drawing shapes and lines. 
3. Explore the turtle library functions.
4. Create some art! (Graffiti is art, you know.)

You'll use the **turtle library** to modify an image using the code snippets we built during the week.

Download this starter repository. In it, you'll find a starter code and either picture of ELON MUSK (below). The start code already loads in the image of ELON MUSK to your turtle panel. On this image, you may draw whatever you like--positive, neutral or negative or whacky imagery. We are all adults, and please make some reasonable choices.

<img src="https://github.com/ATLS1300/PC02-Graffiti/blob/master/ElonMuskTalking.gif" width="433" height="296">, <img src="https://github.com/ATLS1300/PC02-Graffiti/blob/master/ElonMuskConfused.gif" width="420" height="280">


>Elon Musk is the CEO of PayPal and the owner of Tesla, SpaceX Neuralink and Starlink (and maybe Twitter?), recently reported to have a net worth of $223 billion dollars (that's: $223,000,000,000,000, or the GDP of Iraq or Peru in 2019), making him one of the richest human in history. Musk has seen a 10-fold increase in wealth since the start of COVID-19 ($25B in 202 to $223B in 2022).

>To draw on Elon Musk, you may have to move your turtle to different pixel locations. A pixel, short for **pic**ture **el**ement, is the smallest unit of a picture. Most screens have upwards of 1000 pixels in its longest dimension. To get a sense of what pixels are and how right Elon Musk is, check out this [data visualization]([https://mkorostoff.github.io/1-pixel-wealth/](https://engaging-data.com/how-rich-is-elon-musk/)).

## The start code

Some code has some code written for you to help you get started quickly. 
The start code sets the drawing window to 750 x 750 pixels, meaning you have 750 pixels horizontally (x), and 750 pixels vertically (y). Remember, the origin (0,0) is at the **center of the picture**, so to move to the *righthand edge*, your turtle moves *positive 375* pixels, and to the *lefthand edge*, you'd move *-375 pixels*. Upward movement is positive, and downward movement is negative. The syntax to move your turtle is shown below.

```turtle.forward(375)```

## The Assignment

1. To make your graffiti, add **at least 2 different geometric shapes** - a circle, a square, a polygon (+4 sides), and a line are all unique shapes

    For full credit, these shapes must:
        1. have **different weights (or thicknesses) of the lines**
        2. be drawn at **different positions** on the screen 
        *(Hint: to navigate your turtle, you can use ```turtle.goto(x,y)``` for a specific position, or pick up the pen ```turtle.up(PIXELS)``` and use ```turtle.forward(PIXELS)``` and rotations (```turtle.left(DEGREES)```, ```turtle.right(DEGREES)```)*.

2. Upload your script (the .py file) saved as:

    PC02_Graffiti.py

    *Note: This class uses **autograders** -- code that looks for requirements. This kind of test code is an industry standard, so we'll get you used to   working with them! Tests are not affecting scores yet, but complying speeds up development! Tests are in development and will be released to the class shortly. For upcoming assignments, tests will be available in the assignment repository, so you can see what technical grade you will get before you submit. *

3. Submit through Github Classrooms by uploading the file into **this repository**. 

## HOW YOU SHOULD SPEND WORK TIME:

1. Play!


   - Explore using the [Turtle Library documentation](https://docs.python.org/3/library/turtle.html#turtle.forward) and the code that we made in class to see what turtle can do! There's no wrong way to code, this is your expression. Play with colors, shapes, and look up commands. 
   - Here are of all the [string color names in the turtle library](https://cs111.wellesley.edu/labs/lab01/colors) (to use with ```pencolor()``` or ```color()```)
   - To save your work, you must add your lines to the **text editor**! Running your code autosaves it. Run your code often!

2. Sketch! Outline

   - Now that you know what to do with turtle, sketch some things out! You can write notes to yourself, or make an actual drawing. Note where and how you'll change color, shapes and pen width.
   - Outline your project! What will you draw first? Second? Last? Make some rules for how you will draw you image--this will become a blueprint for how you build your code. (It's an algorithm!)

3. Test your code!

   - You'll be working between the **command line** and **text editor**. Run your code (*green play button*) often to make sure it is does what you expect it to BEFORE you turn it in! Also close and open Spyder and then run your code before submitting!

## EXTRA CREDIT - Grad students _must_ complete at least 2!

    0.5 pts - create a **3rd shape**

    0.5 pts - set at least **one color** using **RGB values**. 

    0.5 pts - create **one unfilled** and **one filled shape**


## Resources
[Turtle Cheat Sheet](https://canvas.colorado.edu/courses/75648/pages/turtle-cheat-sheet?module_item_id=3014370) - quick list of turtle functions and how to use them. (ATLS 1300 Fall 21 Canvas Page)

[Elon Musk Coordinates](https://canvas.colorado.edu/courses/83516/pages/elon-musk-useful-coordinates) - get started faster!

[Turtle Colors](https://cs111.wellesley.edu/labs/lab01/colors) - All of turtles string colors. There are so many..."The colors, Duke, the colors!"
(Dr. Z is aware no one will get this reference. #eldermillenial)

[Turtle Documentation](https://docs.python.org/3/library/turtle.html) - a deep dive into the turtle library
