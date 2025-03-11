# * **p2p-chat** *
*uses iroh library to establish a QUIC(udp connection)*

iroh is a library that helps establishing a QUIC-udp connection.Uses rust tokio as env.

Follow this to implement by yourself:

### 1. _ To open a chat room _
 1. ```cargo run open```
 2. You will get a ticket id
 3. this ticket id can be shared with someone who wants to join the chat room

### 2. _ To join a chat room _
 1.```cargo run join "<your ticket id>"```

You can set your nicknacme using the --name <NAME> flag
