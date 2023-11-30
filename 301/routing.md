# Mike's reading

## OPS 301 readings

### VirtualBox Network Settings Guide

#### Which network mode in VirtualBox can be used to 
#### emulate unplugging the Ethernet cable from the network?
    You can use the "Not Attached" option.

#### Which network mode would be best if you wanted to run a server 
#### on a VM that could be fully accessible from your physical local area network?
    You would use the "Bridged Adaptor" option.

#### What are the three options of promiscuous mode and what does each do?
    The three options are:
    
    Deny - Any traffic that is not intended to the virtual network adapter
     of the VM is hidden from the VM. This option is set by default.

    Allow VM's - All traffic is hidden from the VM network adapter except 
    the traffic transmitted to and from other VMs.

    Allow All - There are no restrictions in this mode. 
    A VM network adapter can see all incoming and outgoing traffic.

#### What is Port Forwarding?
    Port forwarding is the concept of intercepting/
    redirecting traffic from one IP and port to another.