Student: Yaoye LU

ID: 5188093



**Exercise 1: Understanding the Impact of Network Dynamics on Routing** 

Q1:

node 0 communicates with node 1;

node 1 communicates with node 4;

node 4 communicates with node 5;

node 2 communicates with node 3;

node 3 communicates with node 5;

The packets follow route 5.

It does not change over time.

Q2:

At time 1.0, the link between route 1 and route 4 is down, and at time 1.2 the link is up again. 

During the time of 1.0 to 1.2, there is  no communication between route1 and route 4 and route 5, but after time 1.2, it becomes same as before.

Q3:

Yes, additionally sending routing tables.

When the link bewteen route 1 and 4 broke, the network sends the packets from route1 to route 2 instead.

Q4:

The packets stop going to router 5 from router 1 via router 4, because the cost between router 1 and router 4 changed, which affects routing the forwaring path.

Q5:
 Route 2 also routed the path from route 1 to route 5.

The effect of the uncommented line is to set the route to plan muliple end-end-paths when routing.

**Exercise 2: Setting up NS2 simulation for measuring TCP throughput** 

Q1: Because flow tcp1 has to traverse more router than flow tcp2 does and it has a longer delay.

Q2: Because TCP connection starts with a slow start and increases the cwnd with receiving ACKs, and when there is data loss or triple duplicate ACKs, it will change to a congestion avoidance algorithm.

Q3: Because the amount of data that sender can reach is the minimum of rend and the cwnd.

**Exercise 3: Understanding IP Fragmentation** 

Q1:

2000-byte data size has caused fragmentation

frame 16

two fragments

Q2:

Yes, because the replied data size is also 3500 bytes.

Q3:

ID: 7a7b

Length: 1480,1480, 548

Flag: $0\times2000$, more fragments;  $0\times20b9$, more fragments;  $0\times0172$

Offset: 0, 185, 370

Q4:

No, because all fragments did not exceed the MTU.

Q5:

The entire datagram will be resent.





























