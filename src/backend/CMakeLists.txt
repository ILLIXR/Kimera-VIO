### Add source code
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/VioBackEndModule.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/VioBackEnd.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/VioBackEndParams.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/RegularVioBackEnd.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/RegularVioBackEndParams.cpp"
)
