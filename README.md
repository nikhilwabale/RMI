ASSIGNMENT 1 :- RMI  


javac *.java

rmic AddServerImpl

rmiregistry

java AddServer

java AddClient 127.0.0.1 10 5


ASSIGNMENT 2 -



//command

idlj -fall ReverseModule.idl

javac .java ReverseModule/.java

orbd -ORBInitialPort 1050&

java ReverseServer -ORBInitialPort 1050& -ORBInitialHost localhost&

java ReverseClient -ORBInitialPort 1050 -ORBInitialHost localhost



ASSIGNMENT 3 :-


//command

sudo apt-get install openmpi-bin libopenmpi-dev

mpicc MPI.c -o MPI

mpicc -I/path/to/mpi/include MPI.c -o MPI

./MPI


ASSIGNMENT 4 :-



javac *.java

java BerkeleyAlgorithm


ASSIGNMENT 5 -

