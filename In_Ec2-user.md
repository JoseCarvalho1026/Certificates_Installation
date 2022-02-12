# Easy-rsa in Ec2-user

◻️ `amazon-linux-extras install epel -y` ;

◻️ `yum install easy-rsa -y` ;

◻️ `cp -r /usr/share/easy-rsa/3/ /etc/` copy the "3" folder for "/etc" ;

◻️ `cd /etc/3/` ;

◻️ `./easyrsa` shows all commands that can be used ;

◻️ `./easyrsa init-pki` creates the pki folder, where it will contain the certificates when they are created ;

◻️ `./easyrsa build-ca` create "ca.crt" .


