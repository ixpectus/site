---
title: "arp"
date: 2020-05-31T15:25:35+03:00
tags: 
  - linux 
  - network
summary: "ARP - address resolution protocol. С его помощью можно найти устройства в локальной cети"

---

### ARP
* Address resolution protocol
* В локальной сети по ip с помощью arp как-то определяется mac адрес и обращение идёт по нему

#### Call example  
```
sudo arp-scan 192.168.4.0/24
[sudo] пароль для ixpectus:                        
Interface: enp3s0, datalink type: EN10MB (Ethernet)                              
Starting arp-scan 1.9 with 256 hosts (http://www.nta-monitor.com/tools/arp-scan/)
192.168.4.1     00:19:bb:c5:3e:02       Hewlett-Packard Company
192.168.4.2     20:cf:30:f1:fd:58       ASUSTek COMPUTER INC.    
192.168.4.6     00:30:48:62:5e:aa       Supermicro Computer, Inc. 
192.168.4.7     00:25:90:92:68:97       Super Micro Computer, Inc.
192.168.4.8     00:30:48:d4:1e:86       Supermicro Computer, Inc.
192.168.4.9     e8:40:f2:0c:2f:a5       PEGATRON CORPORATION     
192.168.4.10    6c:62:6d:aa:3b:2e       Micro-Star INT'L CO., LTD
192.168.4.11    52:54:00:94:1f:61       QEMU     
```

