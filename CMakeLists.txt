# get IDF version for comparison
set(idf_version "${IDF_VERSION_MAJOR}.${IDF_VERSION_MINOR}")

set(COMPONENT_SRCS
  esp_camera_helper.c
)

set(COMPONENT_ADD_INCLUDEDIRS
  include
)

set(COMPONENT_PRIV_REQUIRES esp32-camera nvs_flash)

register_component()
