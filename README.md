# SimpleChat
A chat application made with java and the swing framework.

#### To run this code:

1. Run the main method that is on the ServerMain.java file to start the server (a window with some text should appear). Don't forget to pass the path of the directory with the needed sound files to the server object, as well as the server port.
2. After, you can run the main on the ClientMain.java file, passing the IP or url and the port of the server as the Client object arguments. You can run multiple instances of the client.

I first made this project so I would understand how Sockets worked and how to use them with threads to make a working application. Later I wanted to find out how to send files through the socket, so the client asks the server to download 2 sound files, a startup sound and a notification sound. The location of the files is the only argument that the server object takes.
