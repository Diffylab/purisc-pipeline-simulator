# purisc-pipeline-simulator
Shows ideal pipeline behaviour given a program


#Compiling
Just run
    make

#Usage 
    ./purisc-pipeline-simulator filename [exec limit] 

The input file is a human readable machine code file. Each line of the file
represents the contents of one memory location, represented in base 10. All
memory locations must have a value in the file.

The execution limit (the number of cycles the simulation should run for) can be
specified as the second argument. The default is 20.

