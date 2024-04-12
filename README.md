# InterISP-Connect
InterISP Connect is an extensive initiative concentrating on the planning, design, setup, and documentation of a network layout involving multiple Internet Service Providers (ISPs) interconnected to furnish connectivity to a corporate clientele. Leveraging the capabilities of the GNS3 platform, this project encompasses tasks spanning network design, configuration, and documentation to guarantee seamless connectivity and robust network performance tailored to the enterprise requisites.
<img width="975" alt="screenshot" src="https://github.com/RicardoBeny/InterISP-Connect/assets/126669644/e9caca0d-293b-4776-ac39-fa3d9fdb909b">

Optimizing Network Performance:

- Addressing Optimization: Employing link-local addresses on all IPv6 interfaces to efficiently fulfill network requirements.
- IGP Domain Configuration for ISP Tier 1: Deploying OSPFv3 within a multi-area framework with ample routers supporting various area types.
- Traffic Routing from ISPs Tier 3: Steering traffic from Tier 3 ISPs through Tier 2A, with Tier 2B poised as a contingency in the event of Tier 2A link failure.
- Redundancy and Load Balancing: Assuring redundant and parallel link utilization between Tier 3 and Tier 2 to bolster network resilience.
- Preferred Links in Tier 1 Connections: Establishing preferred links in Tier 1 connections to either Tier 2, thereby optimizing network performance.
- BGP Implementation in ISP Tier 1: Employing BGP with minimized iBGP connections to efficiently manage router expansion, with emphasis placed on prioritizing confederations.
- Quality of Service (QoS) in Tier 2A: Implementing QoS in Tier 2A to prioritize network traffic and augment service quality.

Design Considerations for Corporate Client:

- Private Addressing Utilization: Employing private addressing for the corporate client's network.
- IPv4 Addressing Implementation: Configuring IPv4 addressing for the corporate client's network infrastructure.
- L3 VPN Connectivity via MPLS: Connecting company sites through L3 VPN over MPLS technology.
- Branch Connectivity Protocol Consideration: Evaluating identified protocols for branch connectivity with operator PE routers.
- Headquarters Router Internet Connectivity: Ensuring internet connectivity for internal equipment via the headquarters router.
- QoS Implementation for Effective Traffic Management: Implementing QoS for the corporate client's network to proficiently manage network traffic.
