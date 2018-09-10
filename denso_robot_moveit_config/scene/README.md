### example.scene

```
box_scene
* box1
1
box
0.1 0.2 0.3
1.0 1.0 1.0
0 0 0 1
0 1 0 1
.
```
#### file format

```
#box_scene # maybe scene name
#* box1 # object name
#1 # number of shapes
#box # type of shape (box, cylinder, sphere)
#0.1 0.2 0.3 # size of shape
#1.0 1.0 1.0 # position of shape
#0 0 0 1 # orientation of shape
#0 1 0 1 # RGBA color of shape
#. # necessary final dot
```