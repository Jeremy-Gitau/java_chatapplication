# java_chatapplication
# CHAT SYSTEM
Once you run the programs a server is created at localhost 127.0.1/1201/ by the server machine (server.java file). The server listens to the client for any requests.
In the client.java file created we declare a variable in the button function that receives the message from the text field and stores it in the variable. Once the button is clicked, the function is invoked and the message is stored.  The message is trimmed using the trim function and sent to the server. Inside the client.java file a java.net socket is imported and an object is instantiated and the local host is declared and stored in a variable. This allows the client to connect with the server and communicate, the client sends a request to connect to the server and once the server accepts the request, the message is sent and received by the server machine. The server having the server socket 1201 accepts the request from the client and a message is displayed at the text area, thus a rout/path is created between the server and the client that enables direct communication. Now when the server wants to send a reply, it also does the same function as the client machine to send a message. A message is written and stored in a variable, once the button is clicked a function is invoked and a reply is sent to the client machine.
 


