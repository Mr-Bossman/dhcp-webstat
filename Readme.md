# dhcp-webstat

### Very simple site to list dhcp leases from an isc-dhcp-server

This program SSHs into the isc-dhcp-server using sshpass and runs
dhcp-lease-list and returns it to the conecting client if the client
provides valid credentials to the isc-dhcp-server. The front end will
then format and display the DHCP leases.


To start the website:

```bash
$ sudo apt install npm nodejs sshpass
$ git clone https://github.com/Mr-Bossman/dhcp-webstat.git
$ cd dhcp-webstat
$ npm i
$ node . 22 192.168.1.1
```
