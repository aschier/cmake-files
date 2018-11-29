CMake files
===========

FindOpenMesh.cmake
------------------

A CMake file based on https://github.com/MEPP-team/MEPP/blob/master/cmake/FindOpenMesh.cmake,
which fixes the problem that the OpenMesh debug library is included in the link-libraries for
the release configuration of a multi-configuration project.
