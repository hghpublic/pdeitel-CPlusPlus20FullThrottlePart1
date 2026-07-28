set(target fig20_13)
add_executable(${target})
target_sources(${target} PRIVATE
    fig20_13.cpp

    Commission.cpp
    Commission.h

    Employee.cpp
    Employee.h

    Salaried.cpp
    Salaried.h
)
set_target_properties(${target} PROPERTIES
    FOLDER examples/ch20
)
