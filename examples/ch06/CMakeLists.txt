set(targets
    fig06_01
    fig06_02
    fig06_03
    fig06_11
    fig06_12
    fig06_13
    fig06_14
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch06
    )
endforeach()
