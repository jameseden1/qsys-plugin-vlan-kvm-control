# VLAN KVM Control - Q-SYS Plugin

Use Q-SYS to control the VLANs of a Cisco Catalyst switch, allowing you to dynamically route KVM extenders.

## Overview
Some [cheaper KVM extenders](https://www.te-smart.com/120m-hdmi-kvm-many-to-many-over-ip-extender-w-ir) exist which let you extend your HDMI, keyboard and mouse over ethernet cables, but they lack in settings to control IP addresses, routing, etc

One technique to allow for the management of multiple KVM pairs on a single network, is to put each pair of KVM's in their own VLAN. 

This plugin allows you to connect a Q-SYS Core to a Cisco 3750 Switch, and control the VLAN assignments per-port, allowing you to dynamically change the KVM Transmitter that a KVM Receiver is connected to. 

# Setting up the switch
 - This plugin connects to your switch via Telnet. Please ensure you have your switch set up correctly for Telnet connections, using a username and password. You can verify by using Putty.
