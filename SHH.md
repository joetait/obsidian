# SSH
#programming #ssh #servers #raspberryPi #remoteAccess #computers

### Raspberry Pi access

Can access [[raspberry Pi]] via 
```
ssh pi@192.168.1.11 `
```
This uses the IP address, which can change. Need to look into [[DHCP]], which dynamically sets the IP address, and see how to edit this is I want a static one to make it easier to find.

In the meantime, I can use `arp -v` to view all IP addresses on the network to find the  IP address if needed.


## To look at
- [ ] What is the impact of having created [[fingerprint]] when setting up SSH connection