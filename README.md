# Exercise 12
Let's see how we can apply revolve-boss, revolve-cut, extrude-boss, extrude-cut, fillet, and mirror feature for a drawing below 
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image1.png)</br>

Starting from the top plane, we can build the L shape and the center line line below and revolve it
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image2.png)</br>

We can then add the rib from the same plane and extrude-boss it with .25 inches thickness following the drawing
Please note that the trapesium shape should go a bit deeper (in this case I go up to the internal diameter) to anticipate unfulfill area during extrusion (see area A).
It would subsequently cause a burr effect as seen on area B which we will use revolve-cut technique later to remove it.
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image3.png)</br>

Before we remove the burr, let's us mirror above feature like below
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image4.png)</br>

We can then sketch the area we would like to revolve-cut which is large enough to cover those excess material
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image5.png)</br>

Herewith how those virtual eraser revolve along the half circle to remove the burr
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image6.png)</br>

And we can apply extrude cut to add the hole along with the specification from the drawing
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image7.png)</br>

Last but not least we can add the fillet as follow
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image8.png)</br>

Herewith is the final 3D model
![](https://github.com/ft-cnc/SW2024-EX12/blob/main/image9.png)</br>

