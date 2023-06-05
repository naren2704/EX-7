# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
# DATE:19-04-2023
# AIM :
To write the python program for simulating Traceroute command

# ALGORITHM :
Start the program.
Get the frame size from the user.
To create the frame based on the user request.
To send frames to server from the client side.
If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
Stop the program
# PROGRAM :
from scapy.all import *

target = ["www.google.com"]
result, unans = traceroute(target, maxttl=32)
print(result, unans)
# OUTPUT :
![image](https://github.com/naren2704/EX-7/assets/118706984/aaac1e6d-4fa9-41cf-8de5-862bccc8d87e)


# RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.
