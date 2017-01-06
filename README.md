##ECMP

ECMP is a traffic routing application for Fattree network, switching packets with static hash algorithm. It is suitable for fattree4 and fattree8, using OpenFlow 1.3.0. It can work without a SDN controller.


### Download File

Download files into ryu directory, for instance, 'ryu/ryu/app/ECMP' is OK.


### Start

The usage of ECMP is simple, just start up the network as below:

    $ sudo python ryu/ryu/app/ECMP/fattree4_ecmp.py

If the network has started up, test the correctness of it:

    mininet> pingall
    mininet> iperf

If you have any question, you can email me. Don't forget to STAR this repository!

Enjoy it!
