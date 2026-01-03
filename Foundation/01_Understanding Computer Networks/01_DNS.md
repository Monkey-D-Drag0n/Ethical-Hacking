![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=UNDERSTAND+COMPUTER+NETWORKS!)
---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=F71918&width=435&lines=DOMAIN+NAME+SYSTEM+(DBMS)!)
---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2BDDC6E6&width=435&lines=INDEX!)
---

1. [Domain Name System(DNS)](#domain-name-system-dns)
2. [Function of DNS](#function-of-dns)
3. [Working of DNS](#working-of-dns)
   - User Inputs
   - Local Cache Check
   - DNS Resolver Query
   - Root DNS Server
   - Top-Level Domain (TLD) Server
   - Authoritative DNS Server
   - Final Response
4. [Structure of DNS](#structure-of-dns)
   - Root DNS Server
   - Top-Level Domain Server
   - Authoritative DNS Server
5. [Types of Domains](#types-of-domains)
   - Generic Domains
   - Country Code Domain (ccTLDs)
   - Inverse (Reverse) Domain
6. [Domain Name Server](#domain-name-server)
7. [DNS Lookup (DNS Resolution)](#dns-lookup-dns-resolution)
   - DNS Resolver
   - Recursive Query
   - Iterative Query
   - Non-Recursive Query
8. [Types of DNS Queries](#types-of-dns-queries)
   - Recursive Queries
   - Iterative Query
   - Non-Recursive Query
9. [DNS Caching](#dns-caching)
10. [Time-To-Live(TTL)](time-to-live)
11. [DNS Security](#dns-security)
12. [DNS Security Extensions (DNSSEC)](dnssec)
13. [Reverse DNS Lookup](#reverse)
14. [Common Use of Reverse DNS Lookup](#use-of-reverse-dns)
15. [DNS Record Types](#dns-record-types)
16. [DNS Attack](#dns-attack)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=F7CB7D&width=440&height=51&lines=Domain+Name+System+(DNS)!)](#domain-name-system-dns)

## Domain Name System (DNS)

Domain Name System (DNS) is a Hierarchical and Distributed Mapping System Used on the Internet to Translate Human Readable Domain Names into IP Addresses Allowing Users to Access Website Easily.

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=F6F715&width=435&lines=FUNCTION+OF+DNS!)


## Function of DNS

- Convert Domain Names (e.g.,www.example.com) into IP Address.
- Eliminates the Needs for Users to Remember Numerical IP Addresses.
- Uses Root Server, Top-Level Domain (TLD) Servers, and Authoritative DNS Server to Resolve Domain Names.
- Support Caching Which Improves Speed and Reduces Networking Traffic.
---

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=WORKING+OF+DNS!)](#working-of-dns)

## Working of DNS

The Domain Name System (DNS) works through a series of steps that allow users to access a website by typing a domain name instead of an IP address.

- **User Inputs :-** The user enters a website address (e.g., `www.example.com`) into the web browser.

- **Local Cache Check :-** The browser first checks its local cache to see if the IP address for the domain is already stored. If found, it uses the cached IP address and no further DNS query is needed.

- **DNS Resolver Query :-** If the IP address is not found in the local cache, the computer sends a request to a DNS resolver, usually provided by the Internet Service Provider (ISP).

- **Root DNS Server :-** The resolver contacts the root DNS server to find information about the top-level domain.(TLD) Server (Such as .org, .com, etc...).

- **Top-Level Domain (TLD) Server :-** TLD Server Responds with the Address of the Authoritative DNS Server for the Request Domain (e.g, example.com).

- **Authoritative DNS Server :-** The Authoritative Server Contains the Actual DNS Records and Provides the Correct IP Address of the Website.

- **Final Response :-** The DNS Resolver Returns the IP Address to the User's Computer Which then Connect to the Web Server and Loads the Website.

---
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=STRUCTURE+OF+DNS!)

## Structure of DNS 

The Domain Name System (DNS) Operates Using Hierarechical Structure which Ensures Stability, Efficiency, and Reliability Across the Global Internet.

- **Root DNS Server :-** These are the Top-Level Server in the DNS Hierarchy they do not Store IP Address of Website but Known the Location of Top-Level Domain (TLD) Server and Direct DNS Queries to them.

- **Top-Level Domain (TLD) Server:-** TLD Server Manager Domain Extensions Such as .com, .org, .net, .edu, .gov, and other they guide DNS Server Queries to the appropriate Authoritative DNS Server for the Requested Domain.

- **Authoritative DNS Server :-** These Server Store the Actual DNS Records of Domain Names Including IP Addresses. They Provide the Final and Accurate Response that allows User's to Access Website.

> This Hierarchical Structure Enables DNS to Handle Billions of Request Efficiently while Maintaining Accuracy and Speed.

---

## Types of Domains 

DNS Helps Manage Different Types of Domain to Organize the Large Number of Website on the Internet. 

### The Main Types Are : 

- **Generic Domains :-** These Include the Commonly Used Top-Level Domain Such as .com, .org, .net, .edu, etc.. they are Widely Recognized and Used Across the World.

- **Country Code Domain :-** These Domain Represent Specific Countries or Region Such as .in (India), .us (United States), .uk (United Kingdom), and .jp (Japan).

- **Inverse (Reverse) Domain :-** Inverse Domain are Used for Reverse DNS Lookups which map IP Addresses back to Domain Names this is useful for Network Diagnostics and Security Helping Verify the Legitimacy of Networks Traffic.

---
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=Domain+Name+Server!)

## Domain Name Server 

When a User Request a Website the Client Machine Sends a Query to the Local Server does not have the IP Address in it's Caches it Forwords the Request to the Root Name Server.

The Root Name Server does not Usually Store the exact IP Address of the Website but it Knowns which Top-Level Domain (TLD) Server Should be Queried. In Some Case it may Contain Limited Hostname to IP Query Mappings.

The TLD Server (Such as .com, .org, etc...) Known the Location of the Authoritative Name Server for the Request Domain and Direct the Query to it.

The Authoritative Name Server Contain the Actual DNS Records and Returns the Correct IP Address. This IP Address is Sent Back to the Local Name Server Which then Delivers it to the Client Machine Allowing the Website to Load.

---
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DNS+LOOKUP+(DNS+RESOLUTION)!)

## DNS Lookup (DNS Resolution)

DNS Lookup also known as DNS Resolution, is the Process of Converting a Human Readable Domain Name into it's Corresponding IP Address Enabling Computers to Locate Website on the Internet.

- **DNS Resolver :-** The DNS Resolver also called a DNS Client Initiates the Lookup Process on Behalf of the User.

- **Recursive Query :-** In a Recursive Query the Resolver takes full Responsibility for Finding the IP Address by Querying Multiple DNS Server Unit the Correct Answer Obtained.

- **Iterative Query :-** Resolver ask Servers for the Best Answer Avilable.

- **Non-Recursive Query :-** In Non-Recursive Query the Resolver queries a DNS Server that already has the Requested Records Stored in it's Caches and immediately Returns the IP Address.

## Types of DNS Queries 

- **Recursive Queries :-** In a Recursive queries the DNS Client Experts the DNS Server to Provide a Complete Answer. if the Server Cannot find the Request Records it Must Return Either the Correct IP Address or an Error Messages. The Server takes full Responsibility for Resolving the Query.

- **Iterative Query :-** In an Iterative Query the DNS Client Request the best Possible Answer for the DNS Server that may have more information.

- **Non-Recursive Query :-** A Non-Recursive Query Occurs When the DNS Resolve Queries a DNS Server that already has the Required Records Either Because it is Authoritative for the Domain or Because the Records is Stored in it's Cache. The Server Return the Result Immediately.

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DNS+CACHING!)

## DNS Caching 

DNS Caching is a Machanism in which DNS Records 
