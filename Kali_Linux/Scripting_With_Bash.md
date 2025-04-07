# Declaration:
`#!/bin/bash` is declaration for bash language just like `#include <iostream>` for C++.

## Code:

![image](https://github.com/user-attachments/assets/f85b0b18-4c34-43eb-8a75-3b93413ff8c1)


## Syntax for "for loop" in bash:
The syntax for a "for loop" in bash is `for -declaration in "number of times you want it to run"`. That's what `for ip in seq 1 245;` is doing, and `do` is there to execute the statements below. `done` at the end is the program terminator, and `$ip` sign is like a variable moving from 1 to 254. It will repeat itself until the value 254.



## Code:

![image](https://github.com/user-attachments/assets/90c43cbe-f1af-44b0-9644-aeada21b0c0c)

## Explanation:
$1 is basically argument one in line number 9 `./ipsweep.sh 192.168.0` where `./ipsweep.sh` is argument zero and `192.168.0` is argument 2. It's sort of like a variable, and we can use more arguments like this if we want.

**Note:** Do not add line number 9 `./ipsweep.sh 192.168.0` or it will run the script again.


## Code:

![image](https://github.com/user-attachments/assets/b8deaad7-7af2-4519-b5eb-6cea2d3efa50)

## Explanation:
Basically, the "if" statement is implying that if argument one is empty, then run the following outputs which we are doing by "echo". Else, run the commands after "else" if we put in argument one, which will be our IP address.

## Code:

![image](https://github.com/user-attachments/assets/41fceb1b-701e-4645-a533-07d696bf8f0f)


## Explanation:
This is a one-liner bash code. Here, "nmap" is used to scan all the ports for that specific IP, and "cat ips.txt" is giving the output of all the IPs we stored earlier from our `./ipsweep.sh` script. It's basically a one-line bash code that speeds up the whole process.
