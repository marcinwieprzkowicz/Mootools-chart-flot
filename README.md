MOOTOOLS FLOT
=============

![Screenshot](http://f.cl.ly/items/323p1i3R1J0o2F1w0n0m/Screen%20shot%202011-03-10%20at%2010.59.32%20AM.png)

This is a direct port of flot from jQuery to MooTools (+ a few plugins)...

Documentation can be found under `/Docs`

Live examples
----------

####Lines
- __Lines:__                    http://jsfiddle.net/UL3d9/  
- __Lines with points:__        http://jsfiddle.net/4zpFS/  
- __Lines with bezier curves:__ http://jsfiddle.net/eQ3n8/
- __Bezier curves & fill:__     http://jsfiddle.net/4b9sQ/

####Bars
- __Bars:__                     http://jsfiddle.net/MPLyB/  
- __Bars with stack:__          http://jsfiddle.net/J4mPM/ 
- __Side by side ordered bars:__ http://jsfiddle.net/y6YZm/ 

####Pie
- __Pie chart:__                http://jsfiddle.net/D996U/  

####Pyramid
- __Pyramid chart:__            http://jsfiddle.net/M62Dr/ 

####Moving Chart
- __Self updating chart:__      http://jsfiddle.net/Q3VK2/


How to use
----------

Instead of overloading the dollar (like in the jQuery version), here flot is on a flot namespace...

    // So this...

    $.plot({...});

    // Becomes

    flot.plot({...});
    
Everything else about the api should be the same.

    flot.plot(element, data, options);

