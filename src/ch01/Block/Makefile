ccflags = /MDd /D "WIN32" /I "../../../freeglut-3.0.0/include" /I "../../../GLTools/include"

libs = ../../../freeglut-3.0.0/lib/Debug/freeglut_staticd.lib ../../../GLTools/gltools.lib

Block: Block.cpp
	cl $(ccflags) $(libs) Block.cpp 

clean:
	del /Q *.obj