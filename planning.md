**Room capacity:** 30 (first-come-first-serve)

## Confirmed Participants
If you are not attending in-person due to any reason, please remove your name from this list, so that people in waiting list can be accommodated. Thanks!
1. Muhammad Usama Sardar
2. Thomas Fossati
3. Ionut Mihalcea
4. Mike Bursell
5. Paul Howard
6. Yogesh Deshpande
7. Pavel Nikonorov
8. Michael Richardson
9. Ian Oliver
10. Hannes Tschofenig
11. Andrew Campbell
12. Mathieu Poirier
13. Henk Birkholz
14. Mathias Brossard
15. Thore Sommer
16. Jean Snyman
17. Anderson Sasaki
18. Michael Prantl
19. Ijlal Loutfi
20. Gilang Hamidy
21. Wiktor Kwapisiewicz
22. Cédrick Austa
23. Navid Ladner
24. Jan Tobias Muehlberg
25. Jason Kayembe
26. Aurélien Chassagne
27. Oscar Van Slijpe
28. Anastassios Nanos
29. Apolline Zehner

## Waiting List 
If a spot becomes available, we will move your name to the confirmed participants. You are very welcome to join online. 
1. Tiago Martins
2. Ricardo Seromenho
3. Freddie Woodruff
4. Jagannathan Raman
5. Chris A. Iradukunda


## Tentative Participants
Please add your name at the **end** of this list if you are planning to attend **in-person** but not sure yet.
1. Mike Schwartz
2. Martina Kannen
3. Lena Oden
4. Sam Van de Velde
5. Marcin Cieślak
6. Kai Jansen
    
## Online Participants
Please add your name at the **end** of this list if you are planning to attend **online**. Also, follow instructions [here](https://github.com/muhammad-usama-sardar/attestation-workshop-fosdem25?tab=readme-ov-file#how-can-i-register-to-attend-online) to get meeting link.
1. ~~Yuxuan Song~~ (unable to attend)
2. Dionna Glaze (starting from 19:00 for the endorsement API discussion)
3. Giri Mandyam (Pacific time zone)
4. Eduardo Cabre (Endorsement API)
5. Marc-André Lureau
6. Carsten Weinhold
7. Venkat Nilesh Dadi
8. Georges Papadopoulos
9. Jun Zhang
10. Ahmad Khalifeh (Central time zone)
11. Tom Godden

## Agenda
Please add your name and topic in the table below if you would like to present. (You may add at the end of the table, and we will see where it fits in the agenda)

**Format**: We will have discussions during the talks. Hence, the starting time of a specific talk cannot be pre-determined.  

| Name  | Title | Relevant material | Specs | Implementation | Duration (min) |
|--|--|--|--|--|--|
| Muhammad Usama Sardar | Welcome |  |  |  | 15 |
| Hannes Tschofenig | IETF Standards Update | Latest news from the standardization world  | IETF RATS/LAMPS/WIMSE |  | 30 |
| Muhammad Usama Sardar | Backdoors in RFC9334 | [Draft (in progress)](https://muhammad-usama-sardar.github.io/rats-unprotected-evidence/draft-usama-rats-unprotected-evidence.html) |  |  | 10 |
| Ian Oliver | Forensics and Attestation | abstract[^1] |  |  | 30 + live demo |
| Thore Sommer | TPM based Remote Attestation: Pitfalls and Lessons Learned |  |  | [Keylime](https://keylime.dev) | 15 |
| Anderson Sasaki | Expanding Keylime: Attestation for Trusted Execution Environments | [Abstract](https://github.com/ansasaki/fosdem2025-talk-proposal) | [Enhancement Proposal](https://github.com/keylime/enhancements/pull/108) | [Changes to coconut-svsm](https://github.com/coconut-svsm/svsm/pull/528) | 20 |
| Pavel Nikonorov | Attested TLS: Inferring Trust in Post-Attestation Integrity with Linux Security Modules | [Demo](https://github.com/elixir-cloud-aai/biohackeu24-issues/issues/17) |  |  | 20 |
| Muhammad Usama Sardar | Formalization of Attested TLS  | [Paper](https://www.researchgate.net/publication/385384309_Towards_Validation_of_TLS_13_Formal_Model_and_Vulnerabilities_in_Intel's_RA-TLS_Protocol); [formalization](https://github.com/CCC-Attestation/formal-spec-TEE); [slides etc.](https://github.com/CCC-Attestation/formal-spec-KBS) | [Specs](https://datatracker.ietf.org/doc/draft-fossati-tls-attestation/) | [Implementation](https://github.com/ccc-attestation/attested-tls-poc) | 30 |
| ~~Yuxuan SONG~~ (Speaker is unable to present.) | Remote Attestation for Constrained IoT Use Cases | [IETF draft](https://datatracker.ietf.org/doc/draft-song-lake-ra/) | | [Attester(DotBot running on nRF5340)](https://github.com/ysong02/DotBot-firmware/blob/only-attestation-Nov/projects/03app_dotbot/03app_dotbot.c) , [Relying Party](https://github.com/ysong02/PyDotBot/tree/demo-remote-attestation), [Verifier](https://github.com/ysong02/dotbot-authority/tree/attestation-demo-video) | 15 |
| Anastassios Nanos | Secure Cloud-Native IoT: Onboarding, OTA Update, and Device Repurposing with OpenDICE in k8s | Presentation / Discussion about IoT application attestation |  |  | 20 |
| Venkat Nilesh Dadi | Confidential Federated Learning : A Case study in Healthcare Deployment | The slides are still in progress but they will focus on challenges, solution, architecture, future opportunities |  | | 10 |
| Muhammad Usama Sardar | Pinky Promises of Confidential Computing: An unspecified world of myths | Discussion about [open questions in attestation](https://mailarchive.ietf.org/arch/msg/rats/f-7MsyMOnUF5mwCH4oDGV4U9yPg/) | [Security through obscurity](https://en.wikipedia.org/wiki/Security_through_obscurity) |  | 20 |
| Paul Howard | Endorsement and RV Distribution: Interaction Model, API and Prototyping | [Slides](https://github.com/CCC-Attestation/meetings/blob/main/materials/PaulHoward_EndorsementDistribution_Sept2024.pdf) [Notes](https://wiki.ietf.org/group/rats/referencevalues) |  | [Veraison](https://github.com/veraison/services) | 20 |



[^1]: Remote attestation provides us with a demonstration that a given system is in a given state - ideally one where the integrity of the system is according to known good values.
Keeping a history of claims, results and decisions of a system over a longer period of time provides vital information about how a system is evolving over firmware and software changes, as well as potential hardware changes. Utilising this information can provide evidence of unwanted and unexpected changes to a system.
We present here a tool for attestation and forensics, through a simple example. Additionally we provide a case study from a potential firmware CVE and finally provide a case based upon Open Radio Access Network hardware.
