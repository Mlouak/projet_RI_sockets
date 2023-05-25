# projet_RI_sockets
you can execute the project directly
med.c : is the file who contains all the functions of the project.
by running this commands in three separted terminals in linux
./server.exe<br>
./router.exe
./client.exe

But if you want to know how from what this come, this is how:
compilation:

1)client:
gcc -c client.c
gcc client.o med.o -o client.exe

2)router:
gcc -c router.c
gcc router.o med.o -o router.exe

3)server:
gcc -c server.c
gcc server.o med.o -o server.exe

the link of explanation ;
https://youtu.be/5hhO1fh7XtI
