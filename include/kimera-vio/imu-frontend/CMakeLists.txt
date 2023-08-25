### Add source code for kimera_vio
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/ImuFrontEnd-definitions.h"
  "${CMAKE_CURRENT_LIST_DIR}/ImuFrontEnd.h"
  "${CMAKE_CURRENT_LIST_DIR}/ImuFrontEndParams.h"
)
