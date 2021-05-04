# Google Cloud at F1 Speed
## Section 1 : Virtual Machines in GCP
### Lesson 1 : Creating VM in GCP
### lesson 2 : Installing HTTP Webserver on GCE

sudo su
apt update 
apt install apache2
ls /var/www/html
echo "Hello World!"
echo "Hello World!" > /var/www/html/index.html
echo $(hostname)
echo $(hostname -i)
echo "Hello World from $(hostname)"
echo "Hello World from $(hostname) $(hostname -i)"
echo "Hello world from $(hostname) $(hostname -i)" > /var/www/html/index.html
sudo service apache2 start

### Lesson 3 : Exploring Compute Engine VM IP Adrdresses
### Lesson 4 : Managing Compute Engine VMs
### Lesson 5 : Simplifying Web Server setup with Compute Engine 
### Lesson 6 : Simplifying VM creation in GCP
#!/bin/bash
apt update 
apt -y install apache2
echo "Hello world from $(hostname) $(hostname -I)" > /var/www/h
### Lesson 7 : Reducing Launch Time with Custom Image
### Lesson 8 : Managing Costs for Compute Engine VMs
### Lesson 9 : Exploring Virtual Machines in GCP
### Lesson 10 : Managing VMs using Instance Group in GCP
### Lesson 11 : Creating Managed Instances Groups
### Lesson 12 : Playing with Managed Instances Group
### Lesson 13 : Load Balancing in GCP
### Lesson 14 : Creating a Load Balancer
### Lesson 15 : Exploring Load Balancer in GCP