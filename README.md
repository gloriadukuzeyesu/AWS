# AWS_Certified Cloud Practitioner


## RoadMap



![](AWS_screenShots/certificatesRoutes.png)



## The Exam has 4 Domains

1. 26 % **Domain** 1 1: Cloud concepts (13 questions)

2. 25% **Domain**2: Security and compliance ( 16 - 17 questions)

3. 33% **Domain** 3: Technology  (21- 22 questions)

4. 16% **Domain**4: Billing and pricing  (10 - 11 questions)

   

   **Passing 700/1000**

   

   Cloud service: a collection of servers in a network to store and manage data. 

   

   ## AWS Evolution. 

   * Simple Queue Services (SQS)  launchedin 2004
   * Simple Storage Services (S3) launched in 2006
   * Elastic Compute cloud (EC2) launched in August 2006 

   

   ## Common Cloud Services

   * **Compute** ( like a virutal computer that runs all application and program and code)

   * **Networking** (virtual network definint internet connection or network isolations between services or outbound to the internet)

   * **Storage** ( virtual hard drive that can stores files)

   * **Databases** virtual databases or database for general purpose web application)

     AWS has over 200+ cloud services 

     

   ## Evolution of Computing

   * Dedicated
     * Dedicated machine for your services
     * You have to know the space you will need upfront
   * VMS : 
     * Run multiple virtual machine on one machine
     * Most common
   * Container
     * More flexible
     * Lots of work to maintain
     * Example :  Docker
   * Functions:
     * Managed by VMS runnning managed Containers
     * Serveless computer
     * pay for the time the code is running
     * COld Starts is  side effect

   

   ## Types of Cloud Computing 

   * SaaS
   * PaaS
   * IaaS 

   ![types of cloud computing](AWS_screenShots/Screenshot%202023-09-09%20at%203.12.35%20PM.png)



## Cloud Computing Deployment Models

* Public Cloud: Everything is build on the cloud service provider(CSP) 

* Private Cloud : Everything is built on company's datacenter also know as **OnPremise**. The cloud can be open stack

* Hybrid : Using both OnPremise and a Cloud Sevice provider(CSV). 

* Cross Cloud : Using multiple Service provide. AKA multi cloud 

  ​	![](AWS_screenShots/Screenshot%202023-09-09%20at%203.23.18%20PM.png)



## Innovation Waves

Kondratiev waves: are hypothesized cycle-like phenomena in the global world of economy. The phenomena is closely connected with Technology.

## Burning Platform

 Refers to when a company abandoms old technology for new technology with the uncertainity of success and can be motivated by fear that organization future survival hinges on its digital platform. Example: Switchich from On-Premises to cloud services. 



## Digital Transformation Checklist

[Checklist](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://d1.awsstatic.com/whitepapers/digital-transformation-checklist.pdf)

## Evolution of computing Power

Computing power is a throughput measured at which a computer can complete a computation task. 

* CPU 

* GPU

* Quantum computing. 

  

  ### AWS Service offerering 

  * CPU => Elastic Compute Cloid EC2
  * GPU = > AWS inferentiare (InF1)
  * Quantum computing => AWS Bracket. 



## Benefits of Cloud 

* Agility : Increase speed and agility 
* Pay as you go pricing
* Economy of scale: Benefits from massive economies of scale
* Global Reach
* Security
* Reliablity
* High Availability
* Scalability : Benefits from massive economies of scale
* Elasticity 

## Six Advantages to Cloud ( original description )

1. Trade fixed expense for variable expense
2. Benefit from massive economies of scale 
3. Stop guessing capacity 
4. Increase speed and agility 
5. Stop spending money running and maintaining data centers
6. Go global in minutes 

![Six Advantages to Cloud ](AWS_screenShots/Six%20Advantages%20to%20Cloud%20.png)

[Six Advantages to Cloud](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)



## The seven Advantages to cloud 

* Cost Effective

* Global 
* Secure
* Reliable
* Scalable
* Elastic : Automate
* Currrent

![the seven advangates](AWS_screenShots/the%20seven%20advangates.png)

## AWS Global Infrastructure

AWS global infrastructure is a global distributed **hardware** and **datacenter** that **are physically networked together** to act as one large resources for end customer.

### Region

A region is a geographical disticnct locations consiting of 	one or more availability zones. 	Every region is pyhysically isolated from independet of every other region in terms of location, power, water and supply. 

The first aws region to be created is in Nothern 	Virginia(US-East1)

Each region has **3 availabilty zones.**

AWS prices vary by region

### 4 Factors to consinder when choosing a region 

1. What regulatory compliance does the region meet?
2. What is the cost of AWS services in this region?
3. what AWS Services are available in this region?
4. What is the distance  or latency to my end users?

## Region vs Global Services

**Region**: AWS scopes. This detemine where the AWS sercices will be launched. 

**Global**: SOme AWS services operate across mutliple region an will be fixed to global. Example : Cloud front., Amazon S3, ...



## Availibity Zones (AZ)

Refers to physical location made up of one or more datacenters. 

A datacenter is a secured building that contains hundreds and thousands of computers. 

A region will generally contain **3 available zones.** 

It is common practbie to run workloads at least in 3 AZ to ensure services reamin available in case one or two datacenter fail (High availability). 

A subset is associated with availabity zine.

Alll traffic between Az is encrypted

Azs are within 60miles of each other. 



## Fault Tolerance

 A fault domain is a section of a network that is vurneravle to damage if a critical device or system fails. The purpose of a fault domain is that if a failure occurs it will not cascade outside that domain., limit the damage possible. 

What is a fault level?
a fault level is a collection of fault domains. 

* AWS region would be a fault level
* AZ would be fault domain. 



Each amazon region is designed to be completely isolated from the other amazon regions. This achieves the greates possible fault tolerance and stability. 



Each Az is isolated but Az within the region are connected through low latency links. 



### AWS Global NEtwork 

Represents interconnection between AWS global infrastructure. Common referred to as **"Back Bone of AWS"** 

### Point of Presence (PoP)

Pop is na intermediate location betwen an AWS region and the end user and this location could be datacenter or collection of Hardware. 

### Pop resources are:

* **Edge locations** : data centers that hold cached (copy) on the most popular files(images, videos, web). So that the delively to end users is short. 

* **Regional Edge Caches** : data centers that hold much larger caches of less popular files to reduce a full round trip and also to reduce the cost of transfer fee.

  

![pop](AWS_screenShots/pop.png)

## AWS Direct Connect

AWS Direct connection is a private/dedicated connection between your datacenter, office, co location and AWS. 

Direct Connect has two very fast network:

1. Lower BandWidth 50MBPs- 500MBps
2. Higher BandWidth 1GBps or 10 GBps

### **Advantage** of Direct connect

:+1:   Helps reduce network costs and increase bandwodth throughput (great for high traffic networks)

:+1:  Provides a more consistent network experience than a typical internet based connection. ( reliable and secure)

## Direct Connect location 

Direct connect locations **are trusted partnered datacenters** that you can establish a dedicated high speed, low latency connection from your on-premise to AWS.

## Local Zones

LOcal zones are datacenter located very close to a densely populated area to provide single millisecond low latency performance(eg. 7ms) fo that area. Exa: Los Angeles, California.

​	 :white_check_mark: The purpose of local zone is to support highly demanding applications sensitive to latency. 

Ex: 

 	1.  media and entertainment. 
 	2.  Ad -tech
 	3.  Machine leaning

## Wavelength zones. 

AWS wavelength zones allows for the **edge computng on 5G** **networks**. Application will have ultra low latency being as close as possible to users. 

How is done? => You create a subnet tied to a wavelength zone and then you can launch virtual machnines (VMs) to the edge of the targeted 5G networks.



## Data Residency

Phyisical or geographyical location of where an organization or cloud resources reside. 

**What is compliance boundary?** = > a regulatory compliance by the organization that describes where data resides. 

**What Data Sovereignty?** => legal authority tha can be asserted over data because it is pyhical location is within jurisdictional boundaries. 











