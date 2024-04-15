# Enabling and Configuring Microsoft Firewall

![Firewall](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/6bc473d9-93a4-4f9f-b7c0-09a71da979bc)


## Introduction


In this project, I enabled Microsoft Firewall, a host-based software firewall, to deter threat actors from exploiting the virtual machine. Multiple firewall profiles were implemented, including Domain Network, Private Network, and Public Network. I ensured that Windows Defender Firewall was enabled for each network profile. Following this, I configured the firewall to permit the application Firefox to communicate through it. By allowing Firefox to have access to the public network rather than just the private network, users can utilize Firefox on the public network. Additionally, I configured a set of inbound rules, to determine which traffic may pass through the firewall. I allowed the Key Management Service to be enabled on the Domain and Private Network, however, access from the public network was blocked. 

## Enabling Firewall 

![Enabling Firewall](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/d23680c4-3038-42d2-8ca4-88ed0bbc3417)


## Allowing App through Firewall

![Allowed Apps](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/5c19410e-ce12-44e5-8206-769ffe567a71)


## Configuring Firewall Rules

![Inbound-Rules](https://github.com/portfolioAustinT/Enabling-and-Configuring-Microsoft-Firewall/assets/147944956/85969699-0b17-4063-a1c0-2e27fbd9aa2f)

## Conclusion

To summarize, implementing a firewall on systems increases the security posture of organizations. By activating Microsoft Firewall and configuring multiple profiles, including Domain Network, Private Network, and Public Network, I achieved my goal to fortify the system against potential threats. Allowing specific applications such as FireFox to communicate through the Firewall while restricting unauthorized access through inbound rules demonstrates the importance of a firewall in safeguarding sensitive data and preventing unauthorized network intrusions.  
