
# Identity and Access Management
User identity is considered the new perimeter of cyber security, signifying the shift from traditional network-based security.  Users and their identities are often targets for malicious actors.

Every Organisation with a computer must do some form of Identity and access management (IAM), but the basics in assigning the right level of access is sometimes forgotten or falls off the list.  Managing the lifecycle of a user/employee is critical to security.  

Some of the below are examples of these common platforms in enterprise used to Manage Users:

 - Microsoft Active Directory services
 - Microsoft Entra ID (formerly Azure Active Directory)
 - Lightweight Directory Access Protocol (LDAP)

As a cyber security professional, it is important to understand some of the concepts within each of these platforms.

## Microsoft Active Directory Services
Windows Server since the early 2000’s has had Active Directory Domain Services (AD for short).  This is the core Identity and access management platform for most corporation networks.  
[What is Active Directory? - YouTube](https://www.youtube.com/watch?v=mH48U0PlLKI)

As AD has been around for a very long time, it was intended to exist within an internal network, not exposed directly to the internet.   AD, can be secured quite well, but it does have a lot of surface area of attack due to the various components that reside in the platform and underlying operating system.  **Some of the defaults that resided in networks 20 years ago, are no longer considered secure configurations.**  

When you then dive into Active directory there are some common components:
 - Domain Controllers
 - Roles and Services
 - Forest and Domain Architecture
 - All will have:
	 - User objects
	 - Groups objects
	 - Computer objects
 - Some AD environments will have:
	 - Microsoft Exchange (a Microsoft Email Service)
	 - Active Directory Certificate Services (a Microsoft Certificate Authority for issuing digital certificates)
	 - Active Directory Federated Services
	 - Federation with other Identity Platforms (e.g. Microsoft Entra ID)

To understand each of these in detail consider some of these:
1.  **Active Directory Domain Service Deep Dive - John Savill**<BR> [https://youtu.be/4qC7H-y7oKI?si=BZqJbyY1N28b6MYW](https://youtu.be/4qC7H-y7oKI?si=BZqJbyY1N28b6MYW)
2.  **The Line Between AD and Azure AD! - John Savill**<BR> [https://youtu.be/uts0oy8NlUs?si=ZmXaJGTQOYDFDy4Q](https://youtu.be/uts0oy8NlUs?si=ZmXaJGTQOYDFDy4Q)

### Modernising AD Security
Noting the security defaults from 20 years ago do not withstand common adversary tools, it is important to modernise AD.  Being aware of known exploitable paths, common misconfigurations and take steps to address it through System hardening and well-designed System Administration Practices. 

This group of content helps you understand more advanced Techniques to Modernise AD Security:  
 -  **Successful Active Directory Modernization (Semperis - maker of** **[PurpleKnight](https://www.semperis.com/purple-knight/?utm_medium=pd&utm_source=bing&utm_campaign=brand)** **assessment tool)** [https://youtu.be/nmOnttE1OW4?si=ZG-0C0M7bstJPNQZ](https://youtu.be/nmOnttE1OW4?si=ZG-0C0M7bstJPNQZ)
 -  Trimarc Security Videos -  [https://youtube.com/@trimarcsecurity?si=CEMQcVGRy2SfuxR-](https://youtube.com/@trimarcsecurity?si=CEMQcVGRy2SfuxR-)  <- this group really uplifted my sysadmin knowledge in protecting AD and Azure/M365 infrastructure
	 - **The top ten most common Active Directory security issues, their impact, and remediation** [https://youtu.be/wVQeJ-fQoKc?si=8lxF2FPBf1FytqWH](https://youtu.be/wVQeJ-fQoKc?si=8lxF2FPBf1FytqWH)
	 - **Securing Active Directory: Resolving Common Issues** [https://youtu.be/5BKGOpBhypk?si=h9IhFjCjGZTGTAXK](https://youtu.be/5BKGOpBhypk?si=h9IhFjCjGZTGTAXK)
	 - **Securing Active Directory: Protecting AD Administration** [https://youtu.be/sdKw04khTZU?si=tiYkM-kVO1SrQYyC](https://youtu.be/sdKw04khTZU?si=tiYkM-kVO1SrQYyC)
	 - **Securing Office 365 and Azure AD Defend Your Tenant** [https://youtu.be/ptufBlgHmkU?si=IghdN26vDf8kHV8i](https://youtu.be/ptufBlgHmkU?si=IghdN26vDf8kHV8i)

## Microsoft Entra ID
Microsoft Entra ID (not to be confused with AD) is Microsoft Azure’s core identity and access management platform to secure Office365 and Azure as-a-service systems. John Savill (youtube sources below) has a great walk through SC-300 which provides core skills around Azure AD - [SC-300 Microsoft Identity and Access Administrator Study Cram - YouTube](https://www.youtube.com/watch?v=LGpgqRVG65g&list=PLlVtbbG169nGj4rfaMUQiKiBZNDlxoo0y)
