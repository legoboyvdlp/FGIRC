cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
set(SOURCES IRCClient.cpp IRCHandler.cpp IRCSocket.cpp Thread.cpp)
set(HEADERS IRCClient.h IRCHandler.h IRCSocket.h Thread.h)
add_executable(IRCClientLib "${SOURCES}" "${HEADERS}")
