### Future Network Engineer

I belive to all network engineers should have all below listed basic skills considering advance technilogy changes in networking word

## Network fundamentals
You didn’t think I would forget about this one, did you? Even in the future, you are a network engineer so that means you need to know networking. You can’t automate what you don’t know, so don’t try to bypass the network fundamentals like switching, routing, TCP/IP, ARP, DHCP, DNS, IPSec, etc. Trust me, even in the public cloud you will have to know these things to build a network.

## VXLAN and EVPN
You have probably heard of overlays. Virtual eXtensible LAN (VXLAN) is an overlay technology that can carry L2 frames over a routed network by tunneling the frames. It’s more scalable than VLANs and commonly used in datacenter networks. Ethernet VPN (EVPN) is a BGP-based control plane for L2 (bridging) and L3 (routing) for VPNs. Once again, EVPN is mainly a DC technology today but I believe that VXLAN + EVPN will be a combo used in the Campus in the future. It wouldn’t hurt to learn the basics of it.

## SDN
Software Defined Networking (SDN), is one of those terms that we struggle to define what it really is. When we talk about SDN we often talk about some form of controller, abstraction, automation, the ability to influence traffic flow, and often overlays are involved. Regardless of the definition, SDN is a topic worth looking into, especially if you are aspiring to something like CCIE. Software Defined Access (SDA), and Software Defined WAN (SD-WAN), are both topics on the CCIE Enterprise Infrastructure lab exam.

## Public cloud networking 
Almost every organization is in the cloud these days. Networking in the cloud may seem easy at first but as the environment grows, the requirements become more complicated, and as you try to connect your on-premises environment to cloud, it becomes evident that someone with networking knowledge should also setting up network connectivity in the cloud. Guess what, that’s you! Your networking skills will be of great use and there is no doubt that people with cloud skills will be in high demand in the future.

## Linux
Linux is everywhere these days, even in Windows! Many network operating systems are built on top of Linux. While the Linux part is often abstracted away, sometimes you get access to powerful tools if you get access to the underlying Linux OS. Linux is also very relevant if you are doing automation and is a skill that will certainly be sought after going forward.

## Markdown
Markdown is a lightweight markup language commonly used in documentation platforms and even supported when opening TAC cases with Cisco. It is also commonly used in Git-based platforms when creating documentation. Markdown allows you to for example write a word within asterisks, like **bold** to make it appear as bold text. Markdown is simple to learn, and I suggest you start using it, if you aren’t already.

## Git
You have probably already heard of Git or of platforms like GitHub. Git is a version control system that is widely used. One great use case for it, for us in networking, is to store your configuration files in Git so that they become version controlled. You by no means need to be an expert in Git but get comfortable cloning directories and learning enough Git to be able to commit files and work collaboratively with colleagues or others in group projects.

image source: https://developer.cisco.com/codeexchange/github/repo/ciscops/ansible-network-backup

## YAML
YAML, or YAML Ain’t Markup Language, is a human-readable data-serialization language. It is commonly used to create configuration files. From a networking perspective, I think we will see use cases where we document our topologies using YAML. You could for example create a network diagram based on information in YAML, that you then store in Git to make it version controlled. For example, Cisco Modeling Labs (CML) supports using YAML to create topologies. Saves you a lot of clicking, for sure!

## JSON
JSON, or JavaScript Object Notation, is a lightweight data-interchange format that is easy for humans to read and write, and for machines to parse and generate. When you start working with Application Programming Interfaces (APIs), you will notice that most often you will get a response back that is JSON-formatted. For example, you could query your DNA Center appliance using the API and you would get a response in JSON. You could then analyze that data and find the information you are looking for.

## Python
I said you didn’t have to be a programmer but still I listed Python? I don’t believe you have to be an expert coder to be relevant in networking but knowing the basics of Python is helpful to automate mundane tasks. I recently wanted to test connectivity between all interfaces in a switch, residing in different VRFs, resulting in around 400 lines of ping commands. You can imagine that it would have taken probably half a day to do this manually. Instead, I was able to leverage Python to generate these lines for me and got it done in around 15 minutes. Once you start getting the hang of Python, I think you’ll find that it’s fun as well.

## Ansible
Ansible is an open-source tool used for software provisioning, configuration management and application deployment. It has become a well-known tool in the networking industry as it’s one of the few tools that don’t require an agent on the device it is managing. Ansible is often used to collect information from the network or to configure devices. Ansible is written in Python and uses YAML for its playbooks. Knowing a little Python can help you extend the functionality of Ansible.