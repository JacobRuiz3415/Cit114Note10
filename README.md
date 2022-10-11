# Cit114Note10
## Main Points
- Load balancing is the practice of balancing the workload between two or more computers.
- This reduces strain on the system and increases efficiency.
- Load balance work is like having a checkout line by dividing user requests with many servers.
- A load balancer is an application, hardware or software-based, that handles load balancing.
- A software-based load balance can run on a server, in a virtual machine, or in the cloud.
- A load balancer handles requests based on a sort algorithm
- There are two algorithms, static and dynamic.
- Static load balancers distribute workload without knowing the current state of the system.
- Static load balancers can be set up quickly but may suffer from efficiencies.
- On the other hand, dynamic load balance takes into account the current state of the system.
- This includes server health, availability, and workload. 
- There are several types of dynamic storing algorithms.
-This includes least connection, weighted least connection, resource-based, and geolocation-based load balancing.
- A load balancer is often used with web applications to handle web traffic
- They are also commonly used in large-localized networks.
- In order to work properly, the dynamic load balancers must monitor the current health of the server.
- This is through regular server checkups.
- If one completely fails, then start a failover state.
- This is where a load balance would diverge workload to other servers.
- IT monitoring determines the health and performance of your IT infrastructure. 
- Auto Scaling is a technique for allocating IT resources.
- This is done by automatically scaling computural resources to meet demand.
- In the cloud, cloud services scales based on a conditions such as traffic.
- An auto scaling group is a group of AWS instances for auto scaling.
- The size is the number of instance between a maximum and minimum number.
- Like load balancing, auto scaling can deduce stress on systems and increase performance.
- Elastic Load Balancing is a load balancing service in AWS.
- To respond to incoming traffic, your load balancer needs to have specified listeners.
- A listener is a process that checks for connection requests.
- Amazon CloudWatch monitor your AWS resources.
- Amazon EC Auto Scaling is the outo scaling service for ec2.
## Quotes
- “Business activity is highly correlated with IT infrastructure and network performance. IT monitoring that evaluates resource consumption and traffic behavior helps businesses determine the corresponding business activities. For example, user traffic and application downloads from specific network nodes and data centers suggests high popularity in that geographic location.”
- “The overall benefit of autoscaling is that it eliminates the need to respond manually in real-time to traffic spikes that merit new resources and instances by automatically changing the active number of servers.”
## New facts
- Scheduled autoscaling can be use to auto scale at certain time.
