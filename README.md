# Cyber Debut

Tracking my Cyber Security Progress starting from void .
Using  Free resources for building fundamentals in cyber security .


## LEVEL 1 :  Getting Started

*Building Basic Fundamentals of Cyber Security in this Set of Modules .
Source - TryHackMe Free*

###  Module 1 : Introduction to Offensive Security
 Offensive Security is about thinking like an attacker to find weaknesses before real hackers do. One common thing Hackers look for on a website is pages that are not linked . We used `dirb` in this module to scan a url in order to find pages that are not linked . This is a brute forcing tool . Requiring Login to Certain pages can help to strengthen the defence of the url.

### Module 2 : Introduction to Defensive Security
 Defensive security, is about keeping hackers out and acting when it goes wrong.  Security Operations Centre (SOC) is  the central hub for defending an organisation.  In defensive security, we share information about attackers,  This is known as threat intelligence . The monitoring dashboard shows a history of what the attacker is trying to find on our website. Incident reports allow us to reflect, train, and detail any attack and it  is helpful for us in defensive security .

###  Module 3 : Search Skills
 This module teaches us to use the internet effectively for gathering information about services for both Offensive and Defensive Cyber security . For Example , we have
* **Shodan** which scans the internet for virtually anything  with a public network connection to see what's running and where .
* **VirusTotal** is a popular resource in the *blue teaming* community for obtaining a general consensus on suspicious files and links, as well as for gathering intelligence on new threats .
* **Common Vulnerabilities and Exposures** (CVE) programme can be described as a universal dictionary of known vulnerabilities. Each Vulnerability is assigned a unique Identifier in the format of `CVE-YEAR-NUMBER` and they are given scores `(CVSS)` on the basis of some factors like *Impact , Complexity and Availability*
 *  Linux MANual pages helps us to read within our terminal about any command of Linux .
    * **Format** `man < command >`

### Module 4 : Linux Fundamentals : Part 1 

A command is an instruction that we can give the computer to perform a given task. Here we will learn some basic Linux terminal commands to get comfortable with the Command Line User Interface .
 * `whoami` - Tells the current user of the system .
 
    ![](Pasted%20image%2020260806121414.png)
 * `echo` - Prints the Phrase followed by this command . 
 
    ![](Pasted%20image%2020260806121434.png)
* `ls` - Lists what is in the Current Folder/Directory

    ![](Pasted%20image%2020260806122233.png)
*  `cd` - Changes Directory

    ![](Pasted%20image%2020260806122346.png)
*  `cat` - Shows the Contents of a File
  
    ![](Pasted%20image%2020260806122445.png)
    
*  `pwd` - Prints the present working directory - " where am i ?" 

    ![](Pasted%20image%2020260806122518.png)
*  `find` - Searches for files by their names .
* `grep` -  Searches inside for text .
    ![](Pasted%20image%2020260806123004.png)

In Linux , There are set of Special Characters that can combine commands together or send the output of a command elsewhere , these special characters are called *Operators* . 
* `&` -  The command runs in the background . 
* `&&` - Runs Both the Commands but waits for the first command to finish , before the next .
* `>` - To take the output of a command and send it to elsewhere , like a file . This command will overwrite anything that's written in that File .
   
    ![](Pasted%20image%2020260806124526.png)
* `>>` - Just like the previous `>` operator but instead of overwriting , it adds the output of the command to the bottom line of the file .
   
    ![](Pasted%20image%2020260806124557.png)
    
    Now overwriting this file with `>` redirect operator 
    
    ![](Pasted%20image%2020260806124713.png)
   

### Module 5 : Careers in Cyber 

 *  **Security Analyst**  
     Security Analyst are often referred to as the digital defenders of an organisation and sit on the *blue team* . They use their skills to investigate potential security incidents , known as **alerts** , and respond accordingly . 
      
   * **Day in life of Security Analyst**
    
        *  Monitoring Activity taking place on the device and network of the organisation.
        * Investigating unusual or suspicious activity , such as strange logins .
        * Piecing together Information to understand what has happened , when and how .
        * Working with other team to improve the organisation's defence .


* **Security Engineer**
       Security Engineers build and maintain the systems and processes that protect an organisation's network and devices and are known as architect of cyber-security.
       They are responsible for maintaining an **Intrusion Detection System** *(IDS)* which can be considered a security camera with an organisation's digital environment .

 End of Module , And level 1 . As far as current level is concerned and the knowledge about cyber-security field i have got , I'm interested in Offensive Security .  




## Level 1.5 : Prerequisites Before Moving to Level 2
Here we will study some topics which we should know in order to have a great command on the upcoming Level 2 . 

### Module A : Web Application Basics  
User generally interacts with the "Face" of a web application , that face can be "Front End" of the web application . It is made up of **HTML(Hypertext Markup Language)** , **CSS(Cascading Style Sheets)** and **Java Script** and more technologies . 

Also there is a "Back End" of a web application , which consist of Database (To store , retrieve and manage Data of a user) , A Web Application Firewall , which provides an element of protection by filtering out dangerous Requests .

 * A Web Server is responsible for hosting and delivering content for web applications.
 * A **URL** (Uniform Resource Locator) is an address which helps us to locate web pages , photo , video on the internet . 
     A URL is generally Made up of these sub parts 
     
     Example : `https://github.com/ladwhocommits/CyberDebut` 
     
	 *  **Scheme** : `http` or `https` ; A protocol used to access the website .  
	 * **User** : `ladwhocommits` 
	 * **Host/Domain** : `github.com` ;  Most important thing , which tells you that which website you are accessing .  Intentionally using 'typo' in the domain for exploiting users to engage in fraud activities is termed as **typo squatting** 
	 * **Port** : (Not in this example) ; It can be explained with the Analogy of "Explaining the browser which doorway to use for communication" . For HTTP(Hyper Text Transfer Protocol ) , 80 is used as a port number and for HTTPS(Hyper Text Transfer Protocol Secure ) , 443 is used as the same .
	 * **Query String** : (Not in this example ) ;  Used for Search Inputs , starts with '?' in the url .
	 * **Path** : `CyberDebut` ; Points to the specific page you are accessing .
	 * **Fragment** : (Not in this example) ; Starts with `#` to specifically point to a particular section of a web page  . 

## LEVEL 2 : Tooling 
Learning some tools needed in Ethical Hacking .

###  Module 1 : NMap : Discovering Live Hosts
NMap is a short abbreviation for Network Mapping . It is a free , open source software released under the GPL License , created by Gordon Lyon(Fydoor) . It is an Industry Standard tool for mapping networks , identifying live hosts and discovering running services 

<!-- COmplete level 1.5 Before Moving to Level 2 -- > 
