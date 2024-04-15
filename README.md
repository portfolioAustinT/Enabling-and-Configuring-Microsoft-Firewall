# Enabling and Configuring Microsoft Firewall

![Firewall](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/6bc473d9-93a4-4f9f-b7c0-09a71da979bc)


## Introduction


In this project, I enabled Microsoft Firewall, a host-based software firewall, to deter threat actors from exploiting the virtual machine. Multiple firewall profiles were implemented, including Domain Network, Private Network, and Public Network. I ensured that Windows Defender Firewall was enabled for each network profile. Following this, I configured the firewall to permit the application Firefox to communicate through it. By allowing Firefox to have access to both the private and public networks, users can utilize Firefox on the public network. Additionally, I configured a set of inbound rules, to determine which traffic may pass through the firewall. I allowed the Key Management Service to be enabled on the Domain and Private Network, however, access from the public network was blocked. 

## Enabling Firewall 

![Enabling Firewall](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/d23680c4-3038-42d2-8ca4-88ed0bbc3417)


## Allowing App through Firewall

![Allowed Apps](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/5c19410e-ce12-44e5-8206-769ffe567a71)


## Configuring Firewall Rules

![Inbound-Rules](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/85969699-0b17-4063-a1c0-2e27fbd9aa2f)

## Conclusion

To summarize, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Microsoft Sentinel was employed to trigger alerts and create incidents based on the ingested logs. Additionally, metrics were measured in the insecure environment before security controls were applied, and then again after implementing security measures. It is noteworthy that the number of security events and incidents were drastically reduced after the security controls were applied, demonstrating their effectiveness.

It is worth noting that if the resources within the network were heavily utilized by regular users, it is likely that more security events and alerts may have been generated within the 24-hour period following the implementation of the security controls.
