# Networking Commands

### `ifconfig`
- **`ifconfig`** is similar to **`ipconfig`** on Windows. It provides information about the machine's:
  - **MAC address**
  - **IP address**
  - **Subnet mask**
  - **Broadcast IP**

### `iwconfig`
- **`iwconfig`** gives information about the **wireless adapter**.

### `ping`
- **`ping`** allows you to test communication between machines.
  - Syntax: `ping <IP address>`
  - You can specify the number of times to ping using: `ping <IP address> -c <number of pings>`
  - **`CTRL + C`** to stop the pinging process.
 
    ![image](https://github.com/user-attachments/assets/b24181f9-425c-4a2f-95f5-522c559602a0)


### `arp -a`
- **`arp -a`** is used to **associate IP addresses with MAC addresses**.

  ![image](https://github.com/user-attachments/assets/e3f784dc-3663-4af0-a817-11b0d4046ae7)


### `netstat -ano`
- **`netstat -ano`** shows **active connections** and the **open ports** on the machine.

### `route`
- **`route`** displays the **routing table** of the machine, showing where traffic is going. This is useful in attacks to identify multiple gateways.

  ![image](https://github.com/user-attachments/assets/72205296-1f94-49e6-b756-83f3e1c7db21)

