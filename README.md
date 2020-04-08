# Wall Shear Stress in 3D
On Wall Shear Rate and Wall Shear Stress computation on Unstructured Grids using VMTK

Here are some notes on the way wall shear stress calculated in VMTK package and also benchmark 3D velocity fields.

In simple words, having a velocity field \vec u and wall normal vectors \vec n:

shear rate tensor:

![](images/strain_tensor.png)

wall shear rate:

![](images/wall_shear_rate.png)

or 

shear rate tensor components:

![](images/strain_tensor_components.png)

wall shear rate components:

![](images/wall_shear_rate_components.png)

and

wall shear stress components:

![](images/wall_shear_rate_components.png)

where

![](images/velocity_gradient.png)
