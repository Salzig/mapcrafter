set(SOURCE
	${SOURCE}
	${CMAKE_CURRENT_SOURCE_DIR}/iniconfig.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/mapcrafterconfig.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/mapcrafterconfighelper.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/validation.cpp
	PARENT_SCOPE
)

set(HEADERS
	${HEADERS}
	${CMAKE_CURRENT_SOURCE_DIR}/iniconfig.h
	${CMAKE_CURRENT_SOURCE_DIR}/mapcrafterconfig.h
	${CMAKE_CURRENT_SOURCE_DIR}/mapcrafterconfighelper.h
	${CMAKE_CURRENT_SOURCE_DIR}/validation.h
	PARENT_SCOPE
)
