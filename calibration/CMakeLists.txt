cmake_minimum_required(VERSION 2.8)
PROJECT( displayimage )
FIND_PACKAGE( OpenCV REQUIRED )
ADD_EXECUTABLE( displayimage simple.cpp )
TARGET_LINK_LIBRARIES( displayimage ${OpenCV_LIBS} )
