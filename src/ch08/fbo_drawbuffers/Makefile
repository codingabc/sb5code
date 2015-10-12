ccflags = /MDd /EHsc /D "WIN32" /I "../../../freeglut-3.0.0/include" /I "../../../GLTools/include" /I "../../Models/Ninja"

libs = ../../../freeglut-3.0.0/lib/Debug/freeglut_staticd.lib ../../../GLTools/gltools.lib

main = fbo_drawbuffers

$(main) : $(main).cpp sbm.obj
	cl $(ccflags) $(libs) $(main).cpp sbm.obj

sbm.obj : ../../Models/Ninja/sbm.cpp
	cl $(ccflags) /c ../../Models/Ninja/sbm.cpp

clean:
	del /Q *.obj