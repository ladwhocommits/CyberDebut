# CyberDebut
Tracking my Cyber Security Progress starting from void .

#  Cyber Security 101 

Using `tryhackme.com` resources for building fundamentals in cyber security .

---
## MODULE 1: Start Your Cyber Security Journey


### 🛡️ Lab 1: Introduction to Offensive Security
 Offensive Security is about thinking like an attacker to find weaknesses before real hackers do. One common thing Hackers look for on a website is pages that are not linked . We used `dirb` in this module to scan a url in order to find pages that are not linked . This is a brute forcing tool . Requiring Login to Certain pages can help to strengthen the defence of the url.

### 🛡️ Lab 2: Introduction to Defensive Security
 Defensive security, is about keeping hackers out and acting when it goes wrong.  Security Operations Centre (SOC) is  the central hub for defending an organisation.  In defensive security, we share information about attackers,  This is known as threat intelligence . The monitoring dashboard shows a history of what the attacker is trying to find on our website. Incident reports allow us to reflect, train, and detail any attack and it  is helpful for us in defensive security .

### 🛡️ Lab 3: Search Skills
 This module teaches us to use the internet effectively for gathering information about services for both Offensive and Defensive Cyber security . For Example , we have
* **Shodan** which scans the internet for virtually anything  with a public network connection to see what's running and where .
* **VirusTotal** is a popular resource in the *blue teaming* community for obtaining a general consensus on suspicious files and links, as well as for gathering intelligence on new threats .
* **Common Vulnerabilities and Exposures** (CVE) programme can be described as a universal dictionary of known vulnerabilities. Each Vulnerability is assigned a unique Identifier in the format of `CVE-YEAR-NUMBER` and they are given scores `(CVSS)` on the basis of some factors like *Impact , Complexity and Availability *
 *  Linux MANual pages helps us to read within our terminal about any command of Linux .
    * **Format** `man < command >`


## MODULE 2: Linux Fundamentals 

### 🛡️ Lab 1 : Linux Fundamentals : Part 1 

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
   
<!-- Template For Future Push
### 🛡️ Lab <Digit>: <name>
 <Core Concepts >
-->
