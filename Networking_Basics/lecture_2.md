## The internets delivery services
    - Internet is a packet switching network
            - Packets can take any route
            - What is a packet?
            - Circuit switching network
                - Every packet follows same route

---

## Circuit switching
    - dedicated resources, no sharing
        - circuit-like (garunteed) performance
    - circuit segment idle if not used by call (no sharing)

## Packet Switching vs. Circuit Switching
    - Packet Switching
        - Uses store and foward
            - entire packet must arrive at router before it can be transmitted on next link
            - queueing: this is succeptible to bottleneck bandwitdths (this leads to build up of packets at bottleneck)
        - This calls for a reliable transfer protocol (TCP)

## Two types of delivery services
    - Reliable transfer: retransmission and reordering
    - Unreliable transfer: no garuntee

## Access Networks
    - Wireless Access Networks (WLANs)
        - Wifi, router, ~100 feet
    - Wide-area cellular access networks
        - provided by mobile, cellular network
        - cell towers use this

## Why layer the internet?
    - explicit structure allows identification, relationship of system's pieces
    - modularization eases maitenance, updatinf of system

## Layered Internet protocol Stack
    1. Physical (wires)
    2. Data Link
        - MAC addresses
    3. Network
        - **routing**
        - IP
    4. Transport
        - TCP,UDP
    5. Application
        - HTTP,IMAP,SMTP,DNS

## Question
    - What kind of devices do not have an IP address?
        - Thoughts: things like printers, keyboards, mouses
