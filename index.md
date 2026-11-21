---
title: Cybersecurity Portfolio
---

## About Me

I am a cybersecurity student building practical skills in network security and authorized security testing. I am especially interested in understanding how systems are exposed on a network and how defenders can reduce that exposure. Through my coursework, I have set up an isolated virtual lab with Kali Linux and Metasploitable 2, used host-only networking to keep practice contained, and used ping and Nmap for host discovery and service-version identification. These exercises have helped me connect technical tools with defensive questions and better understand how scan results can guide security improvements. I aim to keep learning through structured labs, careful note-taking, and evidence-based project work. I value clear scope, safe testing, and honest reporting, and I am developing my ability to explain technical findings in a clear and useful way.

## Technical Skills

| Skill | Level | Project evidence |
|---|---|---|
| Virtual lab setup and snapshots with UTM | Beginner | [Isolated Virtual Lab Setup](projects/virtual-lab-setup/README.md) |
| Kali Linux command-line basics | Beginner | [Nmap Service Enumeration](projects/nmap-service-enumeration/README.md) |
| Nmap host discovery and service-version scanning | Beginner | [Nmap Service Enumeration](projects/nmap-service-enumeration/README.md) |
| Documenting scan findings and defensive notes | Beginner | [Nmap Service Enumeration](projects/nmap-service-enumeration/README.md) |

## Certifications and Training

### Certifications

No cybersecurity certifications earned yet.

### Training

- Cybersecurity coursework: Set up an isolated virtual lab using UTM, Kali Linux, and Metasploitable 2.
- Hands-on lab: Used a host-only network, checked connectivity, and practised Nmap host discovery and service-version scanning in the lab.

## Projects

### Isolated Virtual Lab Setup

Set up a controlled virtual lab with separate Kali Linux and Metasploitable 2 virtual machines. Created clean snapshots so the lab could be restored for later exercises.

[View project details](projects/virtual-lab-setup/README.md)

### Nmap Service Enumeration

Used a host-only network to check connectivity, discover live lab hosts, and identify services and versions on the target with Nmap.

[View project details](projects/nmap-service-enumeration/README.md)

## Learning Journey

These two labs helped me see that cybersecurity practice depends on a safe, repeatable setup before any testing begins. In Lab 1, I used UTM to run Kali Linux as the attacker VM and Metasploitable 2 as the target. I created a fresh-install snapshot for each VM so I could return to a known starting point after later exercises. Keeping the machines separate and preserving clean snapshots gave me a controlled way to practise without involving systems outside the lab. I also learned that preparing the environment is itself a security task: a test is only responsible when its scope and isolation are clear.

Lab 2 built on that setup. I used a host-only network, checked connectivity with ping, used `nmap -sn` to find live hosts, then used `nmap -sV` to identify services and reported versions on the target. The commands answered different questions: ping checked reachability, `-sn` checked which hosts were online, and `-sV` added service and version information. The exercise found two live hosts, my Kali VM and the Metasploitable target. My notes recorded FTP on port 21 and SSH on port 22 as examples. This helped me connect an inventory of services to defensive questions about whether each service is needed and how it should be maintained.

While preparing this portfolio, I noticed that my original Lab 2 findings table was incomplete. It listed FTP and SSH but did not contain the two risk notes requested by the lab. I compared my table with the scan screenshot and the submission checklist, then added two defensive notes to the project write-up. This showed me that seeing command output is not the same as finishing an analysis. I need to record what the result means and suggest a proportionate defense, while avoiding unsupported claims based only on a version number. In future labs, I will check the report against the task requirements before considering it finished.

One area I am still developing is interpreting service-version scan results. Nmap can identify a service and version, but deciding what to prioritize requires more context: whether the service is exposed beyond the lab, whether it is necessary, and whether the installed version is supported. I want more practice turning scan output into a concise, evidence-based risk explanation and a practical mitigation. I also need to improve my Linux command-line fluency so I can work through scan output and keep clean notes efficiently.

As a proposed next goal, by 31 January 2027 I will complete three additional authorized network-security labs in isolated environments. For each lab, I will record the scope, environment, main steps, results, and one defensive recommendation, and save at least one sanitized piece of evidence. I will measure progress by having three complete write-ups and checking that another student could follow my notes to understand what I tested and why. This goal is specific and manageable, and it will help me strengthen both technical practice and communication.

Overall, the labs have given me a first step in building a responsible workflow: establish a bounded environment, identify the target, collect evidence, interpret results cautiously, and present recommendations clearly. I want to keep that workflow as I move to more advanced topics.

## Career Objective

My career objective is to begin in a junior cybersecurity analyst role, such as a SOC analyst, where I can help monitor systems, review security alerts, and support practical risk reduction. My coursework and lab exercises have introduced me to isolated virtual environments, basic network discovery, and service-version scanning. I want to build these foundations into stronger defensive analysis and incident response skills.

My next steps are to strengthen my networking and Linux fundamentals through authorized labs, practise analysing basic logs and triaging security alerts, and develop a portfolio of clear, sanitised project reports. I will also research an entry-level certification that matches the roles I hope to apply for and make a preparation plan. I will measure my progress by completing several documented labs and being able to explain the scope, evidence, and defensive recommendations for each.

## Contact Information

- GitHub: [25111729](https://github.com/25111729)
- LinkedIn: [Tao Ding](https://www.linkedin.com/in/tao-ding-6575ab451/)
