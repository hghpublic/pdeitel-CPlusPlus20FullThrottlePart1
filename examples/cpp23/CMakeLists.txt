# https://www.kitware.com/import-std-in-cmake-3-30/
set(targets
    cpp23
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/cpp23
    )
endforeach()
