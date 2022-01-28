qt5_add_resources(kdevagami_SRCS resources.qrc)
add_executable(kdevagami main.cpp ${kdevagami_SRCS})
target_link_libraries(kdevagami Qt5::Qml Qt5::Gui)

