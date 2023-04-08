add_executable (example "source.cpp" "header.hpp")

target_compile_features (example PRIVATE cxx_std_17)