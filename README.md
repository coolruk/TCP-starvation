# TCP-starvation
This program is for generating and simulating TCP starvation attack

As TCP starvation attack is using the weakness of TCP protocol, it can exhaust the session limit of target machine efficiently.
After the initial 3 way handshake of TCP connection between attacker and destination, attacker send a request to the target and victim replies back to the attacker. 
At this stage, the attacker doesn’t reply back to the target and the victim has to wait for the packets from the attacker and send the same reply packet to the attacker again and again in a certain period of time. 
If the attacker generates this attacks quickly, the session limit of the target service can be used and full in a short time. 
This actions deter the victim’s specific service by not allowing other users to access.

Several advantages of TCp starvation
1.	Generating attack doesn’t need a huge network traffic volume.
2.	Doesn’t consume the other resources of victim. Target machine’s CPU, RAM, Network traffic and so on. 
3.	Only can target the certain service which is using TCP.
