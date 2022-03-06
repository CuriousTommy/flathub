cmake_minimum_required(VERSION 3.10)
project(cmake_flatpak_test)

include(FindPkgConfig)
message(WARNING "PKG_CONFIG_PATH: $ENV{PKG_CONFIG_PATH}")
pkg_check_modules(FUSE REQUIRED fuse)
