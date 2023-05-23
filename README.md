# RMI

Distributed System lab commands
--------------Assignment-1 (RMI)---------------------------
1)open terminal in RMI folder
sanket@ubuntu:~/Desktop/RMI$ javac *.java
sanket@ubuntu:~/Desktop/RMI$ rmic AddServerImpl
sanket@ubuntu:~/Desktop/RMI$ rmiregistry
2)In RMI folder create 'client' folder and copy below files
Addclient.class
AddServerImpl_stub.class
AddServerlntf.class
3)In RMI folder create 'server' folder and copy below files
AddServer.class
AddServerImpl.class
AddServerImpl_stub.class
AddServerlntf.class
4)open new terminal in server folder
sanket@ubuntu:~/Desktop/RMI/server$ java AddServer
5)open new terminal in client folder
sanket@ubuntu:~/Desktop/RMI/client$ java AddClient 127.0.0.1 10 5
===============x=========x===========x============================
--------------Assignment-2 (IDL CORBA)------------------------------------------------
1)open terminal in IDL CORBA folder
sanket@ubuntu:~/Desktop/IDL CORBA$ idlj -fall ReverseModule.idl
sanket@ubuntu:~/Desktop/IDL CORBA$ javac *.java ReverseModule/*.java
sanket@ubuntu:~/Desktop/IDL CORBA$ orbd -ORBInitialPort 1050&
sanket@ubuntu:~/Desktop/IDL CORBA$ java ReverseServer -ORBInitialPort 1050& -ORBInitialHost localhost&
2)open another new terminal in IDL CORBA folder
sanket@ubuntu:~/Desktop/IDL CORBA$ java ReverseClient -ORBInitialPort 1050 -ORBInitialHost localhost
Enter string=
hi this is corba. 
===============x=============x===========x==============================
----------------Assignment-3 (MPI)---------------------------------------------------------
1) open terminal in MPI folder
sanket@ubuntu:~/Desktop/MPI$ sudo apt-get install openmpi-bin libopenmpi-dev
sanket@ubuntu:~/Desktop/MPI$ mpicc MPI.c -o MPI
sanket@ubuntu:~/Desktop/MPI$ mpicc -I/path/to/mpi/include MPI.c -o MPI
sanket@ubuntu:~/Desktop/MPI$ ./MPI
===============x=============x===========x==============================
-----------------Assignment-4 (Berkeley) --------------------------------------------
1)open terminal in Berkley folder
sanket@ubuntu:~/Desktop/Berkeley$ javac *.java
sanket@ubuntu:~/Desktop/Berkeley$ java BerkeleyAlgorithm
===============x=============x=============x==========================
-----------------Assignment-5 (Token ring) -------------------------------------------
1)open terminal in Token folder
sanket@ubuntu:~/Desktop/token$ javac *.java
sanket@ubuntu:~/Desktop/token$ java Tok
OUTPUT:
Enter the num of nodes:
4
0 1 2 3 0
Enter sender:
1
Enter receiver:
3
Enter Data:
10
Token passing: 0-> 1
Sender 1 sending data: 10
data 10 forwarded by 2
Receiver 3 received data: 10
============x==============x===============x=================
-----------------Assignment-6 (Bully and ring) ------------------------------------
1)open terminal in ‘Bully and ring’ folder
sanket@ubuntu:~/Desktop/Bully and ring$ javac Bully.java 
sanket@ubuntu:~/Desktop/Bully and ring$ java Bully
============x==============x===============x=================
-------------------Assignment-1,2,3 (video link) --------------------------------------------------------
https://youtube.com/playlist?list=PLZoBm3Bjtn4nqlp6B_xWU8GVN1pr2gXDa
-------------------Assignment-7 (web service)-------------------------------------------
https://www.youtube.com/watch?v=XA3N6LmCMeo&ab_channel=KetulPatel
