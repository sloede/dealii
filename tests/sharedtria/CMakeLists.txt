cmake_minimum_required(VERSION 3.13.4)
include(../setup_testsubproject.cmake)
project(testsuite CXX)
include(${DEAL_II_TARGET_CONFIG})
deal_ii_pickup_tests()
