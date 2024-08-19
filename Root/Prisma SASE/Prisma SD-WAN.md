
This is the network portion of the [[Prisma SASE]] offering, including things like bandwidth, stability and overall connection quality. 


- A next generation SD-WAN solution, overcoming legacy SD-WAN solutions by using app defined intelligence to create SD-WAN policies and engineer network traffic. 

- The autonomous nature of Prisma SD-WAN uses ML for data science methodologies to eliminate the labor intensive work that previously was required to run a network. 

- This is a cloud delivered solution that can easily configure interconnections, establish network service levels and gather stats for analysis. 

- Prisma SD-WAN cloud management service provides a simplified wat to connect locations. 

- Policies are defined by the apps that pass the network which allows decisions for path selection and network optimization in real time. 

- Prisma SD-WANs instant-On (ION) appliances establish the SD-WAN fabric across data centers and branch offices. 

- The appliances connect underlying network transports and keep in constant communication with Prisma SD-WAN cloud service. 

- Prisma SD-WANs [[CloudBlades]] enable API-based connectivity between ION appliances and cloud-based infrastructure services. 

- CloudBlades provides a centralized approach to program PSW (Prisma SD-WAN) devices for the integration of application flows with best-of-breed cloud services without complexity. 

- PSW offers orgs tremendous value over the alternatives.

- [[SASE Clients]] have experienced the ability to increase their WAN bandwidth significantly by leveraging scalable internet connectivity. 

- Because such improvement, customers have witnessed dramatic reductions in the number of help desk tickers due to WAN issues. 

- They have also seen lower costs associated with WAN management through the elimination of proprietary hardware, expensive dedicated connectivity and additional systems. 

- PSW is part of a larger Palo Alto Networks approach to solve the challenges of hybrid workforces, cloud and digital initiatives and branch office transformation. 

- All of the above is what's known as [[Prisma SASE]].

- Prisma SASE combines [[Prisma Access]], [[Prisma SD-WAN]], and [[ADEM]] to provide customers best-of-breed security, autonomous networking and an enhanced user experience - all delivered from the cloud. 

---

# Prisma SD-WAN Details

- **Three Main Characteristics**
	- Application defined
	- Autonomous in Nature
	- Cloud Delivered 

- Prisma SD-WAN looks at the actual applications traversing the network. 

- If you can analyze which applications are more critical, you can provision and more easily support those applications. 

- Uses AI/ML for event correlation and automated problem remediation.

- Cloud native, less hassle and less costly.

- ION appliances are the backbone to how the SD-WAN is delivered to customers, it is meant to be a gateway to the SD-WAN connection.

- There are 3 components to how PSW works.
	- The Cloud Management portal
		- Policies Defined by apps
		- Intelligent path selection

	- Instant-ON ([[ION]]) Appliances
		- Connectivity for data centers/BO
		- Captures data for performance visibility

	- [[CloudBlades]]


### How does Prisma SD-WAN help? 

- The value proposition of Prisma SD-WAN is wide ranging but some examples include:
	- Increased network bandwidth
	- Decreased help desk tickets


----

## How does Prisma SD-WAN work?


- Traditional WAN architectures are composed of the **Control plane** and the **Data plane**. 

	- The Control plane exists to make networking routing decisions.
	- The Data plane exists to pass the traffic rapidly. 

- SD-WAN is made up of two components. 

	- SD-WAN devices are the Data plane
	- The Central controller is the control plane. 


The central controller is software based and usually based in the cloud, it is also where Policy decisions are made, traffic prioritization is decided and where SLAs (Service Level Agreements) are implemented. 


A service-level agreement (SLA) is an agreement between a service provider and a customer. Particular aspects of the service – quality, availability, responsibilities – are agreed between the service provider and said customer. 


The SD-WAN devices are physical or virtual by nature, and usually placed at an ORGs branch offices. The controller is the crucial part. It looks at the performance of the entire network and adjusts accordingly. 


--- 

# Simple Management Interface

-  Centralized Controls
- ZTP (Zero Touch Provisioning)
- Reports
- Alerts
- System Integration

# VPN/3rd Party Integration

- VPNs are a core func of SD-WANs
- IPSEC VPN integration
- Additions
	- Optimization
	- Orchestration
	- AI
	- Analytics
	- Cloud Integrations


# Summarizing Prisma SD-WAN

### First and foremost Prisma SD-WAN is autonomous.

- Control Plane
	- Cloud Management Portal; Responsible for:
		- configuration
		- monitoring
		- management

	- ION devices have an analytics mode:
		- Monitors network traffic
		- Forwards the network traffic to the Cloud Management Portal
		- The Portal then sets policy and SLA thresholds using ML


---



- Data Plane
	- Instant-On Network Appliances

		- The Devices capture Application level data including:
			- fingerprints
			- transaction time
			- reachability
			- response
			- mean opinion scores

		- Physical 
			- 
		- Virtual
			- ESXI
			- KVM
			- HyperV

	- Provides Network Metrics
		- loss
		- latency
		- jitter

The Application data and Network metrics are combined using Prisma SD-WAN in real time to make real time network routing decisions.

All this combines into intelligent path selections and continual optimization. 

Finally SD-WAN brings in [[CloudBlades]] as a scalable API platform to simplify programming integration with cloud services. 
