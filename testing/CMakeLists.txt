include(def_test)

add_subdirectory(gtest)
include_directories(gtest/include)

def_test(TestGeodetic2Local
  SOURCES geodetic2local_test.cpp
  DEPENDS geocon MSPdtcc msp_ccs
  )