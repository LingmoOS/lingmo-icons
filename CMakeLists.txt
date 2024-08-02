cmake_minimum_required(VERSION 3.5)
project(lingmo-icons)

include(FeatureSummary)

install(DIRECTORY ocean DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
install(DIRECTORY ocean-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
