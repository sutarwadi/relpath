add_executable(compile.t compile.t.cpp)
add_test(NAME compile.t COMMAND compile.t)
target_link_libraries(compile.t test)
