CPPFLAGS = -std=c++11
all: main.exe 

main.exe: QA.o openningMessage.o main.o
	g++ -o $@ $(CPPFLAGS) QA.o openningMessage.o main.o 

%.o: %.cpp
	g++ $(CPPFLAGS) -c $< -o $@ 

clean:
	del  *.o *.exe
# On Windows, use: del *.o *.exe
# On Linux or MacOS, use: rm -f *.o *.exe
