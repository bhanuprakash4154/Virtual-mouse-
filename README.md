# Virtual-mouse-
Creating a virtual mouse by performing fingertip gestures using OpenCV module

Virtual Mouse Using Gesture Recognition
Implementing a virtual mouse using gesture recognition .

Required Modules :

1)Opencv

          pip install opencv-python

2)Numpy

          pip install numpy

3)Pynput
  
          pip install pynput

4)WX
  
          pip install wxpython
  

How it works ?

Generally moving a mouse has two states :

  a)Moving the Cursor
  
  b)Clicking
  
Now we consider that we'll be detecting two objects (green color), and if the both appear this is the first state(moving the cursor) and if they are too near so that they form one single detected object this considered as the second state(clicking mode)

Finally ,this is how it will look like.
