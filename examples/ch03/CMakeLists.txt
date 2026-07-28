find_package(Boost REQUIRED COMPONENTS multiprecision)

set(targets
    fig03_05
    fig03__control_statement_snippets
    fig03__narrowing
)
foreach(target ${targets})
    add_executable(${target} ${target}.cpp)
    target_link_libraries(${target} PRIVATE Boost::multiprecision)
    set_target_properties(${target} PROPERTIES
        FOLDER examples/ch03
    )
endforeach()
