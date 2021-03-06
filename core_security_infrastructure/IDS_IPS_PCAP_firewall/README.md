# Overview

This section will cover several similar technologies, what their functions are, and a few options to get started or mature implementation of these technologies. First, some definitions:
* IDS - Intrusion Detection System. IDS's are used to 'Detect' threats on the network, this can be acomplished via 'signatures' (known indicators of specific threats such as a particular sequence of packets or bytes), anomaly detection (new protocols suddenly leveraged for significant data transfer or to a large number of hosts), and other means. An IDS's function is to 'alert' or 'identify' threats but not to block or 'record' everything which happens. SecurityOnion, Bro (now 'Zeek'), and Suricata all have IDS capabilities.
* IPS - Intrusion Prevention System. An IPS is very similar to an IDS except for it includes the capability to 'block' traffic in addition to alerting on it. Suricata, Zeek, and others provide this prevention capability as well. One of the key reasons one runs an IDS instead of an IPS is due to potential disruption due to blocking false positivies.
* PCAP - Packet capture. Packet captures are recordings of network traffic, they are used to analyze what actually happened on in terms of communications between computers. They are the strongest form of network forensic data and are great for identifying network anomalies, troubleshooting issues, and understanding what is happening at the network level.
* NIDS/HIPS - These are the same as IDS/IPS except they are used to differentiate between 'network based' and 'host based'. This document will deal specifically with 'network based' technologies.
* Firewalls - Firewalls are network security devices which provide a series of capabilites which can including VPN gateways, routing and switching features, authentication, as well as IDS/IPS features. Firewalls are most commonly deployed on the perimeter which means that they would typically not see activity between internal systems - such as a workstation to a local fileserver.
* NSM - This stands for 'Network Security Monitoring' and broadly covers monitoring all aspects of networks to optimize alerting, reporting, and understanding of a network.

# Platforms

We'll cover several platforms in these guides, click below for resources.

* SecurityOnion
* Bro/Zeek
* Suricata
* pfSense

# Temporary Resource Reference
* Suricata - https://www.sealingtech.com/blog/adventures-in-suricata-part-1-low-cost-intrusion-detection-system/
* Suricata Home Setup - https://vdalabs.com/2018/06/18/lessons-for-the-enterprise-from-running-suricata-at-home/
* Suricata & pfSense - https://hurricanelabs.com/splunk-tutorials/your-all-in-one-guide-to-setting-up-pfsense-and-suricata-in-splunk/
* Security Onion Setup - https://sathisharthars.wordpress.com/2014/01/28/setting-up-security-onion-intrusion-detection-and-network-security-monitoring/
* pfSense Setup - https://www.itpro.com/security/firewalls/355328/how-to-build-your-own-firewall-with-pfsense
* Bro/Zeek Documentation - https://docs.zeek.org/en/master/
