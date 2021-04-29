# slider-crank-analysis
This is the simple python code for analyzing how the displacement and velocity of the slider changes with the  crank angle.

Code consists of 5 parts
1.The driver code (it calcualtes the displacement and velocity values for the range of crank angles and store them in the lists)
2.Displacement Plot(this plots the plot of displacement and crank angle, crank angle is taken along x- axis and displacement is taken along the y-axis)
3.Velociy Plot(this plots the plot of velocity vs crank angel)
4.Displacement and Velocity for particular cranka angle (if the angle is given then it gives the displacement and velocity at that angle)
5.Data(This gives the data that we used for plotting the displacement and velocity plots in the form of panda dataframe)

-------------Running the code---------------
when we run the driver code it asks for four parameters
the parameters are
1.connecting rod length
2.crank length
3.Angular speed of crank
4.No of rotations of crank

When we given these values through standard input it gives the information about the parameters that we enterd and gives the
maximum displacement that the slider can attain for these particular parameters.

When we run the Displacement code it gives teh plot of displacement vs crank angle.

When we run the Velocity code it gives the plot of velocity vs crank angle,in addition to that it displays the maximum and minimum
velocity that the slider can attain during the ratation

When we run the code for particular angle it displays the displacement and velocity of slider for that particular angle

When we run the data code that gives the data that we used to plot the displacement and velocity plots.
The data has the displacement and velocity for the each angle.

---------------Conclusion--------------
Equations used  for calculating the displacement and velocity of slider.
      X = r*(1-cosθ + sin^2(θ)/2*n) this is how the displacement depends upon the crank angle
      V= r*w*(sinθ + sin2θ/2*n)  this is how the velocity depends upon the crank angle
      
      
