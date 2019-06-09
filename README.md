# performance-load-socketio-react

//Node Client (Socket client)
Gives all the information about all CPU Metrics needed to show in react client 

//Socket Server
    1)Connects all the clients to Master Node and the Master Node
      Passes the work to workers(There By We can accomplish parllel programming in node).
    2)Connects to React Client(To show in UI), nodeClient(To get CPU info), mongo(know for previous connection establishment), redis(In memory Cache)

//React client
Shows all the CPU metrics as widget data    