### Add source code for stereoVIO
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX}
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/InitializationFromImu.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/InitializationBackEnd.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/OnlineGravityAlignment.cpp"
)
