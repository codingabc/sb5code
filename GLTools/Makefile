objs = GLBatch.obj glew.obj GLShaderManager.obj GLTools.obj GLTriangleBatch.obj math3d.obj
ccflags = /I "include" /D "WIN32" /D "WIN32" /D "_LIB" /D "GLEW_STATIC" /MDd

GLTools : $(objs)
	lib /OUT:GLTools.lib $(objs)

GLBatch.obj : src/GLBatch.cpp
	cl /c  $(ccflags) src/GLBatch.cpp

glew.obj : src/glew.c
	cl /c $(ccflags) src/glew.c

GLShaderManager.obj : src/GLShaderManager.cpp
	cl /c $(ccflags) src/GLShaderManager.cpp

GLTools.obj : src/GLTools.cpp
	cl /c $(ccflags) src/GLTools.cpp

GLTriangleBatch.obj : src/GLTriangleBatch.cpp
	cl /c $(ccflags) src/GLTriangleBatch.cpp

math3d.obj : src/math3d.cpp
	cl /c $(ccflags) src/math3d.cpp

clean :
	del /Q *.obj