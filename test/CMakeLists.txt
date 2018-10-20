find_package(GTest)
enable_testing()
set(TEST_LIBRARIES GTest::GTest;GTest::Main)

add_custom_target(tests ALL)
add_subdirectory(perftest)
add_subdirectory(unittest)
