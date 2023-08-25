### Add source code for stereoVIO
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX}
  PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/ThreadsafeImuBuffer.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/Statistics.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/Histogram.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/UtilsGeometry.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/UtilsOpenCV.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/UtilsNumerical.cpp"
)
