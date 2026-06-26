# AWS Lab 01 - EC2 Instance Launch and SSH Access
Date: 25JUN26
Tags: AWS, EC2, SSH, Cloud, Networking

## What I did.
I set up an Amazon-linux EC2 instance to learn and familiarize myself with the concept and how to do it. I logged into my AWS account, found the EC2 Section, and followed the steps to:
1. Setup the instance
2. Let me log-in via SSH from my Laptop.

## What I Learned
I learned that EC2 instances are actually not all that different from my personal home lab set up. It all followed the same concepts, that I had basic understanding. I Thought it would be a whole new thing, and I imagin at scale it is, but just that one linux instance? Reminded me of SSHing into my home server, or the laptop I use to test out new security tools.

## What Went Wrong / What was Confusing
Just because it was familiar doesn't mean I didn't mess up. I learned the hardway that the .pem keys are a one download thing, and no copying the text from the downloaded .pem file to a created .pem file on another PC doesn't work...(I don't think, should test)
Also setting up the security aspect of the Instance was a bit different than what I am used to with ufw and such. I didn't mess with it too much but it is definatly something I need to learn more about.

## Commands Used
ssh -i key.pem ec2-user@[ip]
who
cat/etc/os-release
ipaddr
ps aux
uname -a


## What Is Next?
Next- add a security group rule, and expose a web server on port 80.
