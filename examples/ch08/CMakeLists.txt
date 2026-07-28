set(targets
    fig08_09
    fig08_16
    fig08_17
    fig08_18
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch08
    )
endforeach()
