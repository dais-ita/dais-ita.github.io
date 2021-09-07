---
layout: splash
permalink: /Resiliant_Cluster/
---

# Resilient Coalition Networks 

[Watch UK Overview Video](https://ibm.box.com/v/Overview-Cluster2-UK-Video)

[Watch US Overview Video](https://ibm.box.com/v/Overview-Cluster2-US-video)

To support distributed analytics tasks, coalitions require a robust tactical network infrastructure.  With connectivity likely to be Degraded, Intermittent and Latent (DIL), networks need to be agile to changing coalition situations, easy and rapid to configure and resilient to failures.  The network also needs to enable effective and flexible sharing of partners’ information and resources such as local services and data-stores, edge devices such as hand-held radios and sensors.  Policies defining the behaviour of the network need to be able to adapt autonomously as the tactical situation unfolds (partners, missions and adversary action).  Finally, the placement of data and services across the network needs to be optimised both for efficiency and contingency in case of network failure or fragmentation.

This cluster of Key Outcomes has therefore been subdivided as follows:

##	Control and Architecture of Software Defined Coalitions 
A novel network control architecture which enables management of multiple coalition enclaves, flexible resource sharing and rapid adaptation in the case of fragmentation:

*	[Enhancing Coalition Networking using Software Defined Coalitions – An Overview](/2a09/)  Extending Software Defined Networking to create a new concept achieving robustness and agility in multi-domain coalition networks.
*	[Control Plane Architecture of Software Defined Coalitions](/2a08/)  To facilitate controller discovery, network reconfiguration and recovery from fragmentation.
*	[Software Defined Coalitions Controller Synchronization](/2a07/)  Development of mechanisms and policies to optimise the rapid creation of slices of shared resource for specific coalition tasks.
*	[Robust Network and Learning Architectures for Software Defined Coalitions](/2a01/)  Network robustness through a hybrid SDC/MANET architecture which uses ML to predict fragmentations.
*	[Joint Reinforcement and Transfer Learning for Distributed Service Configuration in Fragmented Software Defined Coalitions](/2b01/)  Enhancing SDC robustness by using ML techniques to speed up the network’s recovery following reconnection of fragmented domains.
*	[Graph Attention Networks for Congestion and Mobility Prediction](/2a05/)  Techniques to avoid retraining Machine Learning models when network topologies change.
*	[Binarized Neural Network](/2a06/)  Using binary representations of model weights to allow ML models on mobile hand-held devices to make lightweight inferences even when disconnected from the domain controller.  The concept is extended for the training of the models using federated learning.
*	[Resource Sharing in Software Defined Coalitions to Support Coalition Missions](/1f05/)  A comparison of game-theoretic approaches for optimising resource sharing between coalition partners having different objectives.
*	[Game Theoretic Resource Allocation in a Coaliltion](/1a09/)  A short demonstration of the resource allocation technique developed in the previous KO.
*	[Online Resource Allocation Using Distributed Bidding Approaches](/1f04/)  A comparison of a variety of auction-style approaches for allocating edge tasks to a central server.

##	Policy based adaptive network management  
A policy based management system which can learn partner policies and adapt the behaviour of the infrastructure accordingly.

*	[Policy Generation for Edge Devices in Coalitions](/2c04/)  Allowing autonomous edge devices to learn how to behave after being introduced to a context with which they are not familiar.  The edge devices do this based on the behaviour of other devices in their local area.
*	[Advancing Artificial Intelligence with Neural-Symbolic Learning and its Application to Generative Policies in Distributed Coalition Operations](/1c02/)  Allowing systems to perform edge of network policy learning for a range of tactical applications such as the management of networks, logistics and sensors.
*	[Answer Set Grammar](/1c07/) Allowing systems to autonomously adapt their operating policies to maximise their effectiveness and minimise risk.

##	Rapid characterization of coalition network infrastructure  
Adaptive placement of services and data so that they are available at the right place and time;

*	[Topology Inference](/2a03/)  Supporting service placement through inference of the state of a target network across coalition boundaries without requiring direct control plane access.
*	[Service Placement](/2a04/)  Techniques to support agile placement of analytics services to edge devices as opposed to being hosted centrally.
*	[A Security-Constrained Reinforcement Learning Framework for Software Defined Networks](/2c05/)  Development of a RL framework which uses IDS data to optimise network metrics of interest such as throughput while at the same time developing policies to prevent malicious data propagating into the network.
