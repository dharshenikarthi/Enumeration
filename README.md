# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c753a270-5d8c-4b39-b15b-96df51a51e58" />

### filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fbfa15b3-6d34-4fbe-a7fa-db34cb682c1a" />



### intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/792bb3eb-6581-42dd-a35f-1fbe46ceabe9" />


### inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7160a552-6ba1-45e2-8fdb-461ac8f1ccf4" />

### intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5832e4ee-83df-4913-83f0-87c5b019f293" />

### link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be2828f6-51a7-4d99-964a-69e0160a7e13" />

### cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5cd9e3d2-dfc3-421c-a02a-6d20df7d3a7b" />

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 19_32_24" src="https://github.com/user-attachments/assets/fc1fe172-8b18-4d00-8f20-d246a124fb66" />







## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
### OUTPUT:

<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 19_35_14" src="https://github.com/user-attachments/assets/cd82a4aa-3b91-4da7-ac87-51b393138641" />

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
### OUTPUT:
<img width="1920" height="1009" alt="Editing Enumeration_README md at main · amirthaviswanathan05_Enumeration - Google Chrome 19-09-2025 19_44_10" src="https://github.com/user-attachments/assets/88dd3cad-71bd-46d2-adb8-d510ba78a361" />


## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 19_51_45" src="https://github.com/user-attachments/assets/90d36cc8-0662-447d-a981-3fc0d85aeb7c" />


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

