
---
## Zscaler and Netskope
## Strengths:

- Zscaler's main strength is their <mark style="background: #FB8B24;">concise marketing strategy</mark> - all sales reps give exactly the same presentation. They convince customers that they are the only ones built for the cloud and are therefore best-placed to lead network and security transformation with ZTNA.


## What traps are set by the competition?

- Zscaler engages from the top-down: executives communicate their message at the C-Level within customers' organizations. The same message is then reinforced at every opportunity, telling customers that:

	- Firewalls are legacy technology, only proxies can properly secure web traffic.
	- Zero Trust Network Access must remove the user from the network, only a software-defined perimeter (SDP) like ZPA can do this.
	- Prisma Access is just a bunch of virtual firewalls, not cloud-native.


## Trap Counters: 

Clarifications:
  
- Firewall-based architectures are not limited to what types of app traffic and protocols they can inspect. Proxies are unable to perform security inspection of all internet application traffic, including UDP and SMB.

- Zero Trust is an end-to-end cybersecurity strategy that spans the infrastructure, not a product. 

- Zero Trust operates under the assumption that no user, endpoint/workload, application, or content can be trusted at any time, whether it has previously been checked or will be checked later on. Prisma Access relies on a default-deny, identity-based access policy to resources while also inspecting session traffic for threats and data loss. No SDPs can do inline sandboxing or DLP.

- Prisma Access is cloud-native, leveraging public cloud infrastructure with software-based scale. Constantly adding servers to colocation data centers is not cloud-native.

- Prisma SASE is comprehensive, including a unified approach to network security with Prisma Access, with fully integrated Prisma SD-WAN.


## Traps to set vs Zscaler

The best way to set traps to block Zscaler is to emphasize the areas they are weak in, by highlighting that:

- Our cloud architecture <mark style="background: #26F0F1;">scales automatically</mark> and is fully software-based. We do not require adding infrastructure to their data centers every month to attempt to meet customer demand.

- Prisma Access does not require any additional infrastructure to be added to your environment for connecting ZTNA users to your data centers and cloud VPCs.

- Prisma Access is the <mark style="background: #40F99B;">only</mark> ZTNA solution in the industry that can do <mark style="background: #40F99B;">inline inspection of private app traffic</mark> for threats and data loss. To the customer: Do you require sandboxing and/or DLP to be part of your ZTNA solution?

- Only non-proxy based architectures can inspect all internet traffic types and protocols for threats and data loss. Zscaler claims "all ports/protocols" with Z-Tunnel 2.0, but does not mention that only includes visibility of all ports and protocols. Only a handful of ports and protocols are actually inspected for security threats. <mark style="background: #EA2B1F;">Prisma Access inspects all internet traffic types, including Office 365 traffic.</mark>

- <mark style="background: #C2E812;">Prisma Access advertised locations and countries are available to all customers</mark>. Zscaler has several customer clouds and the "150" data centers is an aggregate count. Each customer gets a subset in the range of 50-75 data centers and less than 30 countries. Some countries rely on low throughput connections (e.g. India) for accessing the Zscaler cloud.

---

# Cisco

## Strengths:

- market what they call "flexible, fast, and effective cloud-delivered security."

- They are a long time SD-WAN player, with offerings that cover the whole range of SASE underpinning technologies


## Their Traps:

- private tests, using AVTest, to convince customers of the efficacy of their SASE offering.

- They claim that Palo Alto Networks is limited to delivering security, not networking, whereas Cisco can handle a customer's entire infrastructure.


## Trap Responses:

- Customers are often unaware that AVTest is sponsored by Cisco, and does not disclose the methodology used or let third parties configure products for tests. In a nutshell - the results of the test cannot be trusted.

- going a step deeper reveals the hundreds of unintegrated, disjointed products that they offer to make this claim - this should give customers pause for thought.

- The best solution is a unified platform approach to SASE network security capabilities for ZTNA, Cloud SWG, CASB and FWaaS, as evidenced by consistent security posture, single access policy and management interface.


## Traps to set vs Cisco:

#### Question:

- A true worldwide architecture that sufficiently supports all network infrastructures.

- An actual SASE infrastructure, or just pieced together products without proper integration.

#### Highlight:

- Our Next Gen SD-WAN - Layer 7 based metrics and pathing decisions are beyond anything the Cisco SD-WAN solution provides.

- Our automation with CloudBlades integrations and AI-OPs highlights how we are looking to help customers improve their business, not just maintain a status quo.


Finally, ask your customer how soon they would like to be able to have their SASE deployment 100% completed. We have multiple customer white papers that highlight how they were able to deploy to hundreds, or even thousands of stores in months. Can Cisco say the same?


---

# Fortinet


## Strengths:

- Fortinet convinces customers that they have a mature, strong SASE infrastructure, which is great for speed and SD-Branch.


## Traps:\

- Fortinet is all about lower costs and 'good enough' security efficacy. They often market information that is early release, or not currently available publicly. 

- They say they do everything PANW does, but faster and cheaper, with more networking capabilities (SD-Branch, Wifi, switching, etc).


## Trap Responses:

- Fortinet's supposed ability to do everything PANW can do does not check out on closer examination of, for example, the way they implement IoT, or DNS. Their focus on networking hardware shows their vision is not focused on security, such as stopping emerging threats like DNS tunneling and Zero-Day threats.


## Traps to set:

- ask customers whether Fortinet disclosed the extent of their cloud infrastructure, and the regions they cover as part of their SASE offering.

	- The reality is that Fortinet currently have very little ability to deliver their SASE story from the cloud - on-premise appliances account for 99% of their focus and ability.




---

# SASE silver bullets


Once you've dealt with competitors' traps, you need to focus on the main strengths of Prisma Access and Prisma SD-WAN: your SASE 'silver bullets.' Let's take a look at what they are.


-  Wide Infrastructure 
	- We offer a wide breath of infrastructure in a true cloud environment with almost unlimited scale, network performance, and private backbone, providing an unbeatable SASE environment.

- Industry Leaders
	- We are the only vendor to be recognized across the industry as leaders in everything that makes SASE (Zero Trust, WAN Edge, NGFW and ZTNA). We're also the only vendor that can provide full Next Generation layer 7 functionality across the entire SASE service chain.

- Machine Learning (ML)
	- The use of Machine Learning in all parts of the infrastructure for Prisma Access gives us the ability to learn from the ongoing threats and to block unknown threats before they have an impact to the environment.

- Zero Day
	- For security-first customers, no SASE solution offers better protection against Zero-Day or unknown threats than Prisma SASE. WildFire has over 30K more customers (43K) than FireEye (10K) and Zscaler Cloud Sandbox (3K) combined. From unknown threat received by WildFire to customer protection is usually less than 1 minute, a true "cloud effect". Zscaler advanced sandbox samples have been known to take hours before protecting their customers.


---

# Objection Handling

You know Palo Alto Networks' SASE offering is the best solution in the market, so it's understandable if you tighten up and become defensive when you hear an objection. To make your case properly, however, you need to keep your cool and ask questions to understand the objection, in order to get the objector over it and into your camp.


The **U-turn methodology**, outlined below, is a proven strategy to help you do this. It involves discussing the objections a customer raises, then 'taking them on U-turn'  back to your agenda. Let's take a look at how it works.

- ### Pull- don't Push

	- listen to what your customer has to say about them. Find out exactly what it is they are happy with.
	- Pull your customer in by asking open-ended questions to gain more information and insights into the situation and competitors' positioning and value.

- ### Take The Highroad\

	- highlight best practice in that area, preparing a benchmark to judge the competitor with.
	- It's important not to 'fight' about the information, but rather question and dig deeper

- ### Validate

	- Confirm that the customer will consider you if you show you can improve on the competitor's service.
	- Mirror their answer to ensure what you heard. 

- ### Transition to you agenda

	- Come back to your agenda, focusing on how PANW will help resolve their problems. 
	- "Are you looking at digital transformation? going to the cloud? How are you going to ensure you succeed?"

