## Setup:  
         / <--> Laptop     - Static IP,   192.168.1.1, subnet 255.255.255.0, DNS 0.0.0.0  
  Switch  
         \ <--> UWTC-REC3  - Static IP, 192.168.1.200, subnet 255.255.255.0  



## Communication via Telnet:
$ telnet  
    telnet> open 192.168.1.200 2000  
    <  Trying 192.168.1.200...  
    <  Connected to 192.168.1.200.  
    <  Escape character is '^]'.  
    <  
    >  ERDB002  
    <  2 47 230 23.8 C 25.0 C  
    >  EQNGALL  
    <  2 ABCDEFGH 0000000   1.0   

