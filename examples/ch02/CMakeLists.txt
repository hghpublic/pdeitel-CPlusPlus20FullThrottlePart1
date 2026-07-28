set(targets
    fig02_04
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch02
    )
endforeach()