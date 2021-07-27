# netconf-xml-messages
Netconf xml messages to be tested with Sysrepo

### Runnig the Sysrepo container
`docker run -d --name netopeer2 -p 830:830 -p 6513:6513 sysrepo/sysrepo-netopeer2:latest`

### Connecting to the container in SSH
`ssh netconf@localhost -p 830 -s netconf`
