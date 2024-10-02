# CSE 340 -Winter 2024
# Project 1
## Team Members: 
- Harshitha Kandula
- Pranav Kulkarni
- Saurabh Kumar
- Shubham Kumar
- Yashwant Kumar

## Description:
This project is a simple implementation of a web server using C++ and the Boost.Asio library. The server is capable of handling multiple client connections concurrently and serving static files from a specified directory. It also supports basic HTTP methods such as GET and HEAD.

## Features:
- Supports multiple client connections concurrently using Boost.Asio.
- Serves static files from a specified directory.
- Supports basic HTTP methods such as GET and HEAD.
- Handles errors and returns appropriate HTTP status codes.
- Can be compiled and run on Linux and Windows operating systems.

## Compilation:
To compile the project, you need to have the Boost library installed on your system. You can download it from https://www.boost.org/. Once you have Boost installed, you can compile the project using the following command:
```
g++ -std=c++11 -o server server.cpp -lboost_system -lboost_thread
```

## Running:
To run the server, use the following command: