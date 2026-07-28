set(targets
    fig07_03
    fig07_06
    fig07_12
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch07
    )
endforeach()
