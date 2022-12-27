# Biquadris

## Overview
For our final project for CS246 during the Fall 2022 term, a peer and I made a variation of Tetris called Biquadris. It was written in C++ and adhered to many OOP principles. We also implemented many design patterns, followed MVC architecture, adhered to RAII idiom, and ensured the project had low coupling and high cohesion.

In the end, the game had over 25 classes (each with their own .cc and .h file) and one Makefile. All fields were private to promote encapsulation and all super classes were abstract to promote polymorphism. Each module has a single responsibility and interacts with other modules through basic calls to public methods. Due to Policy 71, the source code of this project is only available upon request.

Below is the final UML diagram for our project:

<img width="1000" alt="UML" src="https://raw.githubusercontent.com/braydonwang/Biquadris/main/images/uml.png">

The game is displayed through both text and graphics (using the XWindows library)

<img width="600" align="left" alt="graphics" src="https://raw.githubusercontent.com/braydonwang/Biquadris/main/images/graphicsdisplay.png">
<img width="200" alt="text" src="https://raw.githubusercontent.com/braydonwang/Biquadris/main/images/textdisplay.png">

## Bonus Features

For our bonus features, we added colour to the text display, a new special action (layer - adds a layer of permanent blocks at the bottom of the opponent's board), and a new command (hold - holds the player's current block to be used in future turns)

<img width="600" align="left" alt="graphics" src="https://raw.githubusercontent.com/braydonwang/Biquadris/main/images/bonusgraphics.png">
<img width="200" alt="text" src="https://raw.githubusercontent.com/braydonwang/Biquadris/main/images/bonustext.png">
