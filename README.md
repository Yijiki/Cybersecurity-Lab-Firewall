# Cybersecurity Lab: Firewall

## Objective

This project focuses on building a multi-layered network security system to help prevent cyberattacks, guarantee constant uptime and control network traffic. The system leverages open-source tools like OPNsense, SquidProxy, Suricata and Zenarmor to assist with deep packet inspection, content filtering and real-time threat monitoring. A core part of the project was configuring high availability using CARP as well as setting up multi-WAN failover and load balancing. This project successfully created a secure and resilient network perimeter demonstrating practical skills in network hardening and security operations.

## Background and Motivation

In the age of 'assume breach' network security is no longer optional, it is critical for all organizations. The growing reliance on connected systems and remote access has dramatically increased the risk of cyberattacks. Attackers are leveraging increasingly sophisticated methods rendering basic security measures useless. To protect critical data organizations must deploy proactive security architectures.

The primary way that information flows is through an organization's network. However, managing and securing this network presents its own unique challenges for security and infrastructure teams. One significant problem is identifying and stopping threats in real-time. Without tools like Intrusion Detection/Prevention Systems (IDS/IPS) and Next-Generation Firewalls (NGFW), unauthorized or malicious traffic can easily slip through. Failing to detect and respond quickly to these threats can lead to security incidents and major disruptions.

Another significant problem is ensuring system reliability. Given that a core security component failing (like a firewall) can immediately shut down all operations, security infrastructure must be designed with redundancy protocols, failover systems and load balancing built in. The need for a network that is both resilient and secure against real-time threats forms the core motivation for this project.

## Problem Statements

Three limitations of traditional or improperly configured network security systems have been identified below:

- Single Point of Failure: Many network security systems rely on a single firewall introducing massive operational risk as routine events like firmware updates, scheduled maintenance or physical device failures can disrupt all network connectivity. This can lead to critical service downtime and interruption of business functions.

- Lack of Deep Threat Visibility: Many standard firewalls only filter traffic based on basic IP addresses and ports meaning they cannot inspect the actual content/application layer of the data. This allows sophisticated threats such as malware hidden in legitimate looking traffic or zero-day exploits to pass through undetected.

- Inconsistent Enforcement of Web Policies: Many network security systems find it difficult to enforce corporate security policies on web usage. This lack of control allows users to access dangerous or unwanted websites increasing the network's exposure to malware and other threats.

## Skills Learned

- Deployed and configured a firewall integrating key security components like an IDS/IPS, content filtering and NGFW features.

- Designed and built a high availability infrastructure utilizing CARP/pfSync for firewall clustering and multi-WAN failover/load balancing for consistent connectivity.

- Enhanced ability to define, implement and test complex firewall rule sets and NAT policies.

- Enhanced ability to analyse and interpret firewall traffic logs for signs of irregularity and Indicators of Compromise (IOCs).

- Practical skills in conducting controlled system failover exercises and managing traffic distribution to ensure system continuity under peak loads.

## Technologies Used

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar.
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar.
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar.
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar.
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar.

## Steps

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar. Nam sed fringilla diam. Vivamus consectetur mollis arcu eu dictum. Phasellus lobortis ornare libero sit amet bibendum. Sed egestas elit sed lacus semper auctor. Cras ac iaculis velit. Aliquam interdum ultrices enim, vel auctor leo vulputate ac. Sed feugiat erat non libero accumsan fermentum. Nulla vel nibh et magna lacinia tempus sit amet at mauris.

## Strategy/Approach

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar. Nam sed fringilla diam. Vivamus consectetur mollis arcu eu dictum. Phasellus lobortis ornare libero sit amet bibendum. Sed egestas elit sed lacus semper auctor. Cras ac iaculis velit. Aliquam interdum ultrices enim, vel auctor leo vulputate ac. Sed feugiat erat non libero accumsan fermentum. Nulla vel nibh et magna lacinia tempus sit amet at mauris.

## Achievements

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar. Nam sed fringilla diam. Vivamus consectetur mollis arcu eu dictum. Phasellus lobortis ornare libero sit amet bibendum. Sed egestas elit sed lacus semper auctor. Cras ac iaculis velit. Aliquam interdum ultrices enim, vel auctor leo vulputate ac. Sed feugiat erat non libero accumsan fermentum. Nulla vel nibh et magna lacinia tempus sit amet at mauris.

## Limitations

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum blandit aliquet mi nec pulvinar. Nam sed fringilla diam. Vivamus consectetur mollis arcu eu dictum. Phasellus lobortis ornare libero sit amet bibendum. Sed egestas elit sed lacus semper auctor. Cras ac iaculis velit. Aliquam interdum ultrices enim, vel auctor leo vulputate ac. Sed feugiat erat non libero accumsan fermentum. Nulla vel nibh et magna lacinia tempus sit amet at mauris.

