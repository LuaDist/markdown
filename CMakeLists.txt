# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(markdown NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
INCLUDE(dist.cmake)

# modules
INSTALL (FILES markdown.lua DESTINATION ${INSTALL_LMOD})
