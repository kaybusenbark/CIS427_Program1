in terminal one
gcc server.cpp sqlite3.c -o server -lpthread -ldl

in terminal two
gcc client.cpp -o client 

in terminal one 
./server

in terminal two
./client 127.0.0.1

then you should be in to test
