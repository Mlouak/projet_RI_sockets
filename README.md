# projet_RI_sockets
you can execute the project directly<br>
med.c : is the file who contains all the functions of the project.<br>
by running this commands in three separted terminals in linux<br>
./server.exe<br>
./router.exe<br>
./client.exe<br>

But if you want to know how from what this come, this is how:<br>
compilation:<br>

1)client:<br>
gcc -c client.c<br>
gcc client.o med.o -o client.exe<br>

2)router:<br>
gcc -c router.c<br>
gcc router.o med.o -o router.exe<br>

3)server:<br>
gcc -c server.c<br>
gcc server.o med.o -o server.exe<br>

the link of explanation ;
https://youtu.be/5hhO1fh7XtI
