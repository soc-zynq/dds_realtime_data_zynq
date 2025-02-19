# Create a library called "dds_realtime_data_zynq"
add_library(dds_realtime_data_zynq_lib dds_realtime_data_zynq.cpp)

# Specify include directories for the library
target_include_directories(dds_realtime_data_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
