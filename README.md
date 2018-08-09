# warrant-canary
## This is the warrant canary log for [VPNArchy](https://vpnarchy.com). 
---
### What is a "warrant canary" ?
A "warrant canary" is a colloquial term for a regularly published statement that a service provider has not received legal process that it would be prohibited from saying it had received, such as a national security letter or a warrant. In this repository we post our monthly warrant canary and archives can be found here as well.

### What is the point?
It can be safely assumed that if we have not published our warrant canary at our regular monthly interval for a particular month we have most likely received a warrant. While the government can force us to keep our mouths shut about a particular warrant they cannot compel us to speak legally. This means we can legally post our warrant canary to keep transparency with our users.

### Verifying signatures
Here at VPNArchy we sign each canary with our respective GPG keys to help mitigate fraud. You can find our public keys within the ****keys*** directory within this repo. To verify our canary is legitimate as a unix user you can first save and import our public keys on your computer.

### Importing our public keys
***Example***
```
gpg --import ~/Desktop/magg0t.pub
```

### Verify canary with keys
***Example***
```
gpg --verify /Users/JohnDoe/Downloads/canary-06012018.magg0t.txt
```

## More to come!
