# ReportAnalysis
summary: In summary, a multimedia company offering web design, graphic design, and social media marketing services experienced a Distributed Denial of Service (DDoS) attack that compromised their internal network. The attack involved a flood of ICMP pings through an unconfigured firewall, resulting in network services becoming unresponsive. The incident management team responded by blocking incoming ICMP packets, taking non-critical services offline, and restoring critical network services.

To address the security event and improve network security, the organization implemented several measures, including a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification on the firewall, network monitoring software to detect abnormal traffic patterns, and an IDS/IPS system to filter suspicious ICMP traffic.

Following the NIST Cybersecurity Framework, the cybersecurity analyst is tasked with creating a plan to enhance network security based on the incident. The plan includes identifying security risks through regular audits, implementing protective measures such as policies, procedures, training, and tools, enhancing detection capabilities through monitoring and analysis, creating a response plan to contain and neutralize incidents, and improving the recovery process for future incidents.
Identify:Type of Attack: Distributed Denial of Service (DDoS) attack
Systems Affected: Internal network services

During the DDoS attack, the company's network services were disrupted as a result of an overwhelming flood of ICMP packets. This attack caused a disruption in normal internal network traffic and prevented access to network resources. The incident management team responded by blocking incoming ICMP packets, taking non-critical network services offline, and restoring critical network services.

The attack was made possible due to a vulnerability in the organization's unconfigured firewall, which allowed the malicious actor to send a flood of ICMP pings into the network, leading to the DDoS attack.

Protect: To further protect the organization's assets, the following systems or procedures need to be updated or changed:

Firewall Configuration: Review and update firewall rules to limit the rate of incoming ICMP packets. This will help mitigate the impact of future DDoS attacks by imposing restrictions on the amount of ICMP traffic that can enter the network.

Source IP Address Verification: Implement source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. This will help prevent attackers from using forged IP addresses to bypass security measures and launch DDoS attacks.

Detect: The team has successfully introduced a set of enhanced authentication measures aimed at thwarting potential future attacks. These measures include the implementation of multi-factor authentication (MFA), where users are required to provide multiple forms of verification during login. Furthermore, login attempts will now be restricted to a maximum of three tries, thus limiting the potential for unauthorized access. Additionally, comprehensive training sessions have been conducted for all employees, emphasizing the importance of safeguarding their login credentials.

Respond: The intern's network account has been disabled by the team. We conducted training sessions for both interns and employees, focusing on safeguarding login credentials in the future. Furthermore, we notified upper management about this incident, and they will reach out to our customers via mail to notify them about the data breach. In compliance with local regulations, management will also be responsible for informing law enforcement and relevant organizations.

Recover:The team is set to retrieve the erased data by restoring the database using the most recent full backup from last night. We have duly notified our staff that any customer information entered or modified this morning would not be included in the backup. It will be necessary for them to re-enter such information into the database after the restoration process is completed using last night's backup.
