# Awesome RIS Attacks and Defenses
This repository contains a collection of papers and resources on **security and privacy** issues related to **reconfigurable intellegent surface (RIS)**.

# Table of Contents
- [📃Survey](#survey)
  - [Application Focus](#application-focus)
  - [Security Focus](#security-focus)
  - [Tutorial & Technical Document](#tutorial--technical-document)
- [⚔️Attacks](#attacks)
  - [Attacking RIS-assisted Systems](#attacking-ris-assisted-systems)
  - [RIS for Attack](#ris-for-attack)
- [🛡️Defenses](#defenses)
  - [Defending attacks on RIS-assisted systems](#defending-attacks-on-ris-assisted-systems)
  - [Defending against RIS for attack](#defending-against-ris-for-attack)
    - [Early Detection of Unauthorized RIS](#early-detection-of-unauthorized-ris)
    - [System-level Defenses](#system-level-defenses)
  - [RIS for Defense](#ris-for-defense)
- [🛠️Tools](#tools)

# 📃Survey
## Application Focus
| Year | Publication                            | Paper                                                        |
| ---- | -------------------------------------- | ------------------------------------------------------------ |
| 2016 | Reports on progress in physics         | [A review of metasurfaces: physics and applications](https://iopscience.iop.org/article/10.1088/0034-4885/79/7/076401/ampdf) |
| 2020 | IEEE TCCN                              | [Reconfigurable intelligent surfaces for wireless communications: Principles, challenges, and opportunities](https://arxiv.org/pdf/2005.00938) |
| 2022 | IEEE STSP                              | [An overview of signal processing techniques for RIS/IRS-aided wireless systems](https://ieeexplore.ieee.org/ielaam/4200690/9874394/9847080-aam.pdf) |
| 2022 | Intelligent and Converged Networks     | [Reconfigurable intelligent surfaces for wireless communications: Overview of hardware designs, channel models, and estimation techniques](https://ieeexplore.ieee.org/iel7/9195266/9765810/09765815.pdf) |
| 2023 | IET Communications                     | [A survey on reconfigurable intelligent surfaces: Wireless communication perspective](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/cmu2.12571) |
| 2023 | IEEE Wireless Communications           | [Integrated sensing and communication with reconfigurable intelligent surfaces: Opportunities, applications, and future directions](https://arxiv.org/pdf/2206.08518) |
| 2022 | Proceedings of the IEEE                | [Toward ubiquitous sensing and localization with reconfigurable intelligent surfaces](https://ieeexplore.ieee.org/ielaam/5/9896612/9775078-aam.pdf) | 
| 2025 | IEEE Communications Surveys & Tutorials| [The emergence of multi-functional and hybrid reconfigurable intelligent surfaces for integrated sensing and communications-a survey](https://ieeexplore.ieee.org/iel8/9739/5451756/10833623.pdf) | 

## Security Focus
| Year | Publication                              | Paper                                                        |
| ---- | ---------------------------------------- | ------------------------------------------------------------ |
| 2025 | IEEE Internet of Things Journal          | [RIS-based physical layer security for integrated sensing and communication: A comprehensive survey](https://arxiv.org/pdf/2503.17721) |
| 2023 | IEEE OJ-COMS                             | [Security and privacy for reconfigurable intelligent surface in 6G: A review of prospective applications and challenges](https://ieeexplore.ieee.org/iel7/8782661/8901158/10121733.pdf) |
| 2025 | Discover Internet of Things              | [A comprehensive survey on 6G-security: physical connection and service layers](https://link.springer.com/content/pdf/10.1007/s43926-025-00123-7.pdf) |
| 2024 | IEEE Communications Surveys & Tutorials  | [Ris-assisted physical layer security in emerging rf and optical wireless communication systems: A comprehensive survey](https://arxiv.org/pdf/2403.10412) | 
| 2024 | IEEE Open Journal of Vehicular Technology| [A survey on reconfigurable intelligent surface for physical layer security of next-generation wireless communications](https://ieeexplore.ieee.org/iel7/8782711/8889399/10409564.pdf) | 

## Tutorial & Technical Document
| Year | Publication                    | Paper                                                        |
| ---- | ------------------------------ | ------------------------------------------------------------ |
| 2022 | IEEE Signal Processing Magazine| [Reconfigurable intelligent surfaces: A signal processing perspective with wireless applications](https://arxiv.org/pdf/2102.00742) | 
| 2023 | ETSI                           | [Reconfigurable Intelligent Surfaces (RIS); Communication Models, Channel Models, Channel Estimation and Evaluation Methodology](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/001/01.01.01_60/gr_RIS001v010101p.pdf) |

# ⚔️Attacks
## Attacking RIS-assisted Systems
| Year | Publication                              | Attack Type  | Paper                                                        |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ |
| 2020 | IEEE Wireless Communications Letters     | Jamming      | [IRS-based wireless jamming attacks: When jammers can attack without power](https://arxiv.org/pdf/2001.01887) |
| 2022 | ASIA CCS '22                             | Jamming      | [Mirror, mirror on the wall: Wireless environment reconfiguration attacks based on fast software-controlled surfaces](https://dl.acm.org/doi/pdf/10.1145/3488932.3497767) |
| 2025 | NDSS 2025                                | Jamming      | [Spatial-domain wireless jamming with reconfigurable intelligent surfaces](https://www.ndss-symposium.org/wp-content/uploads/2025-440-paper.pdf) |
| 2022 | HotMobile '22                            | Eavesdropping| [Malicious mmWave reconfigurable surface: Eavesdropping through harmonic steering](https://dl.acm.org/doi/pdf/10.1145/3508396.3512879) | 
| 2023 | WiSec '23                                | Eavesdropping| [Wavefront manipulation attack via programmable mmWave metasurfaces: from theory to experiments](https://dl.acm.org/doi/pdf/10.1145/3558482.3590182) | 
| 2025 | arXiv                                    | Spoofing     | [RIS-Aided Positioning Under Adverse Conditions: Interference from Unauthorized RIS](https://arxiv.org/pdf/2502.19928) | 
| 2025 | IEEE CSCN 2025                           | Spoofing     | [MALRIS: Malicious Hardware in RIS-Assisted Wireless Communications](https://arxiv.org/pdf/2508.06340) | 
| 2024 | Remote Sensing                           | Spoofing & Jamming| [A broadband information metasurface-assisted target jamming system for synthetic aperture radar](https://www.mdpi.com/2072-4292/16/9/1499) | 
| 2022 | IEEE ISIT 2022                           | Denial-of-Service| [Controller manipulation attack on reconfigurable intelligent surface aided wireless communication](https://ieeexplore.ieee.org/abstract/document/9834681) | 

## RIS for Attack
| Year | Publication                              | Attack Type  | Paper                                                        |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ |
| 2023 | IEEE Transactions on Wireless Communications | Jamming  | [Disco intelligent reflecting surfaces: Active channel aging for fully-passive jamming attack](https://arxiv.org/pdf/2302.00415) |
| 2025 | NDSS 2025                                | Jamming      | [Spatial-domain wireless jamming with reconfigurable intelligent surfaces](https://www.ndss-symposium.org/wp-content/uploads/2025-440-paper.pdf) |
| 2020 | IEEE Transactions on Wireless Communications | Eavesdropping| [Intelligent reflecting surface aided pilot contamination attack and its countermeasure](https://arxiv.org/pdf/2009.08512) |
| 2022 | WiSec '22                                | Eavesdropping| [Metasurface-in-the-Middle Attack: From Theory to Experiment](https://par.nsf.gov/servlets/purl/10338626) | 
| 2022 | HotMobile '22                            | Eavesdropping| [Malicious mmWave reconfigurable surface: Eavesdropping through harmonic steering](https://dl.acm.org/doi/pdf/10.1145/3508396.3512879) | 
| 2023 | WiSec '23                                | Eavesdropping| [Wavefront manipulation attack via programmable mmWave metasurfaces: from theory to experiments](https://dl.acm.org/doi/pdf/10.1145/3558482.3590182) | 
| 2023 | Nature Electronics                       | Eavesdropping| [Metasurface-enabled smart wireless attacks at the physical layer](https://www.researchsquare.com/article/rs-1857836/latest.pdf) | 
| 2025 | arXiv                                    | Spoofing     | [RIS-Aided Positioning Under Adverse Conditions: Interference from Unauthorized RIS](https://arxiv.org/pdf/2502.19928) | 
| 2023 | NDSS 2023                                | Spoofing     | [MetaWave: Attacking mmWave Sensing with Meta-material-enhanced Tags](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f348_paper.pdf) |
| 2023 | SenSys '23                               | Spoofing     | [RIStealth: Practical and Covert Physical-Layer Attack against WiFi-based Intrusion Detection via Reconfigurable Intelligent Surface](https://www.chenhuangxun.com/files/sensys23-ristealth.pdf)) | 
| 2024 | CCS '24                                  | Spoofing     | [RISiren: Wireless Sensing System Attacks via Metasurface](https://dl.acm.org/doi/pdf/10.1145/3658644.3690186) |
| 2025 | arXiv                                    | Spoofing     | [Sensing Safety Analysis for Vehicular Networks with Integrated Sensing and Communication (ISAC)](https://arxiv.org/pdf/2505.01688) |
| 2025 | arXiv                                    | Eavesdropping| [Stealthy Voice Eavesdropping with Acoustic Metamaterials: Unraveling a New Privacy Threat](https://arxiv.org/abs/2501.15032) |
| 2025 | IEEE TIFS                                | Spoofing     | [A Portable and Stealthy Inaudible Voice Attack Based on Acoustic Metamaterials](https://arxiv.org/pdf/2501.15031) |

# 🛡️Defenses
## Defending attacks on RIS-assisted systems
| Year | Publication                              | Threat Type  | Paper                                                        |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ |
| 2022 | IEEE Access                              | Jamming      | [Anti-jamming RIS communications using DQN-based algorithm](https://ieeexplore.ieee.org/iel7/6287639/9668973/09732955.pdf) |
| 2023 | IEEE Wireless Communications Letters     | Jamming      | [A Countermeasure Against RIS Jamming Attack in Physical-Layer Key Generation](https://ieeexplore.ieee.org/abstract/document/10247269/) |
| 2023 | GLOBECOM 2023                            | Jamming      | [An anti-jamming strategy for disco intelligent reflecting surfaces based fully-passive jamming attacks](https://arxiv.org/pdf/2307.03629) |
| 2023 | Electronics                              | Jamming & Eavesdropping| [RIS-assisted robust beamforming for UAV anti-jamming and eavesdropping communications: A deep reinforcement learning approach](https://www.mdpi.com/2079-9292/12/21/4490) |
| 2025 | arXiv                                    | Eavesdropping| [Hiding in Plain Sight: RIS-Aided Target Obfuscation in ISAC](https://arxiv.org/pdf/2001.01887) |
| 2022 | IEEE Transactions on Vehicular Technology| Eavesdropping| [Reconfigurable intelligent surface-assisted secure mobile edge computing networks](https://ieeexplore.ieee.org/abstract/document/9741383/) | 
| 2022 | IEEE Wireless Communications             | Eavesdropping| [Secure beamforming for IRS-enhanced NOMA networks](https://discovery.ucl.ac.uk/id/eprint/10153220/1/IRS_NOMA.pdf) | 
| 2024 | Sensors                                  | Eavesdropping| [An Underwater source location privacy protection scheme based on game theory in a multi-attacker cooperation scenario](https://www.mdpi.com/1424-8220/24/9/2851) | 
| 2024 | Photonics                                | Eavesdropping| [Reconfigurable Intelligent Surface-Aided Security Enhancement for Vehicle-to-Vehicle Visible Light Communications](https://search.proquest.com/openview/5e81221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | 
| 2022 | The Journal of Supercomputing            | Eavesdropping| [Security performance analysis of RIS-assisted UAV wireless communication in industrial IoT](https://dl.acm.org/doi/abs/10.1007/s11227-021-04095-7) | 
| 2024 | Photonics                                | Eavesdropping| [Reconfigurable Intelligent Surface-Aided Security Enhancement for Vehicle-to-Vehicle Visible Light Communications](https://search.proquest.com/openview/5e81221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | 
| 2022 | ICC 2022                                 | Eavesdropping| [Robust design for STAR-RIS secured Internet of Medical Things](https://discovery.ucl.ac.uk/id/eprint/10153132/1/ICC22-m88403-wang%20final.pdf) |
| 2024 | IEEE Transactions on Communications      | Eavesdropping| [Security Enhancement for RIS-Aided MEC Systems with Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10707344/) |
| 2025 | ICNC 2025                                | Eavesdropping| [Secure-IRS: Defending Against Adversarial Physical-Layer Sensing in ISAC System](http://www.conf-icnc.org/2025/papers/p436-chen.pdf) |
| 2023 | IEEE Transactions on Industrial Informatics| Eavesdropping| [Deep reinforcement learning for RIS-aided secure mobile edge computing in industrial Internet of Things](https://ieeexplore.ieee.org/abstract/document/10186000/) |
| 2022 | Physical Communication                   | Eavesdropping| [Deep reinforcement learning based IRS-assisted mobile edge computing under physical-layer security](https://www.sciencedirect.com/science/article/pii/S1874490722001732) |

## Defending against RIS for attack
### Early Detection of Unauthorized RIS
| Year | Publication                    | Paper                                                        |
| ---- | ------------------------------ | ------------------------------------------------------------ |
| 2023 | Optics Express                 | [Detection and mapping of specular surfaces using multibounce lidar returns](https://opg.optica.org/viewmedia.cfm?uri=oe-31-4-6370) |
| 2025 | ICC 2025                       | [On the Detection of Non-Cooperative RISs: Scan B-Testing via Deep Support Vector Data Description](https://arxiv.org/pdf/2411.03237) |
| 2025 | arXiv                          | [Analysis and Detection of RIS-based Spoofing in Integrated Sensing and Communication (ISAC)](https://arxiv.org/pdf/2508.18100) |
| 2022 | IEEE Pervasive Computing       | [See no evil: Discovering covert surveillance devices using thermal imaging](https://ieeexplore.ieee.org/iel7/7756/10002256/09830124.pdf) |

### System-level Defenses
| Year | Publication                    | Paper                                                        |
| ---- | ------------------------------ | ------------------------------------------------------------ |
| 2024 | IEEE SPAWC 2024                | [Benign and Malicious Reconfigurable Intelligent Surfaces in MISO Wiretap Channels](https://ieeexplore.ieee.org/abstract/document/10693994/) |
| 2023 | IEEE Wireless Communications Letters | [A Countermeasure Against RIS Jamming Attack in Physical-Layer Key Generation](https://ieeexplore.ieee.org/abstract/document/10247269/) |
| 2023 | IEEE OJ-COMS                   | [Counteracting eavesdropper attacks through reconfigurable intelligent surfaces: A new threat model and secrecy rate optimization](https://ieeexplore.ieee.org/iel7/8782661/8901158/10143983.pdf) |
| 2025 | Drones                         | [Cooperative Jamming for RIS-Assisted UAV-WSN Against Aerial Malicious Eavesdropping](https://www.mdpi.com/2504-446X/9/6/431) |

## RIS for Defense
| Year | Publication                              | Method       | Paper                                                        |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ |
| 2023 | Electronics                              | Optimization | [RIS-assisted robust beamforming for UAV anti-jamming and eavesdropping communications: A deep reinforcement learning approach](https://www.mdpi.com/2079-9292/12/21/4490) |
| 2023 | IEEE OJ-COMS                             | Optimization | [Counteracting eavesdropper attacks through reconfigurable intelligent surfaces: A new threat model and secrecy rate optimization](https://ieeexplore.ieee.org/iel7/8782661/8901158/10143983.pdf) |
| 2024 | GLOBECOM 2024                            | Optimization | [Online DRL-based Beam Selection for RIS-Aided Physical Layer Security: An Experimental Study](https://www.researchgate.net/profile/Abdulkadir-Celik/publication/385879881_Online_DRL-based_Beam_Selection_for_RIS-Aided_Physical_Layer_Security_An_Experimental_Study/links/6738bbb437496239b2c276e2/Online-DRL-based-Beam-Selection-for-RIS-Aided-Physical-Layer-Security-An-Experimental-Study.pdf) |
| 2024 | IEEE Systems Journal                     | Optimization | [Self-Sustainable Active Reconfigurable Intelligent Surfaces for Antijamming in Wireless Communications](https://arxiv.org/pdf/2406.09447) |
| 2025 | arXiv                                    | Optimization | [Optimizing Indoor RIS-Aided Physical-Layer Security: A Codebook-Generation Methodology and Measurement-Based Analysis](https://arxiv.org/pdf/2506.22082) |
| 2023 | Entropy                                  | Optimization | [A communication anti-jamming scheme assisted by RIS with angular response](https://www.mdpi.com/1099-4300/25/12/1638) |
| 2024 | Photonics                                | Optimization | [Reconfigurable Intelligent Surface-Aided Security Enhancement for Vehicle-to-Vehicle Visible Light Communications](https://search.proquest.com/openview/5e81221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | 
| 2022 | IEEE S&P 2022                            | Introducing Randomness | [IRShield: A countermeasure against adversarial physical-layer wireless sensing](https://arxiv.org/pdf/2112.01967) | 
| 2022 | MobiCom '22                              | Introducing Randomness | [Protego: securing wireless communication via programmable metasurface](https://search.proquest.com/openview/5281221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | 
| 2023 | Applied Physics Letters                  | Introducing Randomness | [Physical-level secure wireless communication using random-signal-excited reprogrammable metasurface](https://pubs.aip.org/aip/apl/article/122/5/051704/2874729) |
| 2025 | Nature Communications                    | Introducing Randomness | [Chaotic information metasurface for direct physical-layer secure communication](https://www.nature.com/articles/s41467-025-60725-1.pdf) |
| 2024 | Optica                                   | Spoofing the Attacker  | [Audio misinformation encoding via an on-phone sub-terahertz metasurface](https://opg.optica.org/viewmedia.cfm?seq=0&uri=optica-11-8-1113) |
| 2025 | IEEE S&P 2025                            | Spoofing the Attacker  | [Spoofing eavesdroppers with audio misinformation](https://ieeexplore.ieee.org/abstract/document/11023283/) |
| 2024 | IEEE Wireless Communications Letters     | Spoofing the Attacker  | [Intelligent reflecting surface-aided radar spoofing](https://arxiv.org/pdf/2405.06951) |
| 2025 | Nature Communications                    | Spoofing the Attacker  | [Anti-radar based on metasurface](https://www.nature.com/articles/s41467-025-62633-w.pdf) |
| 2023 | IEEE Access                              | Attenuation  | [Mitigating inaudible ultrasound attacks on voice assistants with acoustic metamaterials](https://ieeexplore.ieee.org/iel7/6287639/6514899/10100683.pdf) |
| 2023 | JASA                                     | Attenuation  | [3D printed acoustic metamaterial filters for the mitigation of inaudible ultrasound attacks on smart speakers](https://pubs.aip.org/asa/jasa/article-abstract/153/3_supplement/A197/2885933) |
| 2025 | MobiCom 2025                             | Attenuation  | [MetaGuardian: Enhancing Voice Assistant Security through Advanced Acoustic Metamaterials](https://arxiv.org/pdf/2508.09728) |

# 🛠️Tools
| Year | Publication / Organization            | Resources                                                    |
| ---- | ------------------------------------- | ------------------------------------------------------------ |
| 2024 | Mathworks                             | [Introduction to Reconfigurable Intelligent Surfaces (RIS)](https://www.mathworks.com/help/phased/ug/introduction-to-reconfigurable-intelligent-surfaces.html) | 
| 2024 | Mathworks                             | [Radar Sensing with Reconfigurable Intelligent Surfaces (RIS)](https://www.mathworks.com/help/phased/ug/reconfigurable-intelligent-surfaces-ris-aided-sensing.html) |
| 2024 | Mathworks                             | [Model Reconfigurable Intelligent Surfaces with CDL Channels](https://www.mathworks.com/help/5g/ug/model-reconfigurable-intelligent-surfaces-with-cdl-channels.html) |
| 2023 | ISAP 2023                             | [Open Source RIS](https://github.com/mheinri/OpenSourceRIS) |
| 2025 | / | [RIS-Codes-Collection](https://github.com/ken0225/RIS-Codes-Collection) |
