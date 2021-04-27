# devops

## CASE 1:

### 1.2:
 
sudo adduser azizcan.akkaya -p 123

su azizcan.akkaya

![1.2](/img/1.2.png)

### 1.3:

cd /opt

sudo mkdir bootcamp

sudo mount /dev/sda1 /opt/bootcamp

![1.3](/img/1.3.png)

### 1.4:	

cd /opt/bootcamp

sudo touch bootcamp.txt

![1.4.1](/img/1.4.1.png)

sudo nano bootcamp.txt

![1.4.2](/img/1.4.2.png)

### 1.5:
 
sudo find / -name bootcamp.txt -exec cp "{}" /opt/bootcamp \;

![1.5](/img/1.5.png)
