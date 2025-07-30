# 3MTT--Cyber-security-Reonnaissance
# July 2025 3MTT Cybersecurity KnowledgeShowcase — Reconnaissance Techniques
#3MTTLearningCommunity @My3MTT
@3MTTNigeria 
@DAHIRU MUSA ADAMU
@My FE/23/11334801

# July 2025 3MTT Cybersecurity Knowledge Showcase — Reconnaissance Techniques


## 📚 Table of Contents
- [Overview](#-overview)
- [Tools Used](#-tools-used)
- [Methodology](#-methodology)
- [Setup Instructions](#-setup-instructions)
- [Demonstration](#-demonstration)
- [Conclusions](#-conclusions)
- [Credits](#-credits)

- ## 📘 Overview
This project is part of the 3MTT July 2025 showcase, demonstrating foundational and advanced reconnaissance techniques in cybersecurity. It highlights tools, methodologies, and practical insights used in the reconnaissance phase of ethical hacking.

As a refresher, the term ethical hacker describes a person who acts as an attacker and evaluates the security posture of a computer network for the purpose of minimizing risk

the same type of “research” performed by someone who then uses the same vulnerability to gain unauthorized access to a target network/system would be considered a nonethical hacker.

The truth is that as an ethical hacker, you use the same tools to find vulnerabilities and exploit targets as do nonethical hackers.

. So, the key factor here in defining ethical versus nonethical hacking is that the latter involves malicious intent. The permission to attack or permission to test is crucial and what will keep you out of trouble! This permission to attack is often referred to as “the scope” of the test (what you are allowed and not allowed to test). More on this later in this module.

The truth is that as an ethical hacker, you use the same tools to find vulnerabilities and exploit targets as do nonethical hackers.

                                                  RECONNAISANCE
  Reconnaissance

Reconnaissance is always the initial step in a cyber attack. An attacker must first gather information about the target in order to be successful. In fact, the term reconnaissance is widely used in the military world to describe the gathering of information about the enemy, such as information about the enemy’s location, capabilities, and movements. This type of information is needed to successfully perform an attack.                                            
                                                  
“If you know the enemy and know yourself, you need not fear the result of a hundred battles. If you know yourself but not the enemy, for every victory gained you will also suffer a defeat. If you know neither the enemy nor yourself, you will succumb in every battle.”
― Sun Tzu, The Art of War


- ## 🛠️ Tools Used
- 
- Recon-ng
-  Open-Source Intelligence (OSINT) Gathering
Open-source intelligence (OSINT) gathering is a method of gathering publicly available intelligence sources to collect and analyze information about a target. OSINT is “open source” because collecting the information does not require any type of covert methods. Typically, the information can be found on the Internet.
Recon-ng

This module covers a number of individual sources and tools used for information gathering. These tools are all very effective for their specific uses; however, wouldn’t it be great if there were a tool that could pull together all these different functions? This is where Recon-ng comes in. It is a framework developed by Tim Tomes of Black Hills Information Security. This tool was developed in Python with Metasploit msfconsole in mind. If you have used the Metasploit console before, Recon-ng should be familiar and easy to understand.

Recon-ng is a modular framework, which makes it easy to develop and integrate new functionality. It is highly effective in social networking site enumeration because of its use of application programming interfaces (APIs) to gather information. It also includes a reporting feature that allows you to export data in different report formats. Because you will always need to provide some kind of deliverable in any testing you do, Recon-ng is especially valuable.

Step 1: Start Recon-ng

To start using Recon-ng, you simply run recon-ng from a new terminal window. Example 1.1 shows the command and the initial menu that Recon-ng starts with. 

1.1 ![recon-ng](https://github.com/user-attachments/assets/f6860fa1-536b-40ee-a7cd-5a212d4727b6)
1.2![IMG_20250724_225253](https://github.com/user-attachments/assets/dc04ef3b-30a6-4234-9008-8128282b2a97)
1.3![IMG_20250724_225310](https://github.com/user-attachments/assets/c7afb463-cf8e-4666-9beb-17ad8f6f5d1e)
1.4![IMG_20250724_225326](https://github.com/user-attachments/assets/7803e0d5-849c-49ea-b352-d7d9255b47eb)
1.5![IMG_20250724_225340](https://github.com/user-attachments/assets/5ea15777-d146-4458-be28-43291668ac30)
1.6![IMG_20250724_225406](https://github.com/user-attachments/assets/99a6ce64-17ec-420f-99e9-f56b9353e23e)
1.7![IMG_20250724_225426](https://github.com/user-attachments/assets/5275beb6-0475-4085-a4b9-35c96ec4c7ff)
1.8![IMG_20250724_225442](https://github.com/user-attachments/assets/a1d7f138-5e72-4b50-8a35-04db1bada194)

Cryptographic Flaws
During the reconnaissance phase, attackers often can inspect Secure Sockets Layer (SSL) certificates to obtain information about the organization, potential cryptographic flaws, and weak implementations. You can find a lot inside digital certificates: the certificate serial number, the subject common name, the uniform resource identifier (URI) of the server it was assigned to, the organization name, Online Certificate Status Protocol (OCSP) information, the certificate revocation list (CRL) URI, and so on.
sslscan
SSL certificates are an essential part of online security. They are used to both encrypt data as it transmitted and establish that a website can be trusted as a source or destination for data. It is important to understand the identification and encryption information that is available in SSL certificates. 

in this the aims isto get familiar with SSL certificates and the information that they contain. This is an important part of our reconnaissance . 
- Nmap
- Whois
- Shodan
- Nmap
- Recon-ng
- Google Dorks

- ## 🔍 Methodology
The reconnaissance phase involved passive and active techniques, such as:
- DNS enumeration
- WHOIS lookups
- Network scanning
- Web metadata analysis
- Social media intelligence gathering
Each method was carefully selected to reflect real-world threat assessments.

## ⚙️ Setup Instructions
1. Clone this repository.
2. Install required tools using the script or manual setup.
3. Navigate to the `/demo` folder for showcase scripts and sample targets.
4. Run `python demo_scan.py` to see basic recon in action.

5. ## 🎥 Demonstration
A sample scan was conducted on a test environment to show enumeration techniques. Results include open ports, service banners, and discovered subdomains.

## 🧠 Conclusions
This showcase emphasized the power of reconnaissance as the first step in understanding a target system. Ethical hackers must master these tools to prepare for deeper security assessments.

## 🙌 Credits
Built by DAHIRU MUSA ADAMU as part of the 3MTT July Knowledge showcase 2025 cohort3.
Special thanks to [Mr.Alhassan odein Mr.Zulkiflu], and the 3MTT Cybersecurity community.
