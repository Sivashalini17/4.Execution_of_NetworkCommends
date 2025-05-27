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

![image](https://github.com/user-attachments/assets/d7d84cfa-1992-4926-9732-3923f0037edb)

![image](https://github.com/user-attachments/assets/1fb935f4-fa37-428d-8693-376d16ca125e)

![image](https://github.com/user-attachments/assets/97da94bc-555f-4f1b-b645-9350a89d738d)

![image](https://github.com/user-attachments/assets/5c9a7e2a-f128-4c0c-84f3-c7157fb771e8)

![image](https://github.com/user-attachments/assets/3c8e8516-3306-4945-bbd8-2bac5e52c4b9)

![image](https://github.com/user-attachments/assets/4d56f341-80c1-44bd-b597-fb248d58c5b9)

![image](https://github.com/user-attachments/assets/782720c9-89c7-4b63-aa6d-725c023680ff)

![image](https://github.com/user-attachments/assets/f6472f0e-de96-4249-9af2-04bbaa7ab2c3)

![image](https://github.com/user-attachments/assets/6f0d079d-35fe-4988-b5d0-d8c26320d881)

![image](https://github.com/user-attachments/assets/f3463468-488d-481e-8af9-2512555a220e)

## Result
Thus Execution of Network commands Performed 
