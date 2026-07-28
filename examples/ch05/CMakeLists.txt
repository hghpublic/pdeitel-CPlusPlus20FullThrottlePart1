set(targets
    fig05_01
    fig05_05
    fig05_08
    fig05_10
    fig05_13
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch05
    )
endforeach()
