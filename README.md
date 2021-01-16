# E-Learning System-1.0 Authentication-Bypass & RCE

This exploit is available on exploitDB but there were minor mistakes in the exploit that needed some python knowledge to fix and run the exploit.

However I Qucikly Fixed Those Issues and uploaded the updated and 100% Working version of the exploit.

Link to ExploitDB : https://www.exploit-db.com/exploits/49434

Step 1: run the exploit in python with this command: python3 exploit.py

Step 2: Input the URL of the vulnerable application: Example: http://10.10.10.23/caiwl/

Step 3: Input your LHOST where you want the reverse shell: Example: 10.9.192.23

Step 4: Input your LPORT that is the port where the reverse shell will spawn: Example: 4444

Step 5: Start a Netcat Listener on the port specified in Step 4 using this command: nc -lnvp 4444

Step 6: Hit enter on the  if your Netcat Listener is ready, and you will get a reverse shell as soon as you hit enter.

