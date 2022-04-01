# CCNA-Fundamentals

## Network Devices

      1.  Repeator : Repeats the packets to all the ports (Layer1 device, Not mostly using these days)
      2.  **Hub** : **Not an Intelligence device**, It shares the packets to all the ports associated with it (**Layer1 device not mostly used**)
      3.  **Switch** : **It is an Intelligence device**, It shares the packets to the exact ports based on the **MAC Address**(**Layer2 device Mostly used**)
      4.  **Router** : **Used to connect one network with another network**, Deals with **IP Address**(**Layer 3 device mostly used**), Uses **Routing table for routing**
      5.  **FireWall** : It is a Hardware/Software device to control the traffic and denies the bad people, Protect us from Bad People
                     1. **Intrution Detection Service** :Warns when someone attacks (i.e small DOG warns when it see some unknown person)
                     2. **Intrution Protection Service** :It Blocks the attacks and warns (i.e big DOG blocks the intrution)
      6. **Wireless Line Controller(WLC)** :It is used to manage the Access Point's, used when you have many access point's
   
   
## OSI Model

      * 7. Application Layer    (5 to 7->Treated as a Application Layer in **TCP/IP Model**) 
      * 6. Presentation Layer
      * 5. Session Layer
      * 4. Transport Layer  (TCP/UDP)           (Segments)
      * 3. Network Layer    (Router)            (Packets)
      * 2. Data Link Layer  (Bridge/Switch)     (Frames)
      * 1. Physical Layer   (Hub)               (Bits)
      
      
## Port Numbers

      * Https : 80  * FTP : 21 * TFTP : 69 * Telnet : 23 * SSH : 22 * HTTPS : 443 * SMTP : 25
      
## Number Systems 
      * Binary (0 or 1) (Base 2)
      * Decimal (0 - 9) (Base 10)
      * Hexadecimal (0 - F) (Base 16)
      
## Ip Adddressing  
    (Layer 3 logical address assigned by administrator, used to indentify the device in a network, every device in the internet should have unique ip address)
    IPv4 is a layer 3 protocol. IPv4 is a connectionless protocol, TCP is a connection oriented protocol   Transmitter -syn->  <-syn-ack- -ack-> Receiver (3 way hand  shake)
   
    In IP protocol there is no built in session and no retransmission, It depends on higher layer protocol like TCP for retransmission.
     
    Example X.X.X.X ---> Here X is 1 Octet = 8 binary Bits/ 1 byte
   
## Class Classifications 
      * Class A  - * starts with 0 in binary * decimal 0 to 126 (Range --> 1.0.0.0 to 126.255.255.255) * 127 is a loopback address * 0 is default network (We can't use 127 and 0) * Eg 1.0.0.0 --> first octet (1)-->Networks remaining(0.0.0) --> Hosts 
      * Class B  - * starts with 10 in binary * decimal 128 to 191 (Range --> 128.0.0.0 to 191.255.255.255) * Eg 178.1.1.1 --> first 2 octat(178.1) -->networks remaining (1.1)-->hosts
      * Class C  - A, B, C all are Unicast traffic. It is replaced by CIDR   * starts with 110 in binary * decimal 192 to 223 (Range -->192.0.0.0 to 223.255.255.255) * Eg 198.1.1.1 --> first 3 octet(198.1.1) -->Networks remaining (.1) ---> hosts
      * Class D  - multicast traffic
      * Class E  - reserved for future
