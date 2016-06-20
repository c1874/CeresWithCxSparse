ceres-windows
=============

A ceres-solver + CXSparse wrapper for Visual Studio.



Sample projects (using ceres-solver's code examples) are also embedded in the solution.

Dependencies
============

  * Eigen (http://eigen.tuxfamily.org/): Tested with v3.2.2. It's a header-only 
    library, so just extract Eigen to the solution directory and it should compile. 
    Alternatively, set it up in one of your default include directories.

Libraries
=========

  * ceres-solver: http://ceres-solver.org/

  * CXSparse: http://www.cise.ufl.edu/research/sparse/CXSparse/

  * Google glog: https://code.google.com/p/google-glog/


License
=======

The license of this wrapper is the same as ceres-solver and glog, New BSD license.

Note that CXSparse is distributed under the GNU LGPL license.



Usage:
If you want to use dynamic library,you just need to add 
*ceres_gd.lib
*libglog_static_gd.lib
to the additional libs and copy the dlls to your exe directory

and if you want to use static library,you need to
*ceres_stastic_gd.lib
*libglog_static_gd.lib
*CXSparse_gd.lib
to the additional libs
