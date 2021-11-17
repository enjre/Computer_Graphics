*****************
* A2 Simple Modeling
* CS464
* Oct 2 2021
* Andre Maldonado
*****************

OVERVIEW:
    This program is a rendering of a texture based height map. 
    It has mouse controls to manipulate the map.

INCLUDED FILES: 
    * img1.png, img2.png, img3.png - 512x512 image files to be rendered
    * map1.jpg, map2.jpg, map3.jpg - screenshots of each corresponding image file's height map
    * glMAtrix_util.js - matrix utility JS file
    * README - this file
    * WebGL_A2.html - main file that renders the height map
    * webgl-utils.js - webgl utility JS file

USAGE:
    To see the height map, open WebGL_A2.html via a locally hosted webserver to see the height map. 

    You can use the mouse wheel to zoom in or out. Clicking and holding the button lets you drag to rotate
    the map.

DISCUSSION:
    Last project, I could not get my browser to load the textures properly. For this one, I used
    Servez. It is a simple, locally hosted webserver which I pointed to the filepath of my project, which
    allowed me to properly use the texture image files. The coolest part of this project for me was making 
    the functions to allow user interaction. I could not figure out to to make the program only accept
    the left mouse button to rotate, so both left and right work right now. 

SITES USED:
    * https://greggman.github.io/servez/