# Aseprite
# Copyright (C) 2001-2016  David Capello

add_library(gfx-lib
  clip.cpp
  hsv.cpp
  packing_rects.cpp
  region.cpp
  rgb.cpp)

target_link_libraries(gfx-lib
  ${PIXMAN_LIBRARY})
