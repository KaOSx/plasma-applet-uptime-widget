cmake_minimum_required(VERSION 3.16.0 FATAL_ERROR)

project(uptimeWidget)

find_package(ECM 6.0.0 REQUIRED NO_MODULE)
set(CMAKE_MODULE_PATH ${ECM_MODULE_PATH} ${ECM_KDE_MODULE_DIR})

find_package(Plasma REQUIRED)
find_package(Plasma5Support REQUIRED)

#add_subdirectory(translations)

plasma_install_package(package org.kde.uptimewidget)
