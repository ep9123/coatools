# coatools
Certified OpenStack Administrator Exam Practice tools

Create a new virtualbox machine 
Use default NAT network
Under Advanced Networking setup port forwarding for http and ssh
Example:
http TCP  127.0.0.1 8080  10.0.2.15  80
ssh  TCP  127.0.0.1 2222  10.0.2.15  22

this will allow ssh and http access to the vm from your laptop

System settings  4 cpus  and 8Gb or more of memory (depending on how much you have)

build from ubuntu-server-16.04.3 image

ubuntu.sh has settup for proxies if working in office or over vpn

stackit.newton builds a devstack based on newton distribution
stackit.ocata  builds a devstack based on ocata  distribution

after successfull build take a snapshot so you can come back to it if you screw something up

in fact take snapshots as you work to go back to different spots and redo tasks to get comfortable with them and do them in different ways

Save the image state instead of shutting down then you can resume and run headless 

