#这个要使用绝对路径
LINK_DIRECTORIES(C:/Users/czh/source/repos/test1/t3_s/tmp/usr/lib)
INCLUDE_DIRECTORIES(C:/Users/czh/source/repos/test1/t3_s/tmp/usr/include/hello)

ADD_EXECUTABLE(main main.c)
#要放在ADD_EXECUTABLE 之后
TARGET_LINK_LIBRARIES(main hello.lib)