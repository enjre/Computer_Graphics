*****************
* A3 Viewing and Navigation
* CS464
* Oct 30 2021
* Andre Maldonado
*****************

OVERVIEW:
    This program is a rendering of a texture based height map, with a simulated vehicle driving over it. 
    It has mouse controls to manipulate the direction of motion. 

INCLUDED FILES: 
    * img1.png, img2.png, img3.png - 512x512 image files to be rendered
    * sc1.jpg, sc2.jpg, sc3.jpg - screenshot of vehicle view over height map
    * glMAtrix_util.js - matrix utility JS file
    * README - this file
    * WebGL_A2.html - main file that renders the height map and allows viewing controls
    * webgl-utils.js - webgl utility JS file

USAGE:
    To see the height map, open WebGL_A3.html via a locally hosted webserver to see the height map. 

    Mouse Wheel Up: Move backwards
    Mouse Wheel Down: Move forwards
    Click and Drag: change directions. 

DISCUSSION:
   This project was interesting because it did actually just require modification of the last one. 
   Most of it involved the view, rather than the height map itself. I had trouble with the direction of the 
   driving, so for now, the mouse wheel controls are inverted. Also, the driving will bug out after about 
   a minute of driving, then the page has to be refreshed. I did not have enought time to debug this. 

SITES USED:
    * https://greggman.github.io/servez/