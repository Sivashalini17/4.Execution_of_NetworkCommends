# 4.Execution_of_NetworkCommands

NAME : SIVA SHALINI.S
REG.NO : 212224240154

## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

PROGRAM :
SERVER :
```
import socket 
s=socket.socket() 
s.connect(('localhost',8000)) 
while True: 
ip=input("Enter the website you want to ping ") 
s.send(ip.encode()) 
print(s.recv(1024).decode())
```

CLIENT :
```
import socket 
s=socket.socket() 
s.connect(('localhost',8000)) 
while True: 
ip=input("Enter the website you want to ping ") 
s.send(ip.encode()) 
print(s.recv(1024).decode())
```

## Output
![WhatsApp Image 2025-05-02 at 22 51 31_b9f20198](https://github.com/user-attachments/assets/6d49ccbe-5ead-49ef-9c8a-e8950022fcb8)
CLIENT :
![image](https://github.com/user-attachments/assets/532d01e4-f4a3-4f6f-b29f-af600ec5ee58)
SERVER :
![image](https://github.com/user-attachments/assets/72223b3b-cb13-4c91-9435-16ae061f7272)

## Result
Thus Execution of Network commands Performed 
