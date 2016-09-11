# JustKidding
RMI Server Client walkthrough for beginners
In order to run an RMI project you will need the bellow

1. In order to run the rmi server and create the stub class for the server .
  You can do it in several ways i prefer by cmd(comand line)
  You will need to go to right click on you PC and click Properties
  then choose Advance system settings
  then in Advanced you will need to press the button says Environment Variables
  On System variables find the path value.
  and replace the path value whith your java path .(We do this in order to be able to run java commands directly from cmd)
  Important!!!! create backup the old paths value because without it you cant run simple cmd commands such as ipconfig.
2. Now you are ready to compile build and run an rmi project through cmd with the wright commands.
3.Compile comand for all java files is javac you will need first to go to your projects path copy it and in cmd using cd comand
  and your projects path (like:: cd C/.....) enter the folder and javac the servers class (like:: javac RMIServer.java)
4.Now we need to open an rmi registry like this::      start rmiregistry
5.Then you need to create the stub class which is responsible for the communications in server (like:: rmic RMIServer)
6. now you are ready to run the programm from your IDE run the server first and then the client 

-----------------------------Simple RMI instructions for running a RMI project through your cmd---------------------------
