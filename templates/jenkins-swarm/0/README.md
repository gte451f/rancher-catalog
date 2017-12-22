## Jenkins Swarm Plugin Clients
### Experimental


### Info:

This template is based off an Alpine distro with Docker installed. These clients will come up and imediately be available for running Jenkins jobs. 

### Requires

A working Jenkins Master server

### Usage

Jenkins User: If authentication is turned on, you will need to supply the username the swarm clients should login with.

Jenkins Password: If authentication is turned on, you will need to supply the password the swarm clients should use.

swarm executors: Number of build jobs to run on the client. The default is the number of CPUs.
