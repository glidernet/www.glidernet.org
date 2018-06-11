Website under construction. You can refer to [wiki.ogn.aero](http://wiki.ogn.aero) for the time being.

# Welcome to the OGN project!

The objective of the Open Glider Network is to create and maintain a unified tracking platform for gliders, drones and other aircraft. Focused on tracking aircraft equipped with FLARM and OGN trackers, OGN is also open for integrating of other data sources (e.g. PilotAware, SPOT, FANET (paragliders), Spidertracks, …)

The tracking data is freely available to anyone as long as they follow [OGN data usage rules](ogn-data-usage/).

![OGN Architecture](OGN_Arch.png)


Today FLARM is mainly utilized in gliders, however other small aircraft (planes, helicopters, deltas, para-gliders or even drones) are more and more often equipped with it, especially if operating in the areas intensively used by gliders, such as the Alps.
Contrary to FLARM, OGN proposes an open transmission protocol and has an ambition to influence (or better) impose a standard.

The OGN is a community project. It is based on software, hardware, receivers and other contributions from individuals and the open source community.

## The OGN network consists of:
* APRS linux based servers that receive and forward data. Data includes device location information, status of receivers and the status of the OGN APRS network.
* A device database (aircraft). Register your aircraft/drone with tracking device in the OGN device database here if you wish to influence the way how it's going to be visible in the system (anonymous vs recognized).
* OGN ground receivers, based at airfields, gliding clubs, summits of mountains or private houses of our community members. They listen and decode the location data of aircraft in their vicinity and send position reports via network to the APRS servers.
* Software for Linux that can be installed on a PC or small mini-board computers (such as the Raspberry Pi, Cubieboard2, Odroid U3, etc.). It drives a USB DVB-T radio receiver and listens for, decodes, sends the position reports and participates in the OGN network.
* Websites and applications that can use and display the data. The most obvious use is to track aircraft on a moving map in real time, another use would be search and rescue (SAR), automatic flight logs, etc.

## The OGN is growing and evolving.
It is a work in progress and there is still much work to be done. You can help by:
* Funding, installing and running a receiver at your gliding club, at your home or anywhere the OGN has a 'hole' in its coverage. The cost of receiver is probably less than two aerotows for most glider pilots.
* Contributing your time to update, expand and maintain this Wiki, or improve the applications that use/ display/ share the OGN data or write your own application for the community.
* joining and bringing new ideas of where and how OGN should evolve!
You can join us by subscribing to [our discussion group](https://groups.google.com/forum/#!forum/openglidernetwork).

Please refer to the About OGN section for more information.


