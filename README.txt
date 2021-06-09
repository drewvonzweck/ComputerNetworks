## Lab3
## Drew von Zweck
## 1576029
## dvonzwec@ucsc.edu

## lab3.pdf
## lab3controller.py ( skeleton --> finished code of customized controller )
## lab3.py ( a premade topology to use and control with the controller )

In this lab I was provided a template which I used to construct a POX controller. This program was written in Python and it instructs the switch to install the given rules. The first rule is to Flood all ICMP and IPV4 packets, the second is to flood all ARP packets, the third rule is to drop any other type of traffic. I used a few if and else statements to implement this algorithm. 

## some helpful resources
# http://csie.nqu.edu.tw/smallko/sdn/iperf_mininet.htm
# http://sdnhub.org/tutorials/pox/
# https://github.com/matt-welch/POX_Firewall/blob/master/Firewall.py

## comments
This lab was pretty difficult. It was hard to understand what was actually going on and when certain functions in lab3controller.py were being used. Going to lab section helped a lot and pointed me in the right direction.