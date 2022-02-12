# Easy-rsa in Ubuntu

◻️ `apt install easy-rsa` ;

◻️ `cp -r /usr/share/easy-rsa/ /etc/` copy the "easy-rsa" folder for "/etc" ;

◻️ In `nano openssl-easyrsa.cnf` comment RANDFILE “#” ;

◻️ `cd /etc/easy-rsa/` ;

◻️ `./easyrsa` shows all commands that can be used ;

◻️ `./easyrsa init-pki` creates the pki folder, where it will contain the certificates when they are created ;

◻️ `./easyrsa build-ca` create "ca.crt" .
