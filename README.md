APPLY OS HARDENING TECHNIQUES

SCENERIO

Review the scenerio below. then complete the step-by-step instrauctions.

You are a cybersecurity analyst for yummyrecipesforme.com a website that sells recipes and cookbooks. a former employee has decided to lure users to a fake website with malware.

The baker executed a brute force attack to gain access to the web host. they repeatedly entered several known default passwords for the administrative account until they correctly guessed the right one. after they obtained the login credentials they were able to access admin panel and change website source code. they embedded a javascript function in the source code that prompted visitor’s to download and run a file upon visiting the website. after embedding the malware, the baker chnaged the password to the administrative account. when customers download the file, they are redirected to a fakje version of the website that contains the malware. 

Several hours aafter the attack, multiple customers emailed yummyrecipesforme’s helpdesk. they complained that the company’s website had prompted them to download a file to access free recipes. the customers claimed that, after running the file, the address of the website changed and their personal computers began running more slowly.

In response to this incident, the website owner tries to log in to the admin panel but is unable to , so they reach out to website hosting provider. you and other cybersecurity analysts are tasked with investigating this security event.

To address the incident, you create a sandbox environment to observe the suspicious website behaviour. you run the network protocol analyzer tcpdump, then type in URL of the website, yummyrecipesforme.com. As soon ad the website loads, you are prompted to download an executable file to uodate your browser. you accept the download and allow file to run. you then observe that your browser redirects you to a different URL, greatrecipesforme.com, which contains the malware

The logs show the following process: 

1.The browser initiates a DNS request: it requests the ip address of the yummyrecipesforme.com URL from the DNS server

2.This DNS replies with the correct ip address

3.The browser initiates an HTTP request: it request the yummyrecipesforme.com webpage using the ip address sent by the DNS server

4.The browser initiates the download of the malware

5.The browser initiates a DNS request for greatrecipesforme.com

6.The DNS server responds with the ip address for greatrecipesforme.com

7.The browser initiates an HTTP request to the ip address for greatrecipesforme.com


A senior analyst confirms that the website was compromised. the analyst checks the source code for the website. they notice that the javascirpt code had been added to prompt website visitors to download an executable file. analysis of the downloaded file found a script that redirects the visitor’s browsers from yummyrecipesforme.com to greatrecipesforme.com.

The cybersecurity team reports that the web server was impacted by a brute force attack. the disgruntled baker was able to guess the password easily because the admin password was still set to default password. Additionally, the were able to controls in place to prevent the attack.
Your job is to document the incident in detail, including identifying the network protocols used to establish the connection between the user and the website. you shouod also recommed a security action to prevent brute force attacks in the future.

step by step instructions

Identify the network protocol involved in the incident

Document the incident

Recommend one or more remediations for brute force attacks
