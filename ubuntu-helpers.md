# Copy file by connecting ethernet cable across two linux devices

### Target:
1. hostname		    // ex: john
2. hostname -I 	  // copy ip 192.168.....
3. pwd			      // destination directory
3. sudo apt-get install openssh-client openssh-server
4. sudo ufw allow 22


### Source:
1. sudo apt-get install openssh-client openssh-server
2. sudo ufw allow 22
3. scp filename hostname@ip:destination

### Example:
scp sample.jpg john@192.168.9.102:/home/john/Downloads
