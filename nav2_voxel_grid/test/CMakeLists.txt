ament_add_gtest(voxel_grid_tests voxel_grid_tests.cpp)
target_link_libraries(voxel_grid_tests voxel_grid)

ament_add_gtest(voxel_grid_bresenham_3d voxel_grid_bresenham_3d.cpp)
target_link_libraries(voxel_grid_bresenham_3d voxel_grid)
