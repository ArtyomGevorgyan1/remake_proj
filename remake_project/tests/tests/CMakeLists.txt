include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})
add_executable(run_tests tests.cpp)
target_link_libraries(run_tests gtest gtest_main)
