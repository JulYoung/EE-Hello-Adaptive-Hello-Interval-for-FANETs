This repository has been created for experimenting the algorithm proposed in 
"Adaptive Hello Interval in FANET Routing Protocols for Green UAVs"

The algorithm has been implemented on the AODV and OLSR routing protocols.
You can obverse the algorithm in the following files:
/src/aodv/model/aodv-routing-protocol.cc
/src/aodv/model/aodv-routing-protocol.h
/src/olsr/model/olsr-routing-protocol.cc
/src/olsr/model/olsr-routing-protocol.h

Step 1: Clone this repo:
git clone https://github.com/imtiaztee/ns-3.27-adaptive-hello-for-fanet

Step 2: Configure and build the cloned repo:
./waf configure
./waf

Step 3: put your scenario in the scratch and run, 
        you can test the algorithm by implementing AODV or OLSR routing algorithms into your scenario.

********************************************************

Thanks.
Imtiaz Mahmud.

********************************************************
For any inquiry, please contact at imtiaz.tee@gmail.com.