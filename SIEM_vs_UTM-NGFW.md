SIEM and UTM-NGFW
---

When it comes to Unified Threat Management/Next-Generation Firewall (UTM/NGFW) alongside several Security Information and Event Management (SIEM) solutions, some professionals will choose to implement one over the other. The SC Labs team believe these technologies complement each other and should be a staple for all organizations.

The UTM/NGFW space has continued to evolve, packing more and more technology into multilayer threat prevention tools.

These appliances typically sit on the edge of a network and consolidate many features that used to be standalones into a single device to protect an organization.

While the SIEM space has a lot of the same players, we are seeing additional features and modules that can be added to networks to feed even more data to the SIEM solution to enhance the correlation of events and provide additional details in alerts.

While this isn’t the first time we’ve reviewed these products, the team really looked forward to these products. This month Matthew Hreben spent a lot of time testing these product and was assisted by Matthew McMurray.

The team did a good job of staging the products as well as obtaining solid data from our lab and then also leveraging some vendor supplied instances to assist with data collection.

We conducted a web session with each vendor to bring the team up-to-speed on their products and what we should expect.

While testing the UTM/NGFW devices we looked at a few key areas, including, but not limited to, the ability to operate under high network traffic, ease of use, UTM features and the level of logging. When testing the SIEM devices we focused on setup time, including how easy the documentation was to follow.

We considered various logging options such as the ease or difficulty of pointing the logs to the device, as well as whether they were network based versus an agent that must be installed on each system from which an organization might want to gather logs.

In addition, we looked for extra features in SIEMs, such as LDAP/RADIUS authentication integration and any MFA options.

The team tested a variety of hardware and software, physically installing both NGFW and SIEM hardware into the SC Labs testing environment, to platforms that we would install into our VM environment for testing.In addition to testing within the SC Labs environment, we also used vendor testing environments for side by side comparisons.

Whether testing an on premises SIEM or a cloud native-based SIEM such as JASK ASOC, we configured the products the same and pushed the same load of Syslogs and reporting.

We ran test scripts that would generate several results, which ranged from the creation of user accounts to brute force password-cracking techniques. In addition, the SC Labs team looked closely at just how easy it was to trace back the information as well as the response times under maximum load.

UTM and NGFW testing was setup in the SC Labs secure environment along with configuring polices and applying different kinds of security profiles.

Most devices had similar options such as URL filtering, DNS filtering, vulnerability scanning and SSL-VPN capability, so we tested the similar tools of each as well as some of the unique options they offered. FortiNet’s FortiSandbox can uncover attacks hidden in encrypted traffic.

Sophos’s SandStorm offers cloud-based sandboxing while Secucloud’s Secuscaler provides Global Cloud Intelligence as real time protection routing from multiple feeds.


PICK OF THE LITTER

FortiNet’s FortiGate’s product lineup has improved and grown every year and this year is no exception, as the FortiGate 601E clearly demonstrates. The 601E’s NGFW features and performance, paired with its attractive price point, makes this product an SC Labs Best Buy.

Netsurion’s EventTracker 9.1 continues to stand out, combining EDR and SIEM functionality, providing the ability to stop unknown malware and preventing lateral movement during an attack, earning our SC Labs Recommend product for this month’s round of testing.

SIEM and UTM-NGFW

This month, SC Labs reviewed a few Unified Threat Management/Next-Generation Firewall (UTM/NGFW) solutions alongside several Security Information and Event Management (SIEM) offerings. While these product families are in the same group review, they perform very different functions.

UTMs are built on the notion of combining a single device to manage threats and originally included VPNs, IPS/IDS, Webfilters, DLP and firewalls. As these solutions evolved, UTMs started slowly migrating into a single device combined with some firewall devices – pulling these into NGFWs. While UTM is far from dead, the devices have increasingly become interrelated with the next-generation firewall platforms.

SIEM solutions, too, have been around for years serving as the main information source for the threat hunters. These tools also aid in incident response. Most provide forensic level analysis of events in a centralized and secure log management tool.

In recent years SIEM solutions have added features, especially user and entity behavioral analytics (UEBA) and anti-malware raising the specter that more if more UTM-like features are included, the market the verge of a “next-generation” SIEM.


# Refs
1. https://www.scmagazine.com/home/reviews/sc-labs-siem-and-utm-ngfw/