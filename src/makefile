COMMON=-O2 -I../mjpro150/include -L../mjpro150/bin -std=c++11 -mavx

default:
	g++ $(COMMON) hello.cpp -lmujoco150 -lGL -lglew ../mjpro150/bin/libglfw.so.3 -o ../bin/hello
	g++ $(COMMON) pendulum.cpp -lmujoco150 -lGL -lglew ../mjpro150/bin/libglfw.so.3 -o ../bin/pendulum
