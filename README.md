hiage.js
==============

hiage.js is the javascript version of my 2D game engine which I originally made in C#. One game is included which uses it, gravistroids. You can read more about this here: http://hallgeir.org/2013/02/23/gravistroids/

The engine is a work in progress, and only a fraction of the functionality from the original Hiage project is implemented. 

Running Gravistroids
--------------
With Visual Studio, you can simply open the hiage.js solution file, mark gravistroids as the startup project, and press ctrl+f5. Then all the engine files and the gravistroids files will be copied to the right place, and Chrome will be started up. If you'd like to use another browser, you can modify that in the post build events for the gravistroids project.

If you're not running Visual Studio, you need to do the following:
- Copy the hiage.js/src folder into gravistroids/lib, and rename it to *hiage.js*.
- Open index.html in your browser