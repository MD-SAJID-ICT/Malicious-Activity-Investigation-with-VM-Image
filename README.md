<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Malicious Activity Investigation</h1>
  <br>
  
<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/logo%20of%20investigation.png" width="400" height="400">

  

<h3 align="center">Project Module - Digital Forensics</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="[#overview-of-the-project](https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image#1-overview-of-the-case)">OVERVIEW OF THE CASE</a>
      <ul>
        <li><a href="#required-findings">Required Findings</a></li>
        <li><a href="#installation">Timeline of The Key Evidence</a></li>
        <li><a href="#installation">Details of the offenders, victims and witnesses</a></li>
        <li><a href="#installation">Photographs of any physical evidence, clues or supplemental material</a></li>
        <li><a href="#installation">Scenario Rules</a></li>
      </ul>
    </li>
     <li>
      <a href="#getting-started">LEGISLATION ANALYSIS</a>
      <ul>
        <li><a href="#prerequisites">Legislation</a></li>
        <li><a href="#installation">Points to prove</a></li>
        <li><a href="#installation">What the Digital Forensics case can prove</a></li>
        <li><a href="#installation">What the Digital Forensics case will not prove</a></li>
        <li><a href="#installation">Highlight any artefacts that undermine the prosecution’s case</a></li>
      </ul>
    </li>
     <li>
      <a href="#getting-started">EVIDENCE FILE</a>
      <ul>
        <li><a href="#prerequisites">Details of the Evidence File</a></li>
        <li><a href="#installation">Hash value of the Evidence File</a></li>
      </ul>
    </li>
     <li>
      <a href="#getting-started">ARTEFACTS</a>
      <ul>
        <li><a href="#prerequisites">Summary of Artefacts</a></li>
        <li><a href="#installation">Data Recovery Artefacts</a></li>
        <li><a href="#installation">Data Hiding Artefacts</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">SUPPORTING MATERIAL</a></li>
    <li>
    <a href="#usage">PERSONAL REFLECTION</a>
    <ul>
        <li><a href="#prerequisites">Student</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

You are part of a team working for Z-Security, an elite digital forensics company in the UK that was invited 
to investigate a recent security incident involving suspected criminal activities taking place in a medium sized company called UBB.
You have been hired to physically investigate some of the affected assets, while other Z-Security team 
members were assigned similar tasks in order to reduce the overall investigation time. As part of your 
role, you will be asked to prepare an appropriate digital forensics toolkit together with a Digital Forensics 
Investigation (DFI) model to facilitate your investigation tasks. Any legal interface between law 
enforcement and this organisation is also a component to be evaluated as part of your assignment.

<b>The incident(s):</b> Network administrators at UBB identified unusual P2P and encrypted traffic that is rarely 
needed to support their business processes. An early investigation of some of their system logs confirmed 
suspicious connections some of which bypassed their firewall rules. Alice, a senior ICT manager with 
reasonable incident response training was keen to keep all the machines attached to the suspected 
subnet running while he sent an urgent request for Z-Security to start an investigation (based on an 
Incident Response contract between the two parties).
Bob’s decision was significantly encouraged by recent reports showing further incidents in the company, 
in particular, an increased number of staff accounts being accessed from unusual locations inside and 
outside the company. This has raised concerns of the possibility of an insider attack or inappropriate 
behaviour and misuse of the company’s infrastructure.


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- 1. Overview of the Case -->
## 1. Overview of the Case

### 1.1 Required Findings

● An early investigation of some of their system logs confirmed suspicious connections some of 
which bypassed their firewall rules.<br>
● An increased number of staff accounts are being accessed from unusual locations inside and 
outside the company.<br>
● An insider attack or inappropriate behavior and misuse of the company’s infrastructure.<br>
● You must discover, document and forensically report any two actions performed on the seized 
device in violation of UBB’s Acceptable Use Policy .

### 1.2 Acceptable Internet use policy for UBB

UBB has a policy for the use of the internet whereby employees must ensure that they:<br>
● comply with current legislation.<br>
● use the internet in an acceptable way.<br>
● do not create unnecessary business risk to the company by their misuse of the internet.


## 1.3 Unacceptable behaviour

In particular the following is deemed unacceptable use or behaviour by employees:<br>
● visiting internet sites that contain obscene, hateful, pornographic or otherwise illegal material.<br>
● using the computer to perpetrate any form of fraud, or software, film or music piracy.<br>
● using the internet to send offensive or harassing material to other users.<br>
● downloading commercial software or any copyrighted materials belonging to third parties, 
unless this download is covered or permitted under a commercial agreement or other such 
licence.<br>
● hacking into unauthorised areas.<br>
● publishing defamatory and/or knowingly false material about UBB, your colleagues and/or 
our customers on social networking sites, ‘blogs’ (online journals), ‘wikis’ and any online 
publishing format.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- 2. Literature review -->
## 2. Literature review
Digital investigation process models provide a structured approach to investigating digital crimes and 
incidents. The Digital Investigation Process Model (DIPM) developed by Quick, Choo, and Hock 
(2014) is a widely cited model that consists of four phases: identification, preservation, analysis, and 
reporting. Similarly, the Cyber Forensic Investigation Framework (CFIF) developed by Baryamureeba 
and Tushabe (2011) identifies five stages of the investigation process: identification, preservation, 
collection, analysis, and reporting. Another model, the Scientific Investigation Model (SIM) developed 
by Casey (2011), emphasizes the scientific approach to digital investigations and focuses on hypothesis 
testing, data collection, and analysis.<br>
The DIPM is a widely recognized model that proposes a six-step process for conducting digital 
investigations. These steps include identification, preservation, collection, analysis, presentation, and 
review. The CFIF, on the other hand, is a four-stage model that focuses on the identification, 
preservation, analysis, and reporting of digital evidence. The SIM, on the other hand, is a model that 
emphasizes scientific principles and proposes a four-stage process for conducting scientific 
investigations. These stages include hypothesis generation, data collection, analysis, and conclusion.

## 2.1 Points to prove

It is worth noting that while these models are essential in guiding the digital investigation process, there 
is no one-size-fits-all model for all investigations. The suitability of each model is dependent on the 
context of the investigation. The DIPM, for instance, is an ideal model for investigations that involve 
large volumes of data. However, it is not well suited for investigations that require a quick response. 
The CFIF, on the other hand, is ideal for investigations that require a quick response, such as cyber attacks. However, it does not provide guidance on the presentation and review of evidence. The SIM is 
well suited for scientific investigations that require a systematic and scientific approach.<br>
While digital investigation process models provide a useful framework for conducting investigations, 
it is important to critically evaluate their strengths and weaknesses. However, the CFIF also includes a 
stage for data collection, which is a crucial step that may be overlooked in other models. On the other 
hand, the SIM focuses heavily on the scientific approach, which may not be practical or feasible in all 
investigations.<br>
Additionally, it is important to consider the context in which these models are being used. For example, 
the DIPM and CFIF were developed for use in law enforcement investigations, while the SIM was 
designed for use in academic research. Therefore, it may be necessary to adapt these models to suit 
different contexts, such as corporate investigations or incident response in the private sector.<br>
Overall, digital investigation process models provide a useful starting point for conducting 
investigations, but it is important to use them critically and adapt them to suit the specific needs of each 
investigation.

## 2.2 references
According to Casey (2011), the Digital Investigation Process Model (DIPM) proposes a six-step process 
for conducting digital investigations.<br>
<b>Reference List:</b><br>
Casey, E. (2011). Digital Evidence and Computer Crime: Forensic Science, Computers, and the 
Internet. Academic Press.<br>
Baryamureeba, V., & Tushabe, F. (2011). Cyber forensic investigation framework. International Journal 
of Cyber-Security and Digital Forensics, 1(1), 23-35.<br>
Casey, E. (2011). Digital evidence and computer crime: forensic science, computers and the Internet. 
Academic Press.<br>
Quick, D., Choo, K. K. R., & Hock, G. C. (2014). Digital investigation process model. Digital 
Investigation, 11(4), 306-315.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- 3. Evidence File -->
## 3. Evidence File

## 3.1 Details of the Evidence File
On the "Autopy" Digital Forensics program, I find the entire directory tree and other files after 
exporting the given VM.
<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Run%20by%20autopsy.png">
</p>
## 3.2 Hash value of the Evidence File

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Hash%20value%20of%20vm.png">
</p>

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- 4. Artefacts -->

## 4. Analysis Process
## 4.1 Suspected user
On /home directory there have a user and the username is “enkidu”

<p align="center">
  <img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/user%20name.png">
  </p>
 
## 4.2 Suspicious Activity
In Archives-1([2016]) there have three suspicious E-Mail Messages which are come from “John 
Snow” to the local user. 
Email address: enjohnsnow2016@gmail.com

## 4.2.1 1st Suspicious mail
<p align="center">
  <img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Email%20of%20john%20snow%20to%20user.png">
  </p>
  
Here, it is clear that the suspect John Snow sent the local user some instructions for running the 
<b>"autoexec.bat"<b> file.<br>

## 4.2.2 Suspicious files
Additionally, in there locate the <b>"autoexec.bat"</b> file in the VM's <b>/home/Documents</b> directory.

  
  <p align="center">
  <img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/suspicious%20bat%20file.png">
  </p>
Three bat files are displayed here: <b>"autoexec.bat", "maker.bat" and "not.bat"</b>. The autoexec.bat and not.bat scripts are identical.

  <p align="center">
  <img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/script%20of%20that%20file.png">
  </p>
  <p align="center">
  <img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/script%20of%20not%20bat%20file%20as%20same%20auto.png">
  </p>
It is guaranteed that these files are run automatically after clicking them thanks to our analysis of the scripts. Furthermore, it will undermine the system.

## 4.2.3 Virustotal scan
Here, export these two bat files and do a virus check using the website "Virustotal".

 <p align="center">
<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/virus%20total%20scan%20autoexe.png">
</p>

<p align="center">
<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/virus%20total%20scan%20not.png">
</p>

The files "autoexec.bat" and "not.bat" are "Trojan" according to the virus total tool.


## 4.2.4 HybridAnalysis scan
Here also do a scan using "HybridAnalysis" another internet application. Additionally, they identify both files as malicious.

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Hybrid%20analysis.png">
</p>

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Hybrid%20analysis%20not.png">
</p>

## 4.2.5 2nd Suspicious mail

"John Snow" instructs the local user enkidu to use the VPN in this email.

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/Another%20email%20instruction.png">
</p>
<p align="center">

## 4.2.6 3rd Suspicious mail

Here, confirm that "John Snow" has instructed you in this email to use a VPN to get around the 
company's IDS.<br>
Here, the suspect also makes reference to the "TOR project" which is a VPN substitute. Thus, by starting this project, the local user is also able to go through the firewall and IDS of the corporation.<br>
The url of this tor project: https://www.torproject.org/

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/IDS%20bypass%20email.png">
</p>

## 4.2.6 3rd Suspicious Tor Project

Here, also find this torproject on <b>/home/enkidu/.tor-browser-en/INSTALL/Browser/profile.default/extension/tor-launcher@torproject.org.xpi</b>

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/torproject.png">
</p>
<p align="center">


## 4.3 Log files Analysis

There have some important log files in <b>/var/log/</b> directory.
<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/importent%20log%20file.png">
</p>

## 4.3.1 Evidence of launching tor project

After exporting all log files and after analyzing all logs, find proof of launching the tor project. And I found these evidence on Syslog file.


<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/user%20launch%20tor%20project.png">
</p>


<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/launch%20tor%20project%20from%20syslog.png">
</p>

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/tor%20project%20on%20tor%20log.png">
</p>

## 4.3.2 Evidence of Outside staff on the local Network

There also find out the reason for outside staff being accessed on the local network. And find it after analyzing the Syslog.

<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/For%20this%20connection%20outside.png">
</p>
Here is the status of the network, <b>“NetworkManager state is now CONNECTED_GLOBAL”</b>. So any staff outside can access the company’s network.

## 4.3.3 Evidence of Violating Acceptable internet use policy for UBB

Other suspicious activity which violates the “Acceptable internet use policy for UBB” or satisfies “Unacceptable behavior”.<br>

<b>Install fakeroot on provided VM by the local user:</b>


<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/install%20fakeroot.png">
</p>

<b>Establish a SSH connection:</b>


<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/ssh%20session.png">
</p>

## 4.4 Suspicious web history
Here, also find Suspicious web history where the user search for keylogger:
<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/suspicious%20web%20history.png">
</p>
<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/323a19ea0e2f1bd6b7c3826500f89b66.png">
</p>
<p align="center">

<img src="https://github.com/MD-SAJID-ICT/Malicious-Activity-Investigation-with-VM-Image/blob/master/images/71f5131284d26584e54bae026e9020d6.png">
</p>
 
 <!-- 5. The Toolkit -->
 ## 5. The Toolkit 
 


| toolkit   |                Notes                   |
| ----------| -------------------------------------- |
| Autopsy | Autopsy is a powerful and flexible digital forensics platform that provides a range of tools for investigating digital evidence. It is widely used in law enforcement, government, and corporate investigations, and its open-source nature makes it accessible to a wide range of users. Some of the key tools available in Autopsy include:<br>● Forensic Imaging<br>● Data Carving<br>● Keyword Search<br>● Timeline Analysis<br>● Hash Filtering<br>● Metadata Extraction<br>● Reporting |
| VirusTotal | VirusTotal is a free online service that provides a suite of tools for analyzing and investigating potentially malicious files and URLs. Some of the key tools available in VirusTotal include:<br>● File Scanning<br>● URL Scanning<br>● Behavior Analysis<br>● VirusTotal Graph<br>● Search<br>● Community Tools |
| HybridAnalysis | Hybrid Analysis is a free online service that provides a suite of tools for analyzing and investigating potentially malicious files and URLs. Some of the key tools available in Hybrid Analysis include:<br>● Automated Analysis<br>● Sandbox Analysis<br>● Threat Intelligence<br>● Threat Hunting<br>● Reporting<br>● Integrations |
| Nano  | Nano is a text editor that is widely used on Unix-based operating systems. Some of the key tools available in Nano include:<br>● Basic Text Editing<br>● Syntax Highlighting<br>● File Management<br>● Search and Replace<br>● Multi-buffer Editing<br>● Keyboard Shortcuts |
| Grep | Nano is a text editor that is widely used on Unix-based operating systems. Some of the key tools available in Nano include:<br>● Basic Text Editing<br>● Syntax Highlighting<br>● File Management<br>● Search and Replace<br>● Multi-buffer Editing<br>● Keyboard Shortcuts |
| Kali Linux | Kali Linux is a popular Linux distribution that is widely used for penetration testing and digital forensics. Some of the key features of Kali Linux include:<br>● Security Tools<br>● Live Booting<br>● Customizability<br>● Community Support<br>● Documentation<br>● Virtualization Support |

<p align="center"> 
Table of Toolkits
  </p>
  
  
 <!-- 6. Personal Reflection -->
 ## 6. Personal Reflection
 
 ## 6.1 Student 
 
 <b>6.1.1 Reflection</b><br><br>
Child Protection Policy is very need in this time. Digital crime is the most common factors for
this time & child can easily the target by the social media. <br>
 
 <b>6.1.2 Strengths/major contributions to the group</b><br><br>
 
 Completed the full Project on Child Protection Digital Crime Scenario make and Investigation on this. <br>
 
 <b>6.1.3 What you found enjoyable</b><br><br>
 
 Data Encryption for Data Hiding. Most of Steganography Techniques Like morse and the other section is sign language.<br>
 
 <b>6.1.4 What was challenging</b><br><br>
 
 File Signeture Mismathce checking and Correction. <br>
 
 <b>6.1.5 Technical challenges and outcomes</b><br><br>
 
 Encase Forensics Imager is not free version, is premium. I am use Access Data FTK Imager for create the crime scenario evidence .E01 file. That was techniqal challenge for me. The outcome is it can be done easily by Encase Forensics but that is not available in every section like Not Open Source. So Its need to be Open source file. <br>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Tareq Raihan - [@My_Linkedin](https://www.linkedin.com/in/tareqraihan926/) - tareqhasan926ice@gmail.com

Project Link: [https://github.com/tareqraihan926/Digital-Forensics-Cyber-Crime-Investigations](https://github.com/tareqraihan926/Digital-Forensics-Cyber-Crime-Investigations)

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/tareqraihan926
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
