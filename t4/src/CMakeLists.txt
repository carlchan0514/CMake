LINK_DIRECTORIES(/home/chendong/src/backup/cmake/usr/lib)
ADD_EXECUTABLE(main main.c)
INCLUDE_DIRECTORIES(/home/chendong/src/backup/cmake/usr/include/hello)
TARGET_LINK_LIBRARIES(main hello)
