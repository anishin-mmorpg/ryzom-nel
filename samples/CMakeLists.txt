ADD_SUBDIRECTORY(misc)

IF(WITH_3D)
  ADD_SUBDIRECTORY(3d)
ENDIF()

IF(WITH_GEORGES)
  ADD_SUBDIRECTORY(georges)
ENDIF()

IF(WITH_NET)
  ADD_SUBDIRECTORY(net)
ENDIF()

IF(WITH_PACS)
  ADD_SUBDIRECTORY(pacs)
ENDIF()

IF(WITH_SOUND)
  ADD_SUBDIRECTORY(sound)
ENDIF()
