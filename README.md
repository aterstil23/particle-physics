# particle-physics

The motion of the particle is obtained by updating the acceleration in all axis depending on the distance of the particles of each other. Then the velocity increment in the
update by the acceleration times a small delta t. The position in all axis is increment also with the updated speed times the delta time.
There are 2 groups of particles that repell one group from the other. 
There are cohesion attraction and repulsion between the particles of a same group colored differently.
At the beginning i used an inverse square law for the attraction and repulsion of the particles and the particles just smashed into each other and repulled violent and exploding in every direction.
Then i tweaked the power of the inverse law so it was less than 2 so that the rate of change of the attraction wouldn't change as much. And by accident i made the power of the inverse law of the repulsion smaller than 1 making the repulsion weaker, so it seemed to work out and assume a certain cohesion between two groups of particles.
law.
Also, i added an offeset for which when the distance between the particles in a same group is smaller than a certain value the repulsion kicks. The attraction will only occur when the particles are further than their initial distance (equilibrium distance). Initially the 2 groups of particles form a kind a disc.
Also, to make the code work you need to statically link GLFW library in c++. 
It shown how to do it in the video:
https://youtu.be/or1dAmUO8k0
Also, if the code doesn't run, you can try adding opengl32.lib in the additional dependencies. And for it to work, if you chose the X32 precompiled binaries, make sure your code editor runs on X32(or X86 the same) not on X64.





https://user-images.githubusercontent.com/121896803/227749722-a3b3f365-88df-4df8-a5e4-f6776f269b6c.mp4

