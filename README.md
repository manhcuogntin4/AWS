# AWS
ssh -i "file.pem" ubuntu@ec2-52-31-22-160.eu-west-1.compute.amazonaws.com : connect to AWS
scp -i "file.pem" file-to-copy ubuntu@ec2-52-31-22-160.eu-west-1.compute.amazonaws.com :~/folder-name : copy file to AWS
scp -i "file.pem" ubuntu@ec2-52-31-22-160.eu-west-1.compute.amazonaws.com :~/folder-name/filen-to-copy . : copy file to current directory
screen : to run on background
Ctrl A+D to run on background
Ctrl D to logout
screen -r to retreive screen
Some commands for working with AWS 


install Caffe:
https://github.com/BVLC/caffe/wiki/Ubuntu-16.04-or-15.10-Installation-Guide
