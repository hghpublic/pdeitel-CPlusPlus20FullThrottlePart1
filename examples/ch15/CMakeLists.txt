set(targets
    # fig15_04
    # fig15_05
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch15
    )
endforeach()
