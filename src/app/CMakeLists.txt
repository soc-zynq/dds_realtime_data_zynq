# Add source files
add_executable(${PROJECT_NAME} main.cpp)

# Link the project library
target_link_libraries(${PROJECT_NAME} dds_realtime_data_zynq_lib)
