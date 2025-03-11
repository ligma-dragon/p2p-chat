# ***p2p-chat***
*uses iroh library to establish a QUIC(udp connection)*

iroh is a library that helps establishing a QUIC-udp connection.Uses rust tokio as env.

Follow this to implement this by yourself:  
(First Clone the repo and go to the folder)
### 1. _To open a chat room_
Open a new terminal and type:
 1. ```cargo run open```
 2. You will get a ticket id
 3. this ticket id can be shared with someone who wants to join the chat room

### 2. _To join a chat room_
Open another terminal and type:  
 1.```cargo run join "<your ticket id>"```

You can set your nicknacme using the --name <NAME> flag
