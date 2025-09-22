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

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

<img width="1712" height="1018" alt="Screenshot 2025-09-19 131906" src="https://github.com/user-attachments/assets/089b2ae6-157b-4d8d-aea3-8a3ab67bf29c" />


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

## output

<img width="1191" height="1018" alt="Screenshot 2025-09-19 132031" src="https://github.com/user-attachments/assets/ce328ab3-3edd-4117-ba64-30bf636c66a4" />



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

## output

<img width="1255" height="736" alt="Screenshot 2025-09-19 132106" src="https://github.com/user-attachments/assets/2d3bdf45-2466-4773-8644-5a03191128e7" />


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

## output

<img width="1301" height="401" alt="Screenshot 2025-09-19 132200" src="https://github.com/user-attachments/assets/3ad70f3f-1408-4e9f-9007-82bd88a3c80c" />


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

## output


<img width="1227" height="666" alt="Screenshot 2025-09-19 132323" src="https://github.com/user-attachments/assets/6d0e17fe-9e39-4d84-ab97-0486af298295" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

## output

<img width="1370" height="812" alt="Screenshot 2025-09-19 132351" src="https://github.com/user-attachments/assets/ee46e98e-1952-41e4-99a0-af56386c9050" />

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

## output

<img width="947" height="607" alt="Screenshot 2025-09-19 140703" src="https://github.com/user-attachments/assets/9bef74ba-1ca5-4569-9a06-73e2de0bcb5e" />

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:


<img width="708" height="127" alt="image" src="https://github.com/user-attachments/assets/ab9ca18f-81e2-47c5-bd38-334c9a582ee1" />



##dnsenum
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

## output


<img width="792" height="765" alt="Screenshot 2025-09-19 134646" src="https://github.com/user-attachments/assets/9193e8ca-57cb-406b-adae-4994dcf0c8a5" />



##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output
  
  <img width="753" height="399" alt="Screenshot 2025-09-19 134704" src="https://github.com/user-attachments/assets/801528b5-fb17-4266-ab99-d0eca1297d18" />


## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

<img width="632" height="182" alt="Screenshot 2025-09-19 140108" src="https://github.com/user-attachments/assets/6c435e89-e1c9-49a7-99fd-e37d30c63dff" />


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

