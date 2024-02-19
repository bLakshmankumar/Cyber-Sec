# cyber-sec
cybersec-notes

# Network Architecture Diagram :
==========================================

 Added the details in the cyber-sec-class-9 git repo.

 [https://github.com/bLakshmankumar/cyber-sec/blob/main/Cyber-Sec-Class-9-NW-Architecture]
 

![Screenshot 2024-02-19 214556](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/467ff04c-4fd7-4df3-8e81-d49153369cdd)


# NOTE : Access switches(AS) primarily connect end-user(Employee) devices, such as computers, printers, phones, to the local network. 
#        CoreSwitch(CS) contains Entrire Organization of the Traffic. That entire traffic we can call it as netflow data.
#        NIDS is a copy of CS or copying of all organization traffic flow data.
# Note : We can deploy n-number of NIDS/NIPS based on Traffic,  We can call like nx1 nx2 and etc.
# NX meaning is : N = Network , X = ModelNumber, NX1 = N1000, NX2 = N4000, NX3 = N3000 & etc.
# As this above models NX2 = N4000 is the highest model num, so It'll act as our main tool, remaining NX1 and NX3 and others we will monitor from NX2.



# Cyber-Security-Class-10 :
===========================
# Cyber kill chain process :
-----------------------------

 ![Screenshot 2024-02-04 153534](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/b64d0178-42cd-4014-810f-7ac8033caa89)

# Cyber-Security-Class-10 :
==============================
# Backend Process of ARP Spoofing Attack :
------------------------------------------
  
![Screenshot 2024-02-10 124209](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/5e197061-097b-4079-a9e2-a47278e36910)

   # Here User want to send a request to Printer, So Switch will take the request from user and it'll forward the request to printer(destination) through router and Load Balancer.
   # But Here attacker will compromise the Switch, so Whenever the user sends a request, The request will go to swith and redirect to attacker system, Then he will give some malicious response to the user.
   # Once user click on the attacker link the system will get compromised/Attacker will gain a unauthorized access.
 

# Cyber-Security-Class-10 :
==============================
# Backend Process of DNS Spoofing Attack :
------------------------------------------

![Screenshot 2024-02-10 130032](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/b8cf5ad3-58f9-4e6e-a8f5-2722e0c54d13)

   # A user attempts to access their online banking website by entering the domain name (e.g., www.gitbank.com) into their web browser.
   # The attacker, who has infiltrated the network or compromised DNS servers, intercepts the DNS resolution process and responds to the user's request with a spoofed DNS response.
   # Instead of receiving the legitimate IP address of the bank's website, the user's device is directed to an attacker-controlled server hosting a fake banking website.
   # The user, unaware of the spoofing attack, enters their login credentials into the fake website, unwittingly providing them to the attacker.
   # The attacker captures the user's login credentials and may use them for unauthorized access to the user's bank account or for identity theft purposes.
   # In this example, the attacker successfully manipulated the DNS resolution process to redirect the user to a malicious website, exploiting their trust in the DNS infrastructure to carry out fraudulent activities.
   
# Cyber-Security-Class-11 :
==============================
# Roles & Responsibilities of a Cybersecurity as an interview point of view.

![Screenshot 2024-02-10 175828](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/33edbe83-8d65-4b16-8053-946628b0427f)

![Screenshot 2024-02-10 175908](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/caf1c928-daaa-40a4-bf32-a76664538456)

![Screenshot 2024-02-10 180322](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/63c5a892-803d-4f6e-acb3-a113abe4d32a)


# Licencing :
==============

![Screenshot 2024-02-13 201852](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/69012d39-5f13-4923-809b-90092b0dadbd)

Based on How many Endpoints we have, Each and every end-user machine we should deploy the EDR and DLP agent.


![Screenshot 2024-02-16 163110](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/cd11f509-b6d6-4253-8dca-6ab1ff70b82e)

Licencing depends on Number of end-users, LAN bandwidth or Speed, Number of applications, Max number of sessions, Max num of VPN sessions * etc.

# Cyber-Security-Class-11 :
===========================
# Detection Methods for Endpoint Security & Deployment Approach.
# It's an Agent and Server based approach

![Screenshot 2024-02-10 223347](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/19b067d2-ac60-4212-b68c-af34ba120746)

# We Will deploy Detection/Monitoring agents to Each and every Endpoint(end-user machine) with required policies and ports, Then the agent will start Detect the issues based on this agent backend methods/Policies.


#  Cyber-Security-Class-12 :
===========================
   # >  Security Profiles : 
   
![Screenshot 2024-02-16 200405](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/ea90cf42-7370-4322-b474-4f6776e1a110)

![Screenshot 2024-02-16 201731](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/f7f09eff-bd06-4eed-80fe-8b3d6507f630)

 # First we have to configure security profiles and Then we should implement on Firewall policies on inside the Policy & object option.
 # If we are not enable these security profiles then firewall will not block anything.
 # Security profiles refer to a set of security measures or configurations that are applied to network traffic or specific devices to enhance cybersecurity. 

 # High-Availabilty-setup(HA):
 # ===========================
 # We can set the primary and secondary firewall by providing the Device Priority.
 
 ![Screenshot 2024-02-17 192005](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/36ae4ca7-d746-459c-9d3b-293593c1ca8f)

 ![Screenshot 2024-02-17 192301](https://github.com/bLakshmankumar/cyber-sec/assets/109284987/8437ac6c-8c06-482c-a920-566129e7fb74)

 # Note : Primary server Device priority should be higher than Secondary firewall server. 
 
 


