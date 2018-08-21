ProjectSnow
===================================

The defining feature of an ad hoc network is its independence from the larger
“internet”. Ad hoc networks exist dynamically among a group of computers (often referred
to in this report as nodes) communicating wirelessly with each other. It is also dynamic in
the sense that new nodes can join and leave the network seamlessly without (in most cases)
affecting the larger network and is completely decentralized from a main server.

Introduction
------------

In this project we attempt to implement a routing protocol based on the Optimized
Link State Routing (OLSR) protocol. Full compliance to the standard is not the goal but
rather basic routing between intermediary nodes. Specifically, we aim to be able to
transmit Transmission Control (TC) messages throughout the network and properly
establish Multipoint Relays (MPRs) for the nodes.