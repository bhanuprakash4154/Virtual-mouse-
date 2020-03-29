# Virtual-mouse-
Creating a virtual mouse by performing fingertip gestures using OpenCV module

Virtual Mouse Using Gesture Recognition
Implementing a virtual mouse using gesture recognition .

Required Modules :
Opencv
  pip install opencv-python
Numpy
  pip install numpy
Pynput
  pip install pynput
WX
  pip install wxpython
How it works ?
Generally moving a mouse has two states :

Moving the Cursor
Clicking
Now we consider that we'll be detecting two objects (green color), and if the both appear this is the first state(moving the cursor) and if they are too near so that they form one single detected object this considered as the second state(clicking mode)

Finally ,this is how it will look like.
