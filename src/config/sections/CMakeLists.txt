set(SOURCE
	${SOURCE}
	${CMAKE_CURRENT_SOURCE_DIR}/base.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/map.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/marker.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/world.cpp
	PARENT_SCOPE
)

set(HEADERS
	${HEADERS}
	${CMAKE_CURRENT_SOURCE_DIR}/base.h
	${CMAKE_CURRENT_SOURCE_DIR}/map.h
	${CMAKE_CURRENT_SOURCE_DIR}/marker.h
	${CMAKE_CURRENT_SOURCE_DIR}/world.h
	PARENT_SCOPE
)
