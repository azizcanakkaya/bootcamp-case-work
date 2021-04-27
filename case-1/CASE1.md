# CASE 1:

### 1.2:

- We will create a user and set a password for it (it can execute the same operations as a root user do)
sudo adduser azizcan.akkaya -p 123

- Now we switch our user
su azizcan.akkaya

![1.2](/img/1.2.png)

### 1.3:

- Changing directory
cd /opt

- Creating a directory calle "bootcamp"
sudo mkdir bootcamp

- Mount a disk to bootcamp directory
sudo mount /dev/sda1 /opt/bootcamp

![1.3](/img/1.3.png)

### 1.4:	

- Changing directory
cd /opt/bootcamp

- Creating a text file
sudo touch bootcamp.txt

![1.4.1](/img/1.4.1.png)

- Configuring inside the file
sudo nano bootcamp.txt

![1.4.2](/img/1.4.2.png)

### 1.5:
 
- Searching the file that we want inside the root directory, after that take the path you find and the file and copy it to the designated path
sudo find / -name bootcamp.txt -exec cp "{}" /opt/bootcamp \;

![1.5](/img/1.5.png)
