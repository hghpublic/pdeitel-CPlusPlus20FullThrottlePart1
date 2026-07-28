set(targets
    fig12_04
    fig12_04modified
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch12
    )
endforeach()
