# Mike's reading

## OPS 401 readings

### Pass the Hash with Mimikatz

#### Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.
    Pass-the-hash
    Pass-the-ticket
    Overpass-the-hash (pass-the-key)
    Kerberoast golden tickets
    Kerberoast silver tickets
    Pass-the-cache

    Two of these techniques are:

    Pass-the-hash: It allows attackers to use an NTLM hash (a way Windows used to store password 
    data) to log into a target computer without needing to know the actual password, using the hash 
    string directly.

    Pass-the-ticket: It enables attackers to use a Kerberos ticket (a newer form of Windows password 
    data storage) to authenticate to another computer, effectively using someone else's credentials 
    to gain access.
#### What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz.
    Restricting admin privileges
    Disabling password-caching
    Turning off debug privileges
    Configuring additional Local Security Authority (LSA) protection

    Two of these mitigations are:

    Restricting admin privileges: By limiting administrator privileges only to those who really need 
    them, it reduces the number of targets for Mimikatz to exploit, as many of its techniques 
    require admin level access.

    Disabling password-caching: Mimikatz can extract cached password hashes; by setting the system 
    to cache zero passwords, there are no hashes for Mimikatz to steal, mitigating the risk of 
    attack.