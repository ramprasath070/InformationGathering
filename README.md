# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.



## Finding Hosting Company

<img width="947" height="784" alt="Screenshot 2026-01-30 132826" src="https://github.com/user-attachments/assets/decd9af7-c02e-47cf-afee-13d7c41414d4" />

## Finding IP address:


<img width="951" height="786" alt="Screenshot 2026-01-30 142320" src="https://github.com/user-attachments/assets/3cc83811-f9ce-4f4e-9779-2caeb73c6ab0" />

## History of the website:
## output


<img width="963" height="822" alt="Screenshot 2026-01-30 142659" src="https://github.com/user-attachments/assets/7b34f196-9fd3-4d99-80aa-505965e31dbe" />

# Webserver Fingerprinting:

## Netcat:
sudo nc brave.com 80
GET / HTTP/1.1
Host: example.com

<img width="960" height="452" alt="image" src="https://github.com/user-attachments/assets/3b79d3e5-8066-416b-8016-44bf88ee53b4" />


## nmap:
###output

<img width="638" height="380" alt="Screenshot 2026-01-30 140834" src="https://github.com/user-attachments/assets/bcb970d2-df50-41bb-aeb4-c8fa77b46e2e" />

## Whatweb
### output

<img width="867" height="690" alt="Screenshot 2026-01-30 141058" src="https://github.com/user-attachments/assets/d16dee42-c00e-4929-854a-96e44b3de0c5" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.brave.com
## output
<img width="951" height="472" alt="image" src="https://github.com/user-attachments/assets/61fe984c-fa7d-4013-8967-cebaab060f29" />


## UDP Traceroute:
sudo traceroute -U www.brave.com
## output


<img width="852" height="685" alt="Screenshot 2026-01-30 141743" src="https://github.com/user-attachments/assets/29401108-999e-4b4e-b283-ba392ae809bf" />

## ICMP Traceroute:
sudo traceroute  www.brave.com
## output


<img width="835" height="650" alt="Screenshot 2026-01-30 141432" src="https://github.com/user-attachments/assets/c4cb0f18-ec00-4952-a872-60bd3bb8f716" />




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
