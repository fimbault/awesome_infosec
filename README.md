# awesome infosec 

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A curated list of awesome information security resources, inspired by the awesome-* trend on GitHub. It is mainly for my own use or for my students, but happy to share if that can help other people too.
I intend to publish the course content too, someday. 

I only include resources which I have really used in my courses (so that I can comment on them, sometimes with a larger critic available as a blog post). The intent is not a thorough listing (not even close), but a level entry into the most relevant sources to begin with. Most of the resources are in English. 

I exclude resources which cannot be accessed publicly or that are vendor oriented (when possible; sometimes I refer to a sponsored link which makes the content available for free). I try to favor opensource projects when possible.

This list will be updated on a regular basis and organized by type of content. To know when resources where last retrieved, see the git commit date.

## Table of Contents

1. [Videos](#videos)
2. [Literature](#litterature)
3. [Technical books](#technical-books)
4. [Academic work](#academic-work)
5. [Reports](#reports)
6. [Methods](#methods)
7. [Web resources](#web-resources)

## Videos

- J. Corman, *Wh0 K1ll3d D@v3y M00r3?*, 2018, Available at https://www.youtube.com/watch?v=e92YcLaL7bg <br>
This video explains why cyber attacks may kill someone. 

- C. Stoll, *The KGB, The Computer and Me*, Available at https://www.youtube.com/watch?v=EcKxaq1FTac <br>
The cuckoo's story in 1h (if you don't want to read the book, also listed). 

- Norsk Hydro, *Why Hydro chose to be transparent during cyber-attack*, Available at https://news.microsoft.com/transform/hackers-hit-norsk-hydro-ransomware-company-responded-transparency/ <br>
This video explains the challenge faced by a large company (an energy producer) and how the managed the crisis. 

- A. Shostack, *Threat Modeling Lessons from Star Wars*, 2019, Available at https://www.youtube.com/watch?v=nd02oPnMdR4 <br>
An interesting talk on threat modeling techniques. 

- Tomorrow Unlocked, *Wannacry: The Marcus Hutchins Story*, 2019, Available at https://www.youtube.com/watch?v=vveLaA-z3-o <br>
The wannacry ransomware spread, until some genius hacker, called Marcus Hutchins, found a way to stop it (see the full story at https://www.wired.com/story/confessions-marcus-hutchins-hacker-who-saved-the-internet).


## Litterature

- D. Buchanan, *The Hacker and the State: Cyber Attacks and the New Normal of Geopolitics*, Harvard University Press, 2020 <br>An account of state sponsored attacks over the last decade.
- A. Greenberd, *Sandworm: A New Era of Cyberwar and the Hunt for the Kremlin's Most Dangerous Hackers*, Doubleday, 2019 <br>
Attribution to specific criminal groups is a difficult game, but this is a documented essay on attacks perpetrated by Russian hackers in 2017 against Ukraine, which demonstrate the potential massive impact of cyber attacks.
- K. Mitnick, W.L. Simon, *Ghost in the Wires: My Adventures as the World's Most Wanted Hacker*, Back Bay Books, 2012<br>
The real story of hacker Kevin Mitnick (in the 90's). Great resource to understand why people hack and what social engineering is about.
- D.E. Sanger, *The Perfect Weapon: War, Sabotage, and Fear in the Cyber Age*, Broadway Books, 2018 <br>
An essay about the US policy (or lack of) in the cyber realm, and how other nations (Russia, China, North Korea) may use cyber as a stealthier weapon. 
- C. Stoll, *The Cuckoo's Egg: Tracking a Spy Through the Maze of Computer Espionage*, Pocket Books, 2005<br>
A detective like story to identify who a hacker named Hunter is (in the 80's). The author invented many of the techniques still used today for attribution. See also the video section from the same author.
- K. Zetter, *Countdown to Zero Day: Stuxnet and the Launch of the World's First Digital Weapon*, Crown, 2014 <br>
The story of the Stuxnet malware against the Iranian nuclear installations. 


## Technical books

- D. Calavera, L. Fontana, *Linux observability with BPF*, 2019. Available at https://sysdig.com/resources/papers/linux-observability-with-bpf/ <br>
eBPF is a new way to instrument the linux kernel, and there aren't so many resources yet. This book is a bit hard to follow for the non-expert. Yet to understand why it's important, see for instance https://cilium.io/blog/2019/11/19/announcing-hubble (an opensource project).
- C. Dotson, *Practical Cloud Security*, 2019, Available at https://gravitational.com/resources/guides/practical-cloud-security/<br>
A well-written description of security in a cloud native world. 

## Academic work

- S. Cartwright, J.H. Castro, A. Cartwright, *To pay or not: game theoretic models of ransomware*, Journal of cybersecurity, 2019, doi: 10.1093/cybsec/tyz009 <br>
This document provides an economic study of attacker-defender behavior, which is valid in most cases (except in state sponsored cyberwars). 
- L. Rocher, J.M. Hendrickx, Y.A. Montjoye, *Estimating the success of re-identifications in incomplete datasets using generative models*, 2019, https://www.nature.com/articles/s41467-019-10933-3 <br>This article shows why anonymization techniques are often weak against reconstruction. 
- S. Romanosky, *Examining the costs and causes of cyber
incidents*, Journal of cybersecurity, 2016, doi:10.1093/cybsec/tyw001 <br>
This article provides interesting statistics on cyber crime.
- S. Romanosky, L. Ablon, A. Kuehn, T. Jones, *Content analysis of cyber insurance policies: how do carriers price cyber risk?*, 2019, Journal of cybersecurity, doi: 10.1093/cybsec/tyz002 <br>
This article is one of the best documented when it comes to cyber insurance policies (at least for the US, the largest market by far). 
- J.M. Spring, J. Fallon, A. Galyardt, A. Horneman, L. Metcalf, E. Stoner, *Machine learning in cybersecurity: a guide*, Technical report, Carnegie Mellon University, 2019 <br>
This article explains the pitfalls one may encounter with machine learning. Some are not specific to the field, but the interesting part is on what an attacker may try to fool your detection patterns. 
- A. Umar, *Memory security in go*, Available at https://spacetime.dev/memory-security-go <br>
This document explains why it is challenging to implement memory protection with a garbage collected language, and how you can work around this. There's a framework called memguard that can serve as a reference implementation (but not for production use). 

## Reports

* Booz Allen, *The logic behind Russian military cyber operations*, 2020, Available at https://www.boozallen.com/c/insight/publication/the-logic-behind-russian-military-cyber-operations.html <br>An analysis of 200+ past GRU cyber-attacks and their correlation to principles described in Russian military doctrine.
* IBM Security, *Cost of a Data Breach Report*, 2019, Available at https://www.ibm.com/security/data-breach <br>
  Some updated statistics, relevant for large organisations (see SystemX for smaller organisations). 
* Snyk, *The state of JavaScript frameworks security report*, 2019, Available at https://snyk.io/blog/javascript-frameworks-security-report-2019/ <br>
  A review of security in the javascript and npm ecosystem.

## Methods

- ANSSI, *Ebios risk manager*, 2019, Available at https://www.ssi.gouv.fr/en/guide/ebios-risk-manager-the-method/ <br>
  The method used by the French cyber agency to manage cyber risks. 
- W. Dougherty, P. Curry, *Includes no dirt*, Omada, 2019, Available at https://www.omadahealth.com/news/includes-no-dirt-a-practical-threat-modeling-approach-for-digital-healthcare-and-beyond <br>
  A new framework to threat model your applications, for security and privacy. Designed for healthcare but applicable in a variety of scenarios (just need to change the C = Clinical Error => I suggest C = Correct application of business standards). See also the work of A. Shostack.
- MITRE, *The att&ck framework*, Available at https://attack.mitre.org/ <br>
  A knowledge base on the various attacks (the kill chain).

## Web resources

- Bloomberg, *The big hack*, Available at https://www.bloomberg.com/news/features/2018-10-04/the-big-hack-how-china-used-a-tiny-chip-to-infiltrate-america-s-top-companies <br>An investigative story about hardware breaches.
- J. Oppenheimer, *My Favorite Security Quotes*, Available at https://johnopdenakker.com/my-favorite-security-quotes <br> Words for the wise, John also provides a nice newsletter.
- RSA, *Security & Risk: How to Talk Digital Risk with The Board*, 2019, Available at https://www.rsa.com/content/dam/en/analyst-report/gartner-how-to-talk-digital-risk-to-the-board.pdf <br>
A high level view for decision makers who aren't versed in infosec. 
- Signal Sciences, *The Developer’s Guide to Building a Security Program*, 2019, Available at https://info.signalsciences.com/developers-guide-building-security-program <br>
Practical advice for devs that want to secure their apps (from the point of view of a WAF vendor). 
- SystemX, *Le coût additionné des attaques par cryptovirus touchant les PME françaises s’élève à plus de 700 millions d’euros par an* (in <u>French</u>, but I put it here because it provides unusual insights), Available at https://www.irt-systemx.fr/le-cout-additionne-des-attaques-par-cryptovirus-touchant-les-pme-francaises-seleve-a-plus-de-700-millions-deuros-par-an/ <br>
One of the few resources that describe the situation for smaller companies. On average the cost is small (around 10k euros for a SME, which was unexpected) and the frequency is 2 to 5%. For ransomware attacks, the total cost of recovery (when possible) is 25 times the cost asked by thieves. This actually means the risk is low, but SME really need to invest in backup strategies. One other interesting fact is that in France, only 1.24% of companies are cyber insured for a total market value of 28 million euros (the market barely exists).
- K. Waldron, *Resources for measuring cybersecurity*, 2019, Available at https://www.rstreet.org/issue/national-security-cybersecurity/ <br>
A list of resources that you might find useful. 


## License

![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
