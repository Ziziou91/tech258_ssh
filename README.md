# SSH keys

## Format
```
    ssh-keygen -t rsa -b 4096 -C your_email@example.com 

```
where:
- Ssh-keygen -> Generate a ssh key 
- Rsa -> the type of encryption

 

 



ssh key generation bash command explained: ssh-keygen(1) - Linux manual page (man7.org) 


ssh-keygen -t rsa -b 4096 -C your_email@example.com 

 

Running this command generates a pair of keys, 1 public and 1 private 

 

We then need to put the public key in the github folder 

 

 

Use cat keyname 

 

Copy the terminal output (don’t bring in whitespace at the end!). And add under security in the deploy keys on github 

When adding make sure to allow write access. Not clicking this would not allow us to write to the repo. 

 

What it is AND why it’s important 
