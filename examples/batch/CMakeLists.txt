
CONFIGURE_FILE(Makefile.mnemosyne Makefile.mnemosyne)

INSTALL(FILES config.cfg DESTINATION examples/batch PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
INSTALL(FILES ${CMAKE_BINARY_DIR}/examples/batch/Makefile.mnemosyne DESTINATION examples/batch PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
