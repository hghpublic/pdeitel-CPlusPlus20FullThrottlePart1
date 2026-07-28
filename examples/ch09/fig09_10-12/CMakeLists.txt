set(target fig09_12)
add_executable(${target})
target_sources(${target} PRIVATE
    fig09_12.cpp

    Time.cpp
    Time.h
)
set_target_properties(${target} PROPERTIES
    FOLDER examples/ch09
)
