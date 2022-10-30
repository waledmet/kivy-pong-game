# kivy-pong-game
 create simple pong game with using kivy
 This tutorial will teach you how to write pong using Kivy
 You will require a basic knowledge of Python
# install kivy
pip install docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew
pip install Kivy
for more details check next link 
https://kivy.org/doc/stable/gettingstarted/installation.html

# Note
The name of the kv file, e.g. pong.kv, must match the name of the app, e.g. PongApp (the part before the App ending).

## Drawing
# Add canvas
1. this canvas block says that the PongGame widget should draw some graphics primitives
2. we add a rectangle to the canvas. We set the pos of the rectangle to be 5 pixels left of the horizontal center of the widget, and 0 for y.
3.  widget, and 0 for y. The size of the rectangle is set to 10 pixels in width, and the widget’s height in height.
# Add label
1. Each of them adds a Label widget as a child widget to the PongGame widget.
2. the text on both of them is just set to “0”. 
# Add the Ball
# Add Two Paddle