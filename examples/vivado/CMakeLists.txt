
CONFIGURE_FILE(Makefile.mnemosyne Makefile.mnemosyne)

INSTALL(FILES config.cfg DESTINATION examples/vivado PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
INSTALL(FILES ${CMAKE_BINARY_DIR}/examples/vivado/Makefile.mnemosyne DESTINATION examples/vivado PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
