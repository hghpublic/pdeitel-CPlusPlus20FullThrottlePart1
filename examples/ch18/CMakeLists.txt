find_path(TL_GENERATOR_INCLUDE_DIRS "tl/generator.hpp")
set(targets
    fig18_01
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    target_include_directories(${target} PRIVATE ${TL_GENERATOR_INCLUDE_DIRS})
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch18
    )
endforeach()
