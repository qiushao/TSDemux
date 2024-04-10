add_executable(ts-demux-sample main.cpp
        m2tsextractor.cpp m2tsextractor.h
)

target_link_libraries(ts-demux-sample PUBLIC ts-demux)