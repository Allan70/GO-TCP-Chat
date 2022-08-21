## Run the chat app

Enter the following command in the terminal

```
go build .
```

To build an exe file named `chat`

Next, enter the following command in the terminal to start the server on port `:8888. Or run it by executing the chat.exe file.`

```
./chat
```

You will have the following output.

```
2022/08/21 19:54:32 Started server on :8888
2022/08/21 20:45:56 new Client has connected: [::1]:30143   
```

### Running Telnet

Run telnet to connect to the server that was created. Telnet can be run to connect to the port `8888` with the command below.

```
telnet localhost 8888
```

# Commands

`/nick <name>` - get a name, otherwise user will stay anonymous.

`/join <name>` - join a room, if room doesn't exist, the new room will be created. User can be only in one room at a time.

`/rooms` - Shows a list of available rooms to join.

`/msg <msg> `- Broadcast message to everyone in a room.

`/quit` - Disconnects from the chat server.
