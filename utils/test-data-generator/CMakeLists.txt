add_executable (test-data-generator main.cpp)
target_link_libraries (test-data-generator dbms ${Boost_PROGRAM_OPTIONS_LIBRARY})

add_executable (markov-model markov-model.cpp)
target_link_libraries (markov-model dbms ${Boost_PROGRAM_OPTIONS_LIBRARY})
