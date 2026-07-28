set(targets
    fig11_02
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch11
    )
endforeach()
