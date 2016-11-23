##
## A) Package-specific configuration options
##
#
#TRIBITS_CONFIGURE_FILE(${PACKAGE_NAME}_config.h)
#
##
## B) Define the header and source files (and include directories)
##
#
#SET(HEADERS "")
#SET(SOURCES "")
#
## To include the configured header above
#INCLUDE_DIRECTORIES(${CMAKE_CURRENT_BINARY_DIR})
#
#INCLUDE_DIRECTORIES(${CMAKE_CURRENT_SOURCE_DIR})
#
#APPEND_SET(HEADERS
#   Cholesky
#   Core
#   Eigenvalues  
#)
#
#
##
## C) Define the targets for package's library(s)
##
#
#TRIBITS_ADD_LIBRARY(
#  HF_source
#  HEADERS ${HEADERS}
#  )
