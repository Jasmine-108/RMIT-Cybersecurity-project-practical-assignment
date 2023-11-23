# RMIT-Cybersecurity-project-practical-assignment
RMIT Cert 4 Cybersecuirty, Class Cyber security Project (INTE5061), Group practical Project

# Summary and Purpose of Assessment 

This project is one of two assessment tasks you need to complete satisfactorily, in order to be deemed competent for this unit.  Completing this project allows you to demonstrate developing and undertaking the implementation of a solution for an industry project.     

# Assessment Instructions 

You must work in a team to develop an industry project including identifying the business problem and undertaking implementation and evaluation of a solution.  

# What 

You have been nominated as the team organiser for a group of four (5) including yourself.  Your team will be designing and implementing a cyber-security management plan for a new client.  The details of the client will be provided to you by your assessor, or they will direct you to use the simulation client (included at Appendix 1).    For this project your assessor will play the role of the client in confirming project requirements and seeking feedback.  

The target of this project is to use introductory red team / blue team methods to achieve a secure system that is protected against common vulnerabilities.  

Your manager (also played by the assessor) will be the system designer for this project.  You will direct all feedback and questions to the system designer and apply all feedback which they provide to you.  

In your teams you will need to carry out a number of different activities in order to plan, implement and evaluate the project.   The teamwork will be conducted in class – you will make decision, configure labs, run tests and test your management plan over the five (5) planned sessions.  

# Scenario

The client is new to cyber-security in general but has begun to sell digital products via a subscriber website. The digital products range from royalty-based music and video clips through to plans and specifications for business products.  

*  Users download the content in a format of their choice and by entering a contract for its fair use. 

*  The content is submitted to the site and managed by the content-creator / artist.  

*  The client receives its money as portion of the sale or lease fee agreed to by the user.   

The client is concerned about fraud regarding the originality and uniqueness of content and ensuring that the original content creator is correctly attributed and receives fair compensation.  

Likewise, they are concerned about the security of the website ensuring that the content remains secure behind the paywall and cannot be easily mined and distributed by others.  

Finally, they are concerned about financial security – they have heard of other organisations where the transaction is made, the content is accessed but then the payment is cancelled, resulting in the distribution of work, essentially, for free.  

They run the website in the cloud, with only the physical website files backed up physically to an external hard drive. Each integrated application, software and website is accessed via usernames and passwords issued to staff.  One of the two company directors is responsible for enrolling new users and forwarding the details, via email, to the staff member. They keep a spreadsheet of all login details in case someone forgets their access details. They ask that staff who create new accounts with other web resources forward the login details of those accounts to the director for safekeeping and to maintain business interests too.  

They wish this to remain as a lifestyle business so infrastructure includes portable devices that can be used on and offsite including laptop computers, printers, normal peripheral devices (wireless keyboards and mice), USBs / external drives.  The current office contains an ARLO nanny-style cam connected to the WIFI and accessible by the company directors when they receive a notification of movement in the office outside of business hours.   

Staff access the workplace network to run their personal devices included smart phones, tablets, and laptops (as needed).   The staff currently use their own networks when offsite. This includes tethering to a mobile phone, using free Wi-Fi hotspots and accessing home networks.  

While they do not expect to be able to solve all problems immediately, they do wish to secure the current infrastructure using a range of security tools and software, physical infrastructure, access management and regular monitoring.  Additional infrastructure, tools and processes should be recommended for implementation and a plan for implementation established that enables the company directors to budget for the additional costs.  

# Virtual Machines
Each group memeber was tasked with creating a list of virtual machines being:
* Windows 10 (client)
* Windows Server
* Linux Ubuntu (Elkstack)
* PFSENSE
* Kali Linux

**WINDOWS SERVER**

The Windows Server was promoted to a `domain controller` and the client was joined to that domain 
- The domain needed to be named the name of our group in our case it was Fix Ur Things
  
![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/2bb6c306-aefd-4579-a1fe-f43efe1e4741)


**PFSENSE** 

Since all machines were in an internal network pfsense requires 2 adaptors for connecting with the internal network and the outside network alloing all machiens in the internal network to connect to the internet

![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/e2e57c54-860a-40c3-807c-05cdd3fbd36a)


- Windows Server connecting to Youtube through pfsense
   
![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/d6e9dbec-c93d-4e1a-9621-b44778f887f7)


We were also tasked with setting `SNORT` on pfsense

![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/c798ab01-57a7-497e-83eb-23d5b21b3a0c)

- snort detecting traffic

**ELASTIC**

We were tasked with installing elastic on ubuntu and linking it to our server with winlogbeat

![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/7690afc1-5be0-451a-aae3-b2fa4649e9bf)


# Appendix 4 – Implementaion plan
I was assigned with explaining a `Phishing` attack and demonstrating why these are dangerous to the organisation and how we can prevent from the attack from happening

`Zphisher` was installed and use on kali to demonstrate how this attack works

![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/4b842c86-f32b-4fe8-8030-764febfc9947)

# Appendix 5 – Technical Documentation 
Instructions:  

Use each of the headings below to plan and prepare your technical documentation.  

You must address each heading and its prompts with knowledge and instructions in plain-English. You should assume that the end-user is a lay person with no experience in cybersecurity.  This means you should consider the who, what, when, where how and why of each prompt and use screen shots, images, and diagrams where possible. 

I was tasked with explaining Configuring Firewalls the things I had to explain were:
* Explain how firewalls are to be used in the client workplace as identified in your planned solution.
* Give instructions for configuring or maintaining the firewall as it applies post-implementation of your planned solution.

# Project plan

I worked on the `wireless netowrks` section of the project plan

![image](https://github.com/Jasmine-108/RMIT-Cybersecurity-project-practical-assignment/assets/151819725/ed4a9892-f4e4-4c39-9f27-bb43a039b47a)

