# ELECTRONET
The project is an innovative technological solution to the "last mile" problem for a multitude of spatially distributed sources (sensors) that generate a small amount of information at random times.

Previously manually controlled and operated devices are now being replaced by automatic ones, which are monitored utilizing control systems. The sharp increase in the number of such devices has created a new direction - the "Internet of Things". This equipment includes various metering devices, security, lighting appliances, "smart home" systems. Businesses around the world are gearing up to migrate to a new range of products tailored for remote data collection. But monitoring and controlling such devices requires reliable communication.

The communication problem has led to the emergence of various systems and technologies on the market aimed at collecting data and controlling such equipment: NB-IoT, LoRaWAN, and others. Unfortunately, the high cost of deploying and owning such systems does not allow them to scale quickly. Moreover, they, like all radio systems, do not have noise immunity to ensure reliable data delivery. More adequate solutions are required, using fewer resources, cheap and reliable at the same time.
The Electronet project meets all these requirements due to the optimal system elements placement architecture, the existing infrastructure of electrical networks, micropower radio channels, as well as innovative signal processing solutions.

The role of network nodes at the lower level is performed by cheap sensors for monitoring electricity consumption (instead of expensive electricity meters and other devices connected to the mains) equipped with micropower radio transmitting and receiving power network PLC modems. They receive data from self-powered devices (not connected to the mains) via a micropower and environmentally friendly local radio channel and are relayed by the node through the mains along with their own data. It provides simplicity and cost-effectiveness of implementation, reliability of communication, the possibility of a nearly endless build-up of nodes and elements of the system on the scale of one 3-phase power grid. A hub connected to the outside world via standard communication channels will serve as a node for input/output of control signals for the network and devices of the "Internet of things" inside the network.

The project uses innovative communication solutions based on the processing of wideband noise-like signals with a large base, code division multiplexing, and random access to the network. This allows you to solve the problem of high noise immunity in the presence of strong interference and ensure a minimum delay in the delivery of messages.

Our nG-PLC next-generation power grid communication technology, prototypes of channeling equipment, both as part of the "clean technology" transfer and including consulting support, are available today for municipal companies engaged in the innovations implementation in the PRC, as well for developers of communication solutions for electrical products manufacturers.

# My personal contribution to the project
## Full-Stack Development
I've developed the website [Regularus.ru](https://regularus.ru/) using Django Framework

### Features:
* Realtime detailed statistics represented in the convenient visual form of graphs and diagrams.
* Multi-level access to administrative features control
* **TCP Server** working with low-level technical services (data proccessing and remote control)
* **C++** electric meters HEX data translation libraries integration with **Python** (**ctypes**)
