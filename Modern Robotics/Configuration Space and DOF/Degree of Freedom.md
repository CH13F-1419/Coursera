# Degree of Freedom
#robotfundamentals 

The number of degrees of freedom of a robot can be calculated using Grubler's formula,

<img src="https://bit.ly/3B14ygO" align="center" border="0" alt="\text{dof}=m(N-1-J)+\sum_{i=1}^{J}f_i" width="187" height="49" />

where `m=3` for planar mechanisms and `m=6` for spatial mechanisms, `N` is the number of links (including the ground link), `J` is the number of joints, and `f_i` is the number of degrees of freedom of each joint summed up.