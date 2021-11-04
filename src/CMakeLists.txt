set(CMAKE_CXX_STANDARD 17)

include_directories(${CMAKE_SOURCE_DIR}/lib/tgbot-cpp/include)

add_executable(${CMAKE_PROJECT_NAME} main.cpp)

target_link_libraries(${CMAKE_PROJECT_NAME} TgBot)