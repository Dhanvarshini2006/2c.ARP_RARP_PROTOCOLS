# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![image](https://github.com/user-attachments/assets/48dd468b-b3c6-4fc9-8dab-b86133779a2e)

## OUPUT - ARP
![image](https://github.com/user-attachments/assets/526730f3-7766-43c5-891c-44621927c5c9)


## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/7617af71-da3a-4351-96f0-0b0931a0b617)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/97d4193f-3e13-4e57-9c4c-762f59fd52c2)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
