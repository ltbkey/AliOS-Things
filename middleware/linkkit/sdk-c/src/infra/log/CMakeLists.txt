INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR})
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/include)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/include/exports)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/include/imports)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/src/infra/log/)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/src/infra/utils/)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/src/infra/utils/digest)
INCLUDE_DIRECTORIES (${PROJECT_SOURCE_DIR}/src/infra/utils/misc)

ADD_LIBRARY (iot_log OBJECT
    ${PROJECT_SOURCE_DIR}/src/infra/log/iotx_log.c
    ${EXTRA_C_SOURCES}
)

