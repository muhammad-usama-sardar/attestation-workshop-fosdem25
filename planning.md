**Room capacity:** 30 (first-come-first-serve)

Note: 5 seats are reserved for university hosts. So anyone after #25 will be on waiting list.

## Confirmed Participants 
(Please add your name at the **end** of this list if you are surely attending **in-person**, whether presenting or not)
1. Muhammad Usama Sardar
2. Thomas Fossati
3. Ionut Mihalcea
4. Mike Bursell
5. Paul Howard
6. Yogesh Deshpande
7. Jun Zhang
8. Houda Labiod
9. Michael Richardson
10. Ian Oliver 
11. Hannes Tschofenig
12. Kai Jansen
13. Mathieu Poirier
14. Henk Birkholz
15. Mathias Brossard
16. Thore Sommer
17. Jean Snyman
18. Anderson Sasaki
19. Michael Prantl
20. Ijlal Loutfi
21. Gilang Hamidy
22. Wiktor Kwapisiewicz
23. Cédrick Austa
24. Navid Ladner
25. Jan Tobias Muehlberg
26. Jason Kayembe
27. Aurélien Chassagne
28. Oscar Van Slijpe
29. Anastassios Nanos
30. Tom Godden
31. Apolline Zehner
32. Tiago Martins


## Tentative Participants
(Please add your name at the **end** of this list if you are planning to attend **in-person** but not sure yet)
1. Mike Schwartz
2. Martina Kannen
3. Lena Oden
4. Sam Van de Velde
    
## Online Participants
(Please add your name at the **end** of this list if you are planning to attend **online**)
1. Yuxuan Song
2. Dionna Glaze (starting from 19:00 for the endorsement API discussion)

## Agenda
Please add your name and topic in the table below if you would like to present. (You may add at the end of the table, and we will see where it fits in the agenda)

| Name  | Title | Relevant material | Specs | Implementation | Duration (min) |
|--|--|--|--|--|--|
| Muhammad Usama Sardar | Welcome |  |  |  | 10 |
| Hannes Tschofenig | IETF Standards Update | Latest news from the standardization world  | IETF RATS/LAMPS/WIMSE |  | 30 |
| Paul Howard | Endorsement and RV Distribution: Interaction Model, API and Prototyping | [Slides](https://github.com/CCC-Attestation/meetings/blob/main/materials/PaulHoward_EndorsementDistribution_Sept2024.pdf) |  | [Veraison](https://github.com/veraison/services) | 20 |
| Muhammad Usama Sardar | Backdoors in RFC9334 | [Draft (in progress)](https://muhammad-usama-sardar.github.io/rats-unprotected-evidence/draft-usama-rats-unprotected-evidence.html) |  |  | 10 |
| Ian Oliver | Forensics and Attestation | abstract[^1] |  |  | 30 + live demo |
| Thore Sommer | TPM based Remote Attestation: Pitfalls and Lessons Learned |  |  | [Keylime](https://keylime.dev) | 15 |
| Anderson Sasaki | Expanding Keylime: Attestation for Trusted Execution Environments | [Abstract](https://github.com/ansasaki/fosdem2025-talk-proposal) | [Enhancement Proposal](https://github.com/keylime/enhancements/pull/108) | [Changes to coconut-svsm](https://github.com/coconut-svsm/svsm/pull/528) | 20 |
| Muhammad Usama Sardar | Attested TLS and Formalization | [Paper](https://www.researchgate.net/publication/385384309_Towards_Validation_of_TLS_13_Formal_Model_and_Vulnerabilities_in_Intel's_RA-TLS_Protocol); [formalization](https://github.com/CCC-Attestation/formal-spec-TEE); [slides etc.](https://github.com/CCC-Attestation/formal-spec-KBS) | [Specs](https://datatracker.ietf.org/doc/draft-fossati-tls-attestation/) | [Implementation](https://github.com/ccc-attestation/attested-tls-poc) | 30 |
| Anastassios Nanos | Secure Cloud-Native IoT: Onboarding, OTA Update, and Device Repurposing with OpenDICE in k8s | Presentation / Discussion about IoT application attestation |  |  | 20 |
| Yuxuan SONG | Remote Attestation for Constrained IoT Use Cases | [IETF draft](https://datatracker.ietf.org/doc/draft-song-lake-ra/) | | [Attester(DotBot running on nRF5340)](https://github.com/ysong02/DotBot-firmware/blob/only-attestation-Nov/projects/03app_dotbot/03app_dotbot.c) , [Relying Party](https://github.com/ysong02/PyDotBot/tree/demo-remote-attestation), [Verifier](https://github.com/ysong02/dotbot-authority/tree/attestation-demo-video) | 15 |




[^1]: Remote attestation provides us with a demonstration that a given system is in a given state - ideally one where the integrity of the system is according to known good values.
Keeping a history of claims, results and decisions of a system over a longer period of time provides vital information about how a system is evolving over firmware and software changes, as well as potential hardware changes. Utilising this information can provide evidence of unwanted and unexpected changes to a system.
We present here a tool for attestation and forensics, through a simple example. Additionally we provide a case study from a potential firmware CVE and finally provide a case based upon Open Radio Access Network hardware.
