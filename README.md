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
![Screenshot 2025-03-06 184324](https://github.com/user-attachments/assets/ecfb7e7d-f23d-44b2-bd23-8bdc25e44459)

## OUPUT - ARP
![Screenshot 2025-03-06 184339](https://github.com/user-attachments/assets/aec8f1e5-163e-4099-a155-daeecfd284fa)

## PROGRAM - RARP
![Screenshot 2025-03-06 184354](https://github.com/user-attachments/assets/44905e47-3081-4076-9b5f-0edfa518155a)

## OUPUT -RARP
![Screenshot 2025-03-06 184413](https://github.com/user-attachments/assets/54048c39-2300-48d7-8b68-d44e1be2402b)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
