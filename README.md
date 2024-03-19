[Main Page](https://github.com/davidj778/davidj778)

# Use the NIST Cybersecurity Framework to respond to a security incident

Scenario

Review the scenario below. Then complete the step-by-step instructions.
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.

To address this security event, the network security team implemented:
- A new firewall rule to limit the rate of incoming ICMP packets
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:
- Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
- Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
- Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process.

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.



<table>
  <tbody>
    <tr>
      <td>Summary:</td>
      <td>There was a recent DDOS attack that occurred which  compromised the network for 2 hours. This happened due to a misconfigured firewall which allowed a flood of ICMP packets to disrupt the network.</td>
    </tr>
    <tr>
      <td>Identify:</td>
      <td>The organizations network services were stopped due to a flood of ICMP packets. This was found when the network was shut down for 2 hours.
        Upon further investigation, the cybersecurity team found that the attacker sent the flood of ICMP packets through an unconfigured firewall.
      </td>
    </tr>
    <tr>
      <td>Protect:</td>
      <td>The team put in place a IDS/IPS system to filter certain ICMP traffic, depending on suspicious characteristics.</td>
    </tr>
    <tr>
      <td>Detect:</td>
      <td>In order to prevent this type of attack from happening again, the team implemented a network monitoring software which uses abnormal traffic pattern detection. To check for spoofed IP addresses from incoming ICMP traffic, the team configure the source IP address verification on the firewall.</td>
    </tr>
    <tr>
      <td>Respond:</td>
      <td>The incident management team should block all ICMP traffic and stop all none critical services offline.</td>
    </tr>
    <tr>
      <td>Recover:</td>
      <td>Restore critical network services. After this, non-critical network systems and services should be put back online.</td>
    </tr> 
  </tbody>
</table>
