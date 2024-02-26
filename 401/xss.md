# Mike's reading

## OPS 401 readings

### Cloud Identity and Access Management (IAM) with AWS

#### Explain how a cross-site scripting attack works in non-technical terms.
     It's like slipping a fake note into a letter to a friend, tricking them into doing something. 
#### What are the three types of XSS attacks?
    Reflected XSS: The malicious script is reflected off the web server, such as in a search result
    or error message.
    
    Stored XSS: The malicious script is stored on the website itself and executed when users access
    that content.
    
    DOM-based XSS: The attack occurs within the user's browser, manipulating the website's original
    script to perform malicious actions.
#### If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?
    An attacker can steal user data, impersonate the user, redirect to harmful sites, or manipulate
    the website content, leading to potential harm or data loss for the user.
#### What are some security controls that can be implemented to prevent XSS attacks?
    Protecting against XSS involves validating and sanitizing user inputs, escaping outputs, and 
    implementing strict Content Security Policies to ensure that browsers only execute authorized 
    scripts.