# **Static Routing for Internet Access**  

## **Overview**  
This project demonstrates **Static Routing** in Cisco Packet Tracer, ensuring that multiple branch offices can access the internet. The network is designed with **redundancy**, where Airtel is the **primary internet path**, and JIO acts as a **backup in case Airtel fails**.  

## **Network Topology**  
The network consists of:  
- **Four branch routers** (Branch A, B, C, D)  
- **One core switch**  
- **Two ISPs (Airtel & JIO)**  
- **Multiple PCs in different subnets**  
- **Static routes for internet access and redundancy**  

## **Objectives**  
1. Assign IP addresses to all devices based on a predefined IP pool.  
2. Ensure all users from branch offices can access the internet.  
3. Configure static routing such that:  
   - **Airtel is the primary internet route**.  
   - **If Airtel fails, traffic is routed via JIO**.  

## **Configuration Details**  
- **Static routes** are configured on all routers to ensure proper packet forwarding.  
- **Failover mechanism** using manually assigned route priorities.  
- **Multiple subnet configurations** for different branch locations.  

## **How to Use This Packet Tracer File?**  
1. Open the `.pkt` file in **Cisco Packet Tracer**.  
2. Verify the IP assignments on each device.  
3. Test connectivity using the **ping** command from branch PCs to the internet.  
4. Simulate failure by shutting down the **Airtel link** and check if traffic switches to **JIO**.  

## **Future Enhancements**  
- Implement **Dynamic Routing (OSPF/EIGRP)** for automated failover.  
- Configure **NAT (Network Address Translation)** for better internet access control.  
- Add **ACLs (Access Control Lists)** to restrict unauthorized traffic.  
