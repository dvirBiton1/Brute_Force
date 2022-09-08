Use just for cyber_ethical resons, no for hacking!
# Brute Force
## Attack & Mitigation

### Description:

Scripts that demonstrate the brute force attack.

The first script is an port scanning tool show you witch ports are open on a target.

The second script is an attack tool which at the end of its run produces a file with the passwords.

The third script is a mitigation tool, which detects brute force attacks. Based on reading logs.

### preinstalls:

$ pip3 install paramiko

$ pip3 install colorama

$ pip3 install pyfiglet

$ pip3 install scapy

### How to use:
First use the IP_MAC_Scanner to see witch victems are.
* open terminal where the code "IP_MAC_Scanner"
* command: python port_scanning.py

NOTE: You need to add your gateway at the code.


Secound use the port_sanning to see if the target port 22 is open:
* open terminal where the code "port_scanning"
* command: python port_scanning.py <ip> (ip target)

For the attack tool:
* open terminal where the code "bf_attack"(the word list need to in the same folder).
* command: python bf_attack.py <ip> (ip target) -u <uesr name> -P <worldList> (txt file with passwords parse by enter)
          
          example: python bf_attack.py 13.20.12.45 -u admin -P worldList

For the mitigation tool:
* open terminal where the code "bf_mitigation".
* command: python bf_mitigation.py

