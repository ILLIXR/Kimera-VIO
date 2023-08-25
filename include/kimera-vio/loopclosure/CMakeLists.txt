### Add source code for LoopClosureDetector
target_sources(kimera_vio${ILLIXR_BUILD_SUFFIX} PRIVATE
 "${CMAKE_CURRENT_LIST_DIR}/LoopClosureDetector-definitions.h"
 "${CMAKE_CURRENT_LIST_DIR}/LoopClosureDetector.h"
 "${CMAKE_CURRENT_LIST_DIR}/LoopClosureDetectorParams.h"
 "${CMAKE_CURRENT_LIST_DIR}/LcdThirdPartyWrapper.h"
)
