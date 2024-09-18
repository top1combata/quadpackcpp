
add_executable(abscissae abscissae.cpp)
add_executable(logarithmic logarithmic.cpp)

target_link_libraries(abscissae   PUBLIC quadpackcpp)
target_link_libraries(logarithmic PUBLIC quadpackcpp)