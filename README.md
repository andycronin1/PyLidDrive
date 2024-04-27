2D Lid driven cavity simulation in python 

Steps: 

We will be solving the incompressible navier-stokes equations using chorin's splitting projection method
1. Solve the pressure equation without the pressure gradient 
2. Solve the pressure poisson equation 
3. Correct the velocities

Will be solving the NS equations in index notation 
 u = [u, v]
x = [x, y]
