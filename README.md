

# A simulation of a falling bomb using the c4dynamics library

The simplified bomb's falling model is described using the following two equations:

$$ \left\{ \begin{align*} 
ma_{x} &= -\frac{1}{2} Cρv_{x}^2A_{x} \\ 
ma_{z} &= \frac{1}{2} Cρv_{z}^2A_{z} - mg 
\end{align*} \right. $$

,where:\
m - object mass\
$a_{k}$ - acceleration of the object in direction k\
C - drag coefficient\
ρ - air density\
$A_{k}$ - cross section area of falling object in direction k\
$v_{k}$ - falling object velocity in direction K\
g - gravitation constant

The simulation and modeling process is performed using the [c4dynamics](https://github.com/C4dynamics)  package.
