## What does the protocol stack do
- Addressing and name resolution
- Encapsulation and Decapsulation
- Reliable Delivery
    - transport and link layer
- Routing : path selection and forwarding
    - network

## Application Layer
- DNS
    - Transates human readable names into IP addresses
    - Provides a mapping from hostname -> IP address

## Transport Layer
- Uses ports
- Reliable delivery via TCP (not UDP)

 # Transport Layer - addressing
     - Multiple proccesses running on a single host
    - Port numbers get data to the correct process on host
    - In TCP, connection identified by
        ` <Client IP, Client Port#, Server IP, Server Port#> `
    - Client port number os the application your running
    - In UDP, there is no connection, only destination info
        ` <Server IP, Server Port#> `

# Socket Programming
- Creating network applications involves:
    - creating sockets
    - binding sockets to ports
    - using them to send and receive data
