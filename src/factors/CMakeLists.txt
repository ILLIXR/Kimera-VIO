### Add source code for stereoVIO
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX}
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/ParallelPlaneRegularFactor.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/PointPlaneFactor.cpp"
)

