UNM CS351L
3D Graphics Using JavaFX

Author: Connor Denman

About
* This project runs a simple user interface with a toolbar and a subscene for displaying 3D molecules.
* On the toolbar, one button displays Methane (CH4) in the subscene, the other displays water (H2O).
    - when the molecules are switched, a rotation animation on the molecule is played for a few times.
* Below the buttons, there are 2 JavaFX UI sliders that adjust the scene's brightness and contrast.
* Much of the code is based on the tutorial: https://docs.oracle.com/javase/8/javafx/graphics-tutorial/sampleapp3d.htm

Classes
* "Main.java" is the primary class. This program takes no arguments to execute.
* "Xform.java" contains a helpful class that extends JavaFX "Group" and is used throughout "Main".
    - As seen in the tutorial on Oracle's website.