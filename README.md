User and Server

1. User --> Server

    *login / logoff
    *status

2. Server --> User

    *online / offline

3. User --> User

    * direct messages
    * broadcast messages / groupd messaging

Comands:

    login <user> <password>
    logoff

    msg <user> body...
    guest: "msg jim hello" <-- sent
    jim: "msg guest Hello World" <-- recv

    #topic <-- chatroom / group chat
    join #topic
    leave #topic
    send: msg #topic body...
    recv: msg #topic: <login> body ...
