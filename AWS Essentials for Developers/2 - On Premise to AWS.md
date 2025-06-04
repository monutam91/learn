## On-premise to AWS

2. a. On-premise infrastructure
	- Projects, organizations were served from their own server
	- Buy the servers themselves and host, support it on your own
	- Or you could lease a server
	- Then virtual servers came, where virtualisation was used to split up a single server into several virtual servers
	- This lead to the increase of server leasing, by selling more and more virtualised server, which eventually lead to Amazon started capitalizing on this tech
2. b. Birth of the cloud: ES2 and S3
	- Owning infrastructure comes with a lot of responsibility: maintain, handle growth and spikes of traffic
	- EC2 - Elastic computer cloud
		* THe new stuff here was Auto-scaling, EC2 could scale automatically based on the load, then scale back down automatically to save costs
	- S3 - Simple Storage Service
		* Simple file storage, to access files, (Like Dropbox)
	- These two became the first IaaS (Infrastructure as a Service)
	- Autoscale helped to get greater uptimes and lower costs
	- With EC2, the shared responsibility model was implemented. Amazon took care of the hardware, but consumer is still responsible for the software running on the devices
	- With IaaS your responsibilities
		* Maintain the OS on it
		* Make sure its security
		* Guard against attacks like SQL injections
2. c. Where in the world are your AWS services?
	- Data centers are built in groups and connected to eahc other
	- You can select availability zones
	- You can select MultiAz (to clone your data in several zones)
	- TODO: Check out the course AWS for Developers: ECS and Multi-Regional Load Balancing
	- Not all regions offer the exact same services
2. d. Local Zones
	- Extensions of AWS regions, to get even closer to your users
		* To shave off some additional ms, for response time intense apps, like streaming live video, or games
