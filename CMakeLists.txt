###############################################################################
#
# gl3w
# CMakeLists.txt
#
# Howard N Smith (howard@blacktriangles.com)
# February 4, 2016
# (c) blacktriangles 2015 (http://www.blacktriangles.com)
###############################################################################

cmake_minimum_required( VERSION 3.4.0 )

project( gl3w )

include_directories( ${CMAKE_CURRENT_LIST_DIR} )
add_library( gl3w GL/gl3w.c )
