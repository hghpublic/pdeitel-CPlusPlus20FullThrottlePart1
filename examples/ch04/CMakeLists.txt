set(targets
    fig04_04
    fig04_05
    fig04_06
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch04
    )
endforeach()
