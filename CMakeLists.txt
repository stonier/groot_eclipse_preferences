##############################################################################
# Cmake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(groot_eclipse_preferences)

##############################################################################
# Installs
##############################################################################

STRING(REPLACE "_" "-" DASHED_PROJECT_NAME ${PROJECT_NAME})

install(DIRECTORY neon DESTINATION ${CMAKE_INSTALL_PREFIX}/share/${DASHED_PROJECT_NAME})
