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

## site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## Output:
![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/e24e7a95-df36-44b0-829d-8d2fd1bc9484)




## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:
![Screenshot 2024-04-22 195017](https://github.com/R-Udayakumar/Enumeration/assets/118708024/bd434dff-b955-4ec0-81e9-d96213ada63c)






## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
![Screenshot 2024-04-22 195107](https://github.com/R-Udayakumar/Enumeration/assets/118708024/b12366fc-d9b7-4f73-a645-039e430c439d)





## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Ouput:
![Screenshot 2024-04-22 195154](https://github.com/R-Udayakumar/Enumeration/assets/118708024/aec9c31c-53a8-4cd2-a867-e30e8cfcf123)




## intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![Screenshot 2024-04-22 195304](https://github.com/R-Udayakumar/Enumeration/assets/118708024/450cac59-0b0f-4f08-9f99-f522fae873b7)



## link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
![Screenshot 2024-04-22 195359](https://github.com/R-Udayakumar/Enumeration/assets/118708024/7ced64db-188c-4377-ab7f-89d6255060e5)



## cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:
![Screenshot 2024-04-22 195952](https://github.com/R-Udayakumar/Enumeration/assets/118708024/b759cfd4-8bcc-4f04-a6a6-83d7ab10c97b)



 
# DNS Enumeration
## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/6013cc79-5085-4485-a092-e9aaecd5df3e)



![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/7e672e97-66ba-41ad-b9a5-8c1da64d0db3)



![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/08db0159-981e-4de4-8f3c-d069f3c96ce2)





## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![Screenshot 2024-04-22 201755](https://github.com/R-Udayakumar/Enumeration/assets/118708024/74eb8736-ac07-4b65-ac42-73272fe997f8)


## metasploit 
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/e4ade820-4dca-4054-bb76-a1b85ff281dd)

select any username in the first column of the above file and check the same
![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/26faea21-9e49-457b-8a7e-d7b8332cdb5f)


## nmap –script smtp-enum-users.nse <hostname>
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

![image](https://github.com/R-Udayakumar/Enumeration/assets/118708024/8bb8d307-a6d6-4da0-8a84-5b22fac5acc8)



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
