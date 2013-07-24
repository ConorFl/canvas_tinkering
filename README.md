canvas_tinkering
================
I recently finished a Udacity course on HTML Game Development w/ Canvas and wanted to make a repo for any canvas tinkering.

swinging_balls.html
==========
http://jsfiddle.net/HBHKe/

First attempt at building something with canvas.  It's all (HTML/CSS/JS) in one small file.

Given how simple the motion was, I opted not to use a physics engine. A quick review of high school physics sufficed.  The horizontal accelation, and velocity were very simple to obtain, however I hit a snag on the vertical a, v (I think it's because the force acting on the string is constantly changing).  To work around this, since I know the x coordinate and length of the string, I obtained the y-coor using Pythagorean Theorem.


