# Enabling and Configuring Microsoft Firewall


## Introduction

In this project, I constructed a mini honeynet within Azure, collecting log data from various resources into a Log Analytics workspace. Microsoft Sentinel utilizes this data to construct attack maps, trigger alerts, and create incidents. I measured some security metrics in the insecure environment for 24 hours, applied some security controls to harden the environment, measured metrics for another 24 hours, and then shown the results below. The metrics include:

## Enabling Firewall 

![Enabling Firewall](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/4af1ae33-81a0-453c-b14d-5cc009c0ff59)


## Allowing App through Firewall

## Configuring Firewall Rules

## Conclusion

To summarize, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Microsoft Sentinel was employed to trigger alerts and create incidents based on the ingested logs. Additionally, metrics were measured in the insecure environment before security controls were applied, and then again after implementing security measures. It is noteworthy that the number of security events and incidents were drastically reduced after the security controls were applied, demonstrating their effectiveness.

It is worth noting that if the resources within the network were heavily utilized by regular users, it is likely that more security events and alerts may have been generated within the 24-hour period following the implementation of the security controls.
