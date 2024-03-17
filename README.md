# First Principle in Cyber Security

In the past 20 years, I have worked in the information security industry. In this 20 years, numerous theories, approaches, and solutions have been developed, all aimed at addressing problems in cybersecurity. However, a question often arises in my mind: Can these theories or principles truly address all security issues?

# First Principle
First principles refer to the fundamental concepts or assumptions upon which a theory, system, or understanding is based. It is a foundational approach to reasoning and problem-solving, where complex ideas are broken down into their most basic elements.

Elon Musk is known for his application of first principles thinking in various areas of his work. One notable example is his approach to the cost and efficiency of space travel, which led to the founding of SpaceX.  When Musk first looked at the cost of launching payloads into space, he realized that it was exorbitantly expensive due to the reliance on traditional aerospace manufacturing and launch practices. Rather than accepting these costs as fixed, he decided to question the underlying assumptions and break down the problem into its fundamental elements.

Musk identified two key cost drivers in the aerospace industry: the high prices of rocket components and the expendable nature of rockets. Instead of accepting the prevailing industry practice of building new rockets for each launch and discarding them after use, Musk applied first principles thinking to find a more cost-effective solution.  He started by examining the cost of materials and components, realizing that most of them were relatively inexpensive. By manufacturing key rocket components, such as the engines, in-house and seeking more affordable materials, he was able to significantly reduce costs compared to traditional suppliers.

However, the biggest breakthrough came when Musk challenged the assumption that rockets had to be expendable. Instead of accepting that rockets should be discarded after each launch, he set out to develop a reusable rocket system. This involved designing rockets that could land vertically after delivering their payloads to orbit, allowing them to be refurbished and flown again.

By applying first principles thinking to the problems of cost and reusability, Elon Musk and SpaceX were able to revolutionize the space industry. Today, SpaceX's Falcon 9 rockets are routinely reused, resulting in significant cost savings and making space travel more accessible.  This example showcases how Musk's ability to question assumptions and break down complex problems into their fundamental components allowed him to challenge the status quo and develop innovative solutions.

# Cyber Security
Then, what is the first principle or the most basic elements in Cyber security?  Before finding a definition of cyber security, it is important to figure out the **core problem** that we need to solve in cybersecurity.  Practitioners in information security are constantly working to address emerging threats and challenges.  But the fundumental problem should seldom change.

In Rick Howards Cybersecurity First Principles, Rick lays out a notional roadmap for cybersecurity’s first principle, which can be seen at the foundation of the image below.

![4782f6cd-81b3-407c-af9a-c77c4f6a894c_1340x1308](https://github.com/justinlaw360/firstprinciple/assets/4946026/41780960-06eb-4b06-9b77-b7ac03f67f52)
<kbd>Diagram from: Cybersecurity First Principles (Mar 2023, Rick Howards)<kbd>

This means that cybersecurity’s first principle is to “Reduce the Probability of **Material Impact**”.

# Cyber Security Incidents Analysis

Let's zoom in what is the material impact.  I sort out the most citrical security incidents in each month of 2023 as table below.  Most belong to the impact of data leakage due to exfiltration by hackers.

|Month in 2023|Victim Company                                       |Incident Description                                                                                                         |Data involved    |Root Cause      |Material Impact|
|-------------|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-----------------|----------------|---------------|
|December     |Real Estate Wealth Network                           |Unprotected database exposing property ownership records                                                                     |personal data    |Exfiltration    |Data Disclosure|
|December     |TuneFab                                              |Exposed user data from music conversion platform                                                                             |personal data    |misconfiguration|Data Disclosure|
|December     |Dori Media Group                                     |Alleged exfiltration of over 100 TB of data                                                                                  |company data     |misconfiguration|Data Disclosure|
|November     |Kid Security                                         |Parental control app exposed user activity logs online                                                                       |sensitive records|misconfiguration|Data Disclosure|
|November     |SAP SE Bulgaria                                      |Exposed Kubernetes Secrets of multiple organizations                                                                         |sensitive records|misconfiguration|Data Disclosure|
|November     |TmaxSoft                                             |Leaked sensitive records via an IT company's dashboard                                                                       |sensitive records|misconfiguration|Data Disclosure|
|October      |ICMR Indian Council of Medical Research              |Sale of personal data from Covid-testing database                                                                            |personal data    |misconfiguration|Data Disclosure|
|October      |23andMe                                              |Credential stuffing attack resulting in leaked genetic data                                                                  |personal data    |Exfiltration    |Data Disclosure|
|October      |Redcliffe Labs                                       |Unprotected medical database with potential exfiltration                                                                     |sensitive records|misconfiguration|Data Disclosure|
|September    |DarkBeam                                             |Unprotected records from previous data breaches exposed                                                                      |sensitive records|Exfiltration    |Data Disclosure|
|September    |MOVEit                                               |Ongoing breach affecting multiple organizations                                                                              |sensitive records|Exfiltration    |Data Disclosure|
|August       |MOVEit Transfer                                      |Breach of UK Electoral Commission's systems                                                                                  |company data     |Exfiltration    |Data Disclosure|
|August       |UK Electoral Commission                              |"Complex cyber-attack" accessing UK electoral registers                                                                      |personal data    |Exfiltration    |Data Disclosure|
|August       |P繫le emploi                                          |Fallout from MOVEit breach, breached records                                                                                 |sensitive records|Exfiltration    |Data Disclosure|
|August       |Various organizations affected by MOVEit             |Multiple organizations affected by the MOVEit breach                                                                         |sensitive records|Exfiltration    |Data Disclosure|
|August       |University of Minnesota                              |Attacker accessed systems and exfiltrated personal data                                                                      |personal data    |Exfiltration    |Data Disclosure|
|July         |Tigo                                                 |Personal data of more than 700,000 users leaked online                                                                       |personal data    |misconfiguration|Data Disclosure|
|July         |Indonesian Immigration Directorate General           |Hacktivist gained unauthorized access, leaked passport data                                                                  |personal data    |Exfiltration    |Data Disclosure|
|July         |Teachers Insurance and Annuity Association of America|Affected by MOVEit vulnerability, client data compromised                                                                    |personal data    |Exfiltration    |Data Disclosure|
|June         |Oregon Department of Motor Vehicles                  |MOVEit software vulnerability, driver's license information stolen                                                           |personal data    |Exfiltration    |Data Disclosure|
|June         |Louisiana Department of Motor Vehicles               |MOVEit software vulnerability, driver's license information stolen                                                           |personal data    |Exfiltration    |Data Disclosure|
|June         |Genworth Financial                                   |Affected by MOVEit breach, customer personal data stolen                                                                     |personal data    |Exfiltration    |Data Disclosure|
|June         |Wilton Reassurance                                   |Affected by MOVEit breach, customer data compromised                                                                         |personal data    |Exfiltration    |Data Disclosure|
|May          |Luxottica                                            |Stolen data containing 305 lines, including 74.4 million unique email addresses and 2.6 million unique domain email addresses|personal data    |Exfiltration    |Data Disclosure|
|May          |MCNA Insurance                                       |Ransomware attack resulting in the compromise of 8,923,662 people's information                                              |personal data    |Exfiltration    |Data Disclosure|
|May          |PharMerica                                           |Data breach compromising personal information of 5.8 million patients                                                        |personal data    |Exfiltration    |Data Disclosure|
|April        |Shields Health Care Group                            |Unauthorized access led to the theft of personal data of 2.3 million individuals                                             |personal data    |Exfiltration    |Data Disclosure|
|April        |NCB Management                                       |Cyber criminal stole almost one million financial records                                                                    |sensitive records|Exfiltration    |Data Disclosure|
|April        |Kodi                                                 |Unauthorised actor compromised the MyBB forum database, affecting 400,635 users                                              |personal data    |Exfiltration    |Data Disclosure|
|March        |Latitude Financial                                   |Data breach resulting in the compromise of more than 14 million records                                                      |sensitive records|Exfiltration    |Data Disclosure|
|March        |GoAnywhere                                           |Exploitation of a vulnerability affecting multiple organizations                                                             |sensitive records|Exfiltration    |Data Disclosure|
|March        |AT&T                                                 |Data breach exposing personal data of approximately 9 million customers                                                      |personal data    |Exfiltration    |Data Disclosure|
|February     |PeopleConnect                                        |Data breach from a leaked backup database affecting 20 million customers                                                     |personal data    |misconfiguration|Data Disclosure|
|February     |Elevel                                               |Data breach resulting in the leakage of 1.1TB of personal data                                                               |personal data    |misconfiguration|Data Disclosure|
|February     |CentraState Medical Center                           |Ransomware attack compromising sensitive personal data of 617,000 patients                                                   |personal data    |Ransomware      |Data Disclosure|
|January      |Twitter                                              |Leak of more than 220 million users' email addresses, posing privacy risks                                                   |personal data    |Exfiltration    |Data Disclosure|
|January      |T-Mobile                                             |Second data breach of the year, affecting 836 customers with theft of personal details                                       |personal data    |Exfiltration    |Data Disclosure|
|January      |JD Sports                                            |Leaked personal information of 10 million customers, including names, addresses, phone numbers, and payment details          |personal data    |Exfiltration    |Data Disclosure|

# Material Impacts to Security Area
We further think about the material impact, and map into IT Security area.
|Material Impact|Security Area                                        |
|---------------|-----------------------------------------------------|
|Data Disclosure|Authentication                                       |
|Data Disclosure|Authorization                                        |
|Data Disclosure|Business Logic                                       |
|Data Disclosure|Cryptography                                         |
|Data Disclosure|Data Protection                                      |
|Data Disclosure|Data Validation                                      |
|Data Disclosure|Database                                             |
|Data Disclosure|Error Handling                                       |
|Data Disclosure|Logging and Monitoring                               |
|Data Disclosure|Network Communication                                |
|Data Disclosure|Operating System                                     |
|Data Disclosure|Session Management                                   |
|Data Disclosure|Third-Party Integrations                             |
|Data Disclosure|Third-Party Libraries                                |
|Data Disclosure|User Authentication                                  |
|Data Disclosure|Web Application                                      |
|Data Integrity |Authorization                                        |
|Data Integrity |Network Communication                                |
|Service Availability|Authentication                                       |
|Service Availability|Data Validation                                      |
|Service Availability|Database                                             |
|Service Availability|Network Communication                                |
|Service Availability|Third-Party Libraries                                |


# Cyber Security Team
![IS Team](https://github.com/justinlaw360/firstprinciple/assets/4946026/e1690335-44bc-4fd7-9e22-321ff50c5659)
