default: main

main: main.o tv.o
#将file1.o和file2.o连接为可执行的二进制文件main
	g++ -o main main.o tv.o
	rm -f *.o
	
main.o: main.cpp
#表示只编译file1.c文件，成功时输出目标文件file1.o
	g++ -c main.cpp
tv.o: tv.cpp
	g++ -c tv.cpp

