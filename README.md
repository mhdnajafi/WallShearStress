# Wall Shear Stress in 3D
On Wall Shear Rate and Wall Shear Stress computation on Unstructured Grids using VMTK

Here are some notes on the way wall shear stress calculated in VMTK package and also benchmark files.

shear rate tensor: S = (\nabla u + (\nabla u)^{T}) / 2

wall shear rate: \vec {\sigma}_w = 2 * (S \cdot n - (n \cdot S \cdot n) \cdot n)

or 

\vec \sigma_{wi} = (u_{i,j}+u_{j,i}) n_j - (u_{k,j}+u_{j,k}) n_j n_k n_i

and

\vec \tau_{wi} = \mu \, ( (u_{i,j}+u_{j,i}) n_j - (u_{k,j}+u_{j,k}) n_j n_k n_i )
