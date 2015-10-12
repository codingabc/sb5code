ccflags = /MDd /D "WIN32" /I "../../../freeglut-3.0.0/include" /I "../../../GLTools/include"

libs = ../../../freeglut-3.0.0/lib/Debug/freeglut_staticd.lib ../../../GLTools/gltools.lib

main = Smoother

$(main) : $(main).cpp
	cl $(ccflags) $(libs) $(main).cpp

clean:
	del /Q *.obj