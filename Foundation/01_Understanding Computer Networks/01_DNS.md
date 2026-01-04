![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&width=530&lines=UNDERSTAND+COMPUTER+NETWORKS!)
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
12. [DNS Security Extensions (DNSSEC)](dns-security-extension)
13. [Reverse DNS Lookup](#reverse-dns-lookup)
14. [Common Use of Reverse DNS Lookup](#common-use-of-reverse-dns-lookup)
    - Network Diagnostic
    - Email Sceurity
15. [DNS Record Types](#dns-records-types)
16. [DNS Attack](#dns-attack)
17. [Common Types of DNS Attack](common-types-of-dns-attack)

---

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
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DOMAIN+NAME+SERVER!)

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

DNS Caching is a Machanism in which DNS Records are Stored Temporarily at Verious Level (Browser, Os, or DNS Resolver) to Avoide Repeatedly Querying External DNS Server for the same domain.
This improve browsing speed and reduces network traffic.

## Time-To-Live (TTL) 

TTL is the amount of the time a DNS Record remains stored in the cache before it expires. Once the TTL value expires the cached records is deleted and a new DNS query is made to obtain updated information. The TTL value is set by the authoritative DNS server and can be adjusted depending on how frequently the domain IP address changes.


> If the TTL for www.example.com is 36000 seconds the DNS records will be cached for 1 hour after one hour the cache
> expires and a fresh DNS lookup is required to retrive the IP address again.

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DNS+SECURITY!)

## DNS Security

Althorugh DNS play a vital (Important) role in internet communication it is vulnerable to certain security threats One common threat is DNS cache poisoning where attackers insert false DNS records into a cache redirecting users to malicious or fraudulent website.

## DNS Security Extension (DNSSEC)

DNSSEC is a security protocol designed to protect DNS from such attacks. It works by adding cryptographic digital signatures to DNS records.

* Provides Authentication of DNS data.
* Ensures the integrity of DNS Responses.
* Allows the DNS resolvers to verify the DNS information has not been altered or trapered with.
* Helps Prevent attacks like DNS cache poisoning and spoofing.

> In Simple terms DNSSEC ensures that users receive accurate and trustworthy DNS information when accessing website.

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=REVERSE+DNS+LOOKUP!)

## Reverse DNS Lookup 

Reverse DNS Lookup is the process of mapping an IP address back to it's corresponding domain name which opposite of a standard DNS lookup (Domain name -> IP address).

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=COMMON+USE+OF+REVERSE+DNS+LOOKUP!)

## Common Use of Reverse DNS Lookup

- **Network Diagnostic :-** System administrators use reverse DNS to identify the domian name associated with a specific IP address helping trace the sources of network traffic.

- **Email Security :-** Many Email Server perform reverse DNS lookup to verify that incoming emails come from legitimate sources helping prevent spam and email fraud.

> In Short, Reverse DNS add an extra layer of verification for network management and security.

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DNS+RECORD+TYPES+!)

## DNS Records Types

- **A Record (Address Records) :-** maps a domain name to an IPv4 address.
e.g., www.example.com -> 93.184.216.34

This is the most common record pointing a domain to its website.

- **CNAME Records (Cononical Name Records):-** Creates an alias from one domain to another
e.g, www.example.com -> example.com

- **MX (Mail Exchange Records):-** The MX records define which mail server are responsible for receiving emails for a domain. This is crucial for setting up email services.

- **TXT Record (Text Record):-** Stores text-based information
common use include domain ownership verification and email security protocols like SPF (Send Policy Framework) and DKIM
(DomainKey Identified Mail).

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5BF71A&width=435&lines=DNS+ATTACK!)

## DNS Attack 

DNS Attack exploit vulnerabilities in the DNS protocol to redirect or intercept traffic. These attack can lead to unauthorized access data breaches and disruption of services.

### Common Types of DNS Attack

- **DNS Spoofing / DNS Cache Poisoning:-** Attackers inject false DNS records into a DNS resolver cache causing user's to be redirected to malicious website instead of iegitimate one.

- **DNS Hijacking:-** The attacker changes DNS Setting on a devices router or server so DNS queries are resolved by malicious DNS Server.

- **Denial of Service (DoS):-** A DoS attack happens when one attacker send large number of requests to server website or networks to overload it making it slow or completely unavailable to real user's.

- **Distributed Denial of Service (DDoS):-** DDoS attack is similar to DoS but the attack comes from many devices at the same time often from a botnet (infected computer or IoT devices).

---

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrainMono&size=50&pause=1000&color=F158A4&width=500&height=100&lines=COMPLETED!)