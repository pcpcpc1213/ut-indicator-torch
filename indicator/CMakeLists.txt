configure_file(nfsprodriver-indicator-torch.py ${CMAKE_CURRENT_BINARY_DIR}/nfsprodriver-indicator-torch.py)

install(FILES ${CMAKE_CURRENT_BINARY_DIR}/nfsprodriver-indicator-torch.py DESTINATION ${DATA_DIR}indicator)
install(FILES "nfsprodriver-indicator-torch.conf" DESTINATION ${DATA_DIR}indicator)
install(FILES "install.sh" DESTINATION ${DATA_DIR}indicator)
install(FILES "com.nfsprodriver.indicator.torch" DESTINATION ${DATA_DIR}indicator)
install(FILES "uninstall.sh" DESTINATION ${DATA_DIR}indicator)
