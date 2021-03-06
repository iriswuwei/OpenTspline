Copyright (c) 2014, Thomas Mörwald, Vienna University of Technology.
License available in the "License.txt" file.

Author: Thomas Moerwald (Vienna University of Technology)
Email: moerwald@acin.tuwien.ac.at

Tspline geometry toolkit (Version 0.1)

Modules:
	- B-spline Basis function evaluation (cox-de-boor)
	- T-spline evaluation, control point insertion/removal, face splitting
	- T-spline merge/split
	- Multi-patch T-splines enabling extraordinary vertices
	- Rectangular domain creation
	- T-spline creation (plane, box, sphere)

Dependencies:
  Required:
  	- CGAL 4.4: Computational Geometry Algorithms Library (libcgal-dev)
  	- Eigen 3.2.0: Template library for linear algebra (libeigen3-dev)
  Optional:
    - OpenMP: Open Multi-Processing library (www.openmp.com)
    - TomGine 4.1: Visualization and rendering engine (http://users.acin.tuwien.ac.at/tmoerwald/?site=4)
 

  * Note that apps require TomGine 4.1 for visualization (http://users.acin.tuwien.ac.at/tmoerwald/?site=4)
