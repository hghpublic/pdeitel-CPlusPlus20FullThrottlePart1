set(target fig10_10)
add_executable(${target})
target_sources(${target} PRIVATE
    fig10_10.cpp
    
    SalariedCommissionEmployee.cpp
    SalariedCommissionEmployee.h
    
    SalariedEmployee.cpp
    SalariedEmployee.h
)
set_target_properties(${target} PROPERTIES
    FOLDER examples/ch10
)
