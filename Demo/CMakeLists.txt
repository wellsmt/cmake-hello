add_executable (helloDemo demo.cpp)
add_executable (helloDemoB demo_b.cpp)

target_link_libraries (helloDemo LINK_PUBLIC Hello)
target_link_libraries (helloDemoB LINK_PUBLIC Hello)
