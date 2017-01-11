##ECMP

ECMP is a traffic routing application for Fattree network, switching packets with static hash algorithm. It is implemented for fattree4 and fattree8 here, using OpenFlow 1.3.0. It can work without a SDN controller.


### Download

Download files into Ryu directory, for instance, 'ryu/ryu/app/ECMP' is OK.


### Start

The usage of ECMP is simple, just start up the network as below:

    $ sudo python ryu/ryu/app/ECMP/fattree4_ecmp.py

If the network has started up, test the correctness of it:

    mininet> pingall
    mininet> iperf


### Authors

Brought to you by Huang MaChi (Chongqing University of Posts and Telecommunications, Chongqing, China.) and Li Cheng (Beijing University of Posts and Telecommunications. www.muzixing.com).

If you have any question, email me. Don't forget to STAR this repository!

Enjoy it!
