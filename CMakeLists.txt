add_library(portable-memory-mapping STATIC
    MemoryMapped.cpp
    MemoryMapped.h
)

target_include_directories(portable-memory-mapping INTERFACE ./)

target_link_libraries(portable-memory-mapping)
