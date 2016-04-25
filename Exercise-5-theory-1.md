#Theory for Exercise 5, problem 1
![Open channel](Images/open_channel.png)<br/>
*Figure 1. Schematic diagram of pressure-driven flow in a channel.*

The viscosity of ice depends on both temperature and stress. For simplicity, we’ll consider the case where viscosity is only a function of shear stress. Consider a channel of width *h* centered about *y* = 0, with lateral boundaries at *y* = ±*h*/2 (Figure 1). A pressure gradient *Δp* = *p*<sub>1</sub> - *p*<sub>0</sub> drives flow within the channel of length *L*.  The shear stress in the fluid depends on the applied pressure gradient and the distance from the channel boundaries

![Equation 1](Images/Equation1.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 1]**

where *τ* is the shear stress. We know that for Newtonian fluids

![Equation 2](Images/Equation2.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 2]**

where *η* is the dynamic viscosity of the fluid. Substituting the right side of Equation 2 into the left side of Equation 1 we find

![Equation 3](Images/Equation3.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 3]**

Integrating Equation 3 twice we get

![Equations 4 and 5](Images/Equation4-5.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqns. 4, 5]**

Since we know *du*/*dy* = 0 at *y* = 0, we find *c*<sub>1</sub> = 0, and because we assume zero slip at the boundaries of the channel (*u* = 0 at *y* = ±*h*/2), *c*<sub>2</sub> = (1/2*η*)(*dp*/*dx*)(*h*/2)<sup>2</sup>. Thus,

![Equation 6](Images/Equation6.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 6]**

This is the velocity profile for a Newtonian fluid, but as you will recall, we learned that ice is a non-Newtonian (nonlinear viscous) fluid. As such, the behavior should be modeled using a power-law, where the strain rate is a related to the shear stress as follows

![Equation 7](Images/Equation7.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 7]**

where *a* is a function of the viscosity and temperature (we will ignore temperature for now), and *n* is the power-law exponent. If we solve Equation 7 in terms of *τ*, we can substitute the result into Equation 1 to get

![Equation 8](Images/Equation8.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 8]**

Assuming symmetry about the center line, *y* = 0, and integrating we see

![Equation 9](Images/Equation9.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 9]**

Now integrate Equation 9 and assume *u* = 0 at *y* = ±*h*/2

![Equation 10](Images/Equation10.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 10]**

The mean velocity in the fluid is

![Equation 11](Images/Equation11.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 11]**

We can calculate a non-dimensional velocity now by dividing the velocity at any point in the channel by the mean velocity

![Equation 12](Images/Equation12.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Eqn. 12]**
