CONFIGURE_FILE(${CMAKE_CURRENT_SOURCE_DIR}/pdfpc.in ${CMAKE_CURRENT_SOURCE_DIR}/pdfpc.1)

install(FILES
    pdfpc.1
DESTINATION
    share/man/man1
)
