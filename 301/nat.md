# Mike's reading

## OPS 301 readings

### CIDR Block Notation Explained in 2 Minutes

#### What is the main purpose for implementing NAT on a network?
    NAT allows you to access the interent using one IP address,
    while still using private IP's inside the LAN.
#### At what layer of the OSI model does NAT happen?
    NAT occurs during level 3 of the OSI model,
    as that level handles addressing.
#### What happens to packets when NAT runs out of addresses in the pool of available IPs?
    If the NAT runs out of usable addresses then packets
    sent will be be dropped.
#### What disadvantage does using NAT pose for routers?
    Disadvantages of NAT include Translation results in switching path delays,
    certain applications will not function while NAT is enabled, and 
    complicates tunneling protocols such as IPsec. 


