.PHONY:all

all:socks5 tranfer

tranfer:epoll.cc tranfer.cc
		g++ $^ -o $@ -std=c++11 

socks5:epoll.cc socks5.cc
		g++ $^ -o $@ -std=c++11 

.PHONY:clear
		
			
clear:
		rm socks5 tranfer

