add_library(ts-demux STATIC AdaptationField.h
        ElementaryStreamData.cpp ElementaryStreamData.h
        Error.h
        M2TSProcessor.cpp M2TSProcessor.h
        PacketHeader.h
        PAT.h
        PESPacketHeader.h
        PMT.h
        TableHeader.h
        util.cpp util.h
)

target_include_directories(ts-demux PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})