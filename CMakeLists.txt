# CMakeList.txt : CMake project for FGIRC, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (FGIRC "FGIRC.cpp" "FGIRC.h" 
	"IRCClient/IRCClient.cpp" "IRCClient/IRCHandler.cpp" "IRCClient/IRCSocket.cpp" "IRCClient/Thread.cpp"
	"IRCClient/IRCClient.h" "IRCClient/IRCHandler.h" "IRCClient/IRCSocket.h" "IRCClient/Thread.h"
)

# TODO: Add tests and install targets if needed.
