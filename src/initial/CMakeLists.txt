### Add source code for stereoVIO
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX}
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/InitializationFromImu.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/InitializationBackend.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/OnlineGravityAlignment.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/CrossCorrTimeAligner.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/TimeAlignerBase.cpp"
)
