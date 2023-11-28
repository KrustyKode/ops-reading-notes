# Mike's reading

## OPS 301 readings

### Network scanning with NMAP

#### What is a port? Describe it with an analogy that would help a family member understand.
    A port is a virtual location that allows network communication.
    It is similar to a dock in a large shipping port, different docks
    are designed to accomidate different boat traffic, the same is
    true with computer ports.

#### What does a port scanner send to a port to check the current status?
    A port scanner will send either a TCP or UDP packet that
    asks the specified port about its status.

#### When a port scanner sends a request to connect, what are the three possible responses? Describe them.
    The three possible responses are:
    
    Open, accepted: 
        The computer responds and asks if there is anything it can do for you.
    
    Closed, Not Listening: 
    The computer responds that 
    “This port is currently in use and unavailable at this time.”

    Filtered, dropped, blocked:
        The computer doesn’t even bother to respond.

#### What is the difference between TCP and UDP?
    UDP does not allow for error checking, but is faster then TCP
    TCP is preferable when the integrity of the data matters more
    then how fast it can be sent/recieved.

#### List and describe the ports used for the following:
    Telnet: port 23
    SSH: port 22
    DNS: port 53
    SMTP: port 587
    HTTP: port 80
    HTTPS: port 443
    RDP: port 3389
    Ping: ICMP 

