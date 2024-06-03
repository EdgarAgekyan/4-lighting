# Assignment 4
<br>
For this assignment, I was able to add a cube, sphere, and lighting to my blocky world scene/ This includes proper ambient, diffusion, and specular lighting.
<br>
The yellow cube is the visual marker of the location of the light.
<br>
There are buttons to turn the light on/off (on by default), to turn the normals on/off (off by default), and also buttons to turn on the movement for the light to dynamically see how the lighting works (on by default).
<br>
There is also a set of sliders at the bottom that the user can use to move the Camera.
<br>
I did not get the chance to implement the spotlight. I began on it and some of the code is still in the World.js but commented out.
<br>
The frame rate of my submission is a little on the lower side (around 30fps on my local machine) which I believe I could have optimized more if I put in the time. I use the generic render() function given from the Youtube lecture videos and I could have put more thought into optimizing that as well as other components of my code.
<br>
I also added an extra flag/variable to the Cube class so that each cube has an option where it can have it's specular lighting turned off. For example, it can be seen in my scene that the sphere has specular lighting on (the Cube constructor initializes to 1 by default) and it can be turned off by setting the variable to 0 or something else.