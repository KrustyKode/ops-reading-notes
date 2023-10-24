# Mikes Readings

## Ops 102 Readings

### What is bash?

#### What is the primary function of a shell in a computer’s operating system?
  The primary function of the shell is to allow a human to interact with or *around* the kernel.

#### How does Bash locate and execute commands on a Linux or Unix system?
  When a user issues a command bash will attempt to locate and execute from **/usr/bin** or **/bin** by default. 
  Other directories can be specified either permanently or temporarily using the PATH variable.

#### How can you determine if your system is running a Bash shell?
  There are a few different ways that you could do this. 
  `echo $0` run in the shell will display the currently running process, if you have bash the shell will print out bash.
  Typing `echo $SHELL` will also print the current shell in use.

#### What makes Bash scripting powerful and why is it considered scriptable? 
  bash is a truly powerful tool. There are a laundry list of diverse functions that can be called using it.
  Different bash scripts can do everything from changing colors in your shell to executing malicious code.

  Bash is considered to be scriptable because anything that you can manually type into bash can also be automated.

#### Bash scripting allows for customization, automation, and efficiency. Discuss methods or practices from your previous work experience or cultural background that aim to achieve similar goals in daily tasks. 
  I love to automate things. There is a piece of monitoring equipment I use in my coral tanks that actual supports Python scripts. I have my lights, dosing pumps, circulation, and tests all scripted.
  
  
  



