# Site-Prone-to-attack
This project is currently in work. 

**Description:**


It is a machine learning model that is intended to predict whether a site is prone to a perticular type of attack or not with high accuracy.
Make sure your dataset and jupyter fule is in same folder.

-Dataset Used to train model-UNSW-NB15 
link-https://cloudstor.aarnet.edu.au/plus/index.php/s/2DhnLGDdEECo4ys?path=%2FUNSW-NB15%20-%20CSV%20Files%2Fa%20part%20of%20training%20and%20testing%20set


Details require for prediction:

Source IP address


Source port number


Destination IP address


Destination port number


Transaction protocol


Indicates to the state and its dependent protocol, e.g. ACC, CLO, CON, ECO, ECR, FIN, INT, MAS, PAR, REQ, RST, TST, TXD, URH, URN, and (-) (if not used state)


Record total duration


Source to destination transaction bytes 


Destination to source transaction bytes


Source to destination time to live value 


Destination to source time to live value

Source packets retransmitted or dropped 


Destination packets retransmitted or dropped

http, ftp, smtp, ssh, dns, ftp-data ,irc  and (-) if not much used service

Source bits per second

Destination bits per second


Source to destination packet count 


Destination to source packet count


Source TCP window advertisement value


Destination TCP window advertisement value


Source TCP base sequence number


Destination TCP base sequence number


Mean of the ?ow packet size transmitted by the src 


Mean of the ?ow packet size transmitted by the dst 


Represents the pipelined depth into the connection of http request/response transaction


Actual uncompressed content size of the data transferred from the server’s http service.


Source jitter (mSec)


Destination jitter (mSec)

record start time


record last time


Source interpacket arrival time (mSec)


Destination interpacket arrival time (mSec)


TCP connection setup round-trip time, the sum of ’synack’ and ’ackdat’.


TCP connection setup time, the time between the SYN and the SYN_ACK packets.


TCP connection setup time, the time between the SYN_ACK and the ACK packets.


If source (1) and destination (3)IP addresses equal and port numbers (2)(4)  equal then, this variable takes value 1 else 0


No. for each state (6) according to specific range of values for source/destination time to live (10) (11).


No. of flows that has methods such as Get and Post in http service.


If the ftp session is accessed by user and password then 1 else 0. 


No of flows that has a command in ftp session.

No. of connections that contain the same service (14) and source address (1) in 100 connections according to the last time (26).


No. of connections that contain the same service (14) and destination address (3) in 100 connections according to the last time (26).


No. of connections of the same destination address (3) in 100 connections according to the last time (26).


No. of connections of the same source address (1) in 100 connections according to the last time (26).


No of connections of the same source address (1) and the destination port (4) in 100 connections according to the last time (26).


No of connections of the same destination address (3) and the source port (2) in 100 connections according to the last time (26).


No of connections of the same source (1) and the destination (3) address in in 100 connections according to the last time (26).

The name of each attack category. In this data set , nine categories e.g. Fuzzers, Analysis, Backdoors, DoS Exploits, Generic, Reconnaissance, Shellcode and Worms


Total **48** details is required 
