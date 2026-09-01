# Awesome RIS Attacks and Defenses
This repository contains a collection of papers and resources on **security and privacy** issues related to **reconfigurable intelligent surfaces (RISs)**.

# Table of Contents
- [📃Survey](#survey)
  - [Application Focus](#application-focus)
  - [Security Focus](#security-focus)
  - [Tutorials, Standards & Technical Reports](#tutorials-standards--technical-reports)
- [⚔️Attacks](#attacks)
  - [Attacks on RIS Systems](#attacks-on-ris-systems)
  - [Attacks Leveraging the RIS](#attacks-leveraging-the-ris)
- [🛡️Defenses](#defenses)
  - [Securing RIS-Assisted Systems](#securing-ris-assisted-systems)
  - [Countermeasures Against Malicious RISs](#countermeasures-against-malicious-riss)
    - [Early Detection of Unauthorized RIS](#early-detection-of-unauthorized-ris)
    - [System-level Defenses](#system-level-defenses)
  - [RIS as a Defensive Tool](#ris-as-a-defensive-tool)
    - [Physical-Layer Authentication](#physical-layer-authentication)
- [🛠️Tools](#tools)

# 📃Survey
## Application Focus
| Year | Publication                             | Paper                                                        |
| ---- | --------------------------------------- | ------------------------------------------------------------ |
| 2016 | Reports on progress in physics          | [A review of metasurfaces: physics and applications](https://iopscience.iop.org/article/10.1088/0034-4885/79/7/076401/ampdf) |
| 2020 | IEEE TCCN                               | [Reconfigurable intelligent surfaces for wireless communications: Principles, challenges, and opportunities](https://arxiv.org/pdf/2005.00938) |
| 2022 | IEEE STSP                               | [An overview of signal processing techniques for RIS/IRS-aided wireless systems](https://ieeexplore.ieee.org/ielaam/4200690/9874394/9847080-aam.pdf) |
| 2022 | Intelligent and Converged Networks      | [Reconfigurable intelligent surfaces for wireless communications: Overview of hardware designs, channel models, and estimation techniques](https://ieeexplore.ieee.org/iel7/9195266/9765810/09765815.pdf) |
| 2023 | IET Communications                      | [A survey on reconfigurable intelligent surfaces: Wireless communication perspective](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/cmu2.12571) |
| 2023 | IEEE Wireless Communications            | [Integrated sensing and communication with reconfigurable intelligent surfaces: Opportunities, applications, and future directions](https://arxiv.org/pdf/2206.08518) |
| 2022 | Proceedings of the IEEE                 | [Toward ubiquitous sensing and localization with reconfigurable intelligent surfaces](https://ieeexplore.ieee.org/ielaam/5/9896612/9775078-aam.pdf) | 
| 2025 | IEEE Communications Surveys & Tutorials | [The emergence of multi-functional and hybrid reconfigurable intelligent surfaces for integrated sensing and communications-a survey](https://ieeexplore.ieee.org/iel8/9739/5451756/10833623.pdf) | 
| 2025 | arXiv                                   | [A Survey on Reconfigurable Intelligent Surfaces in Practical Systems: Security and Privacy Perspectives](https://arxiv.org/pdf/2512.15754) |

## Security Focus
| Year | Publication                               | Paper                                                        |
| ---- | ----------------------------------------- | ------------------------------------------------------------ |
| 2025 | IEEE Internet of Things Journal           | [RIS-based physical layer security for integrated sensing and communication: A comprehensive survey](https://arxiv.org/pdf/2503.17721) |
| 2023 | IEEE OJ-COMS                              | [Security and privacy for reconfigurable intelligent surface in 6G: A review of prospective applications and challenges](https://ieeexplore.ieee.org/iel7/8782661/8901158/10121733.pdf) |
| 2025 | Discover Internet of Things               | [A comprehensive survey on 6G-security: physical connection and service layers](https://link.springer.com/content/pdf/10.1007/s43926-025-00123-7.pdf) |
| 2024 | IEEE Communications Surveys & Tutorials   | [Ris-assisted physical layer security in emerging rf and optical wireless communication systems: A comprehensive survey](https://arxiv.org/pdf/2403.10412) | 
| 2024 | IEEE Open Journal of Vehicular Technology | [A survey on reconfigurable intelligent surface for physical layer security of next-generation wireless communications](https://ieeexplore.ieee.org/iel7/8782711/8889399/10409564.pdf) | 

## Tutorials, Standards & Technical Reports

### Tutorial
| Year | Publication | Document |
| ---- | ----------- | -------- |
| 2022 | IEEE Signal Processing Magazine | [Reconfigurable Intelligent Surfaces: A Signal Processing Perspective with Wireless Applications](https://arxiv.org/pdf/2102.00742) |

### ETSI ISG RIS Deliverables
| Year | Organization | Document |
| ---- | ------------ | -------- |
| 2025 | ETSI | [GR RIS 001 V1.2.1: Use Cases, Deployment Scenarios and Requirements](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/001/01.02.01_60/gr_ris001v010201p.pdf) |
| 2025 | ETSI | [GR RIS 002 V1.2.1: Technological Challenges, Architecture and Impact on Standardization](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/002/01.02.01_60/gr_RIS002v010201p.pdf) |
| 2025 | ETSI | [GR RIS 003 V1.2.1: Communication Models, Channel Models, Channel Estimation and Evaluation Methodology](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/003/01.02.01_60/gr_RIS003v010201p.pdf) |
| 2025 | ETSI | [GR RIS 004 V1.1.1: Implementation and Practical Considerations](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/004/01.01.01_60/gr_RIS004v010101p.pdf) |
| 2025 | ETSI | [GR RIS 005 V1.1.1: Diversity and Multiplexing of RIS-Aided Communications](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/005/01.01.01_60/gr_ris005v010101p.pdf) |
| 2025 | ETSI | [GR RIS 006 V1.1.1: Multi-Functional RIS—Modelling, Optimization, and Operation](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/006/01.01.01_60/gr_RIS006v010101p.pdf) |
| 2026 | ETSI | [GR RIS 007 V1.1.1: Near-Field Channel Modelling and Mechanics](https://www.etsi.org/deliver/etsi_gr/RIS/001_099/007/01.01.01_60/gr_RIS007v010101p.pdf) |
| 2026 | ETSI | [GS RIS 008 V1.1.1: Standardized Testing for Reconfigurable Intelligent Surfaces](https://www.etsi.org/deliver/etsi_gs/RIS/001_099/008/01.01.01_60/gs_RIS008v010101p.pdf) |

### Supporting 3GPP and ITU Documents
These documents provide general channel, security, and IMT-2030 baselines; they are not dedicated 3GPP RIS specifications.

| Year | Organization | Document |
| ---- | ------------ | -------- |
| Continuously updated | 3GPP | [TR 38.901: Study on Channel Model for Frequencies from 0.5 to 100 GHz](https://portal.3gpp.org/desktopmodules/Specifications/SpecificationDetails.aspx?specificationId=3173) |
| Continuously updated | 3GPP | [TS 33.501: Security Architecture and Procedures for the 5G System](https://portal.3gpp.org/desktopmodules/Specifications/SpecificationDetails.aspx?specificationId=3169) |
| 2022 | ITU-R | [Report M.2516-0: Future Technology Trends of Terrestrial IMT Systems Towards 2030 and Beyond](https://www.itu.int/dms_pub/itu-r/opb/rep/R-REP-M.2516-2022-PDF-E.pdf) |
| 2023 | ITU-R | [Recommendation M.2160-0: Framework and Overall Objectives of IMT for 2030 and Beyond](https://www.itu.int/dms_pubrec/itu-r/rec/m/R-REC-M.2160-0-202311-I%21%21PDF-E.pdf) |

### Industry White Papers
| Year | Organization | Document |
| ---- | ------------ | -------- |
| 2023 | RIS TECH Alliance (RISTA) | [Reconfigurable Intelligent Surface Technology White Paper](https://www.risalliance.com/en/riswp2023_en/) |
| 2025 | FuTURE Forum / RISTA | [White Paper on Channel Modeling and Simulation for Reconfigurable Intelligent Surface](https://www.risalliance.com/en/channel-modeling-and-simulation-for-reconfigurable-intelligent-surface/) |
| 2025 | FuTURE Forum / RISTA | [White Paper on Prototyping of Reconfigurable Intelligent Surface](https://www.risalliance.com/en/white-paper-on-prototyping-of-reconfigurable-intelligent-surface/) |
| 2025 | FuTURE Forum / RISTA | [White Paper on Potential Standardization Work for Reconfigurable Intelligent Surface](https://www.risalliance.com/en/potential-standardization-work-for-reconfigurable-intelligent-surface-white-paper/) |
| 2025 | FuTURE Forum / RISTA | [6G Near-Field Technologies White Paper 2.0](https://www.risalliance.com/en/6g-near-field-technologies-white-paper-2-0-2/) |

# ⚔️Attacks
The attack taxonomy follows the adversary's position relative to the network operator's trust domain. **Attacks on RIS systems** exploit or compromise a legitimate RIS deployment, whereas **attacks leveraging the RIS** weaponize an unauthorized RIS or a fully compromised legitimate RIS against the broader wireless system. A paper may appear in both categories when it explicitly supports both deployment models.

## Attacks on RIS Systems
| Year | Publication                              | Target Component | Paper                                                     | Code💻 / Demo✅ |
| ---- | ---------------------------------------- | ------------- | ------------------------------------------------------------ | --------------- |
| 2022 | HotMobile '22                            | Control Link  | [Malicious mmWave reconfigurable surface: Eavesdropping through harmonic steering](https://dl.acm.org/doi/pdf/10.1145/3508396.3512879) | |
| 2023 | WiSec '23                                | Control Link  | [Wavefront manipulation attack via programmable mmWave metasurfaces: from theory to experiments](https://dl.acm.org/doi/pdf/10.1145/3558482.3590182) | |
| 2022 | ASIA CCS '22                             | Control Link  | [Mirror, mirror on the wall: Wireless environment reconfiguration attacks based on fast software-controlled surfaces](https://dl.acm.org/doi/pdf/10.1145/3488932.3497767) | |
| 2022 | IEEE ISIT 2022                           | RIS Controller | [Controller manipulation attack on reconfigurable intelligent surface aided wireless communication](https://ieeexplore.ieee.org/abstract/document/9834681) | |
| 2025 | IEEE CSCN 2025                           | RIS Hardware  | [MALRIS: Malicious Hardware in RIS-Assisted Wireless Communications](https://arxiv.org/pdf/2508.06340) | |
| 2020 | IEEE Wireless Communications Letters     | RIS Surface   | [IRS-based wireless jamming attacks: When jammers can attack without power](https://arxiv.org/pdf/2001.01887) | |
| 2025 | NDSS 2025                                | RIS Surface   | [Spatial-domain wireless jamming with reconfigurable intelligent surfaces](https://www.ndss-symposium.org/wp-content/uploads/2025-440-paper.pdf) | |

## Attacks Leveraging the RIS
| Year | Publication                              | Attack Type   | Paper                                                        | Code💻 / Demo✅ |
| ---- | ---------------------------------------- | ------------- | ------------------------------------------------------------ | --------------- |
| 2023 | IEEE TWC                                 | Jamming       | [Disco intelligent reflecting surfaces: Active channel aging for fully-passive jamming attack](https://arxiv.org/pdf/2302.00415) | [💻](https://github.com/huanhuan1799/Disco-Intelligent-Reflecting-Surfaces-Active-Channel-Aging-for-Fully-Passive-Jamming-Attacks) |
| 2025 | NDSS 2025                                | Jamming       | [Spatial-domain wireless jamming with reconfigurable intelligent surfaces](https://www.ndss-symposium.org/wp-content/uploads/2025-440-paper.pdf) | |
| 2020 | IEEE TWC                                 | Pilot Contamination | [Intelligent reflecting surface aided pilot contamination attack and its countermeasure](https://arxiv.org/pdf/2009.08512) | |
| 2022 | WiSec '22                                | Eavesdropping | [Metasurface-in-the-Middle Attack: From Theory to Experiment](https://par.nsf.gov/servlets/purl/10338626) | [✅](https://drive.google.com/file/d/1hu5ivAArYmeul0-GmbCC0SM9leYhDIeJ/view) |
| 2022 | HotMobile '22                            | Eavesdropping | [Malicious mmWave reconfigurable surface: Eavesdropping through harmonic steering](https://dl.acm.org/doi/pdf/10.1145/3508396.3512879) | |
| 2023 | WiSec '23                                | Eavesdropping | [Wavefront manipulation attack via programmable mmWave metasurfaces: from theory to experiments](https://dl.acm.org/doi/pdf/10.1145/3558482.3590182) | |
| 2023 | Nature Electronics                       | Eavesdropping | [Metasurface-enabled smart wireless attacks at the physical layer](https://www.researchsquare.com/article/rs-1857836/latest.pdf) | |
| 2023 | HotMobile '23                            | Eavesdropping | [Remotely Positioned MetaSurface-Drone Attack](https://dl.acm.org/doi/pdf/10.1145/3572864.3580343) | |
| 2024 | IEEE S&P 2024                            | Eavesdropping | [MetaFly: Wireless Backhaul Interception via Aerial Wavefront Manipulation](https://unlab.tech/wp-content/uploads/2023/10/313000a151.pdf) | |
| 2025 | arXiv                                    | Spoofing      | [RIS-Aided Positioning Under Adverse Conditions: Interference from Unauthorized RIS](https://arxiv.org/pdf/2502.19928) | |
| 2023 | IEEE S&P 2023                            | Spoofing      | [mmSpoof: Resilient Spoofing of Automotive Millimeter-Wave Radars Using Reflect Array](https://wcsng.ucsd.edu/files/mmspoof.pdf) | [✅](https://wcsng.ucsd.edu/mmspoof/) |
| 2023 | NDSS 2023                                | Spoofing      | [MetaWave: Attacking mmWave Sensing with Meta-material-enhanced Tags](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_f348_paper.pdf) | |
| 2023 | SenSys '23                               | Spoofing      | [RIStealth: Practical and Covert Physical-Layer Attack against WiFi-based Intrusion Detection via Reconfigurable Intelligent Surface](https://www.chenhuangxun.com/files/sensys23-ristealth.pdf) | |
| 2024 | CCS '24                                  | Spoofing      | [RISiren: Wireless Sensing System Attacks via Metasurface](https://dl.acm.org/doi/pdf/10.1145/3658644.3690186) | [✅](https://www.youtube.com/watch?v=yY80IhLvz3Q) |
| 2025 | arXiv                                    | Spoofing      | [Sensing Safety Analysis for Vehicular Networks with Integrated Sensing and Communication (ISAC)](https://arxiv.org/pdf/2505.01688) | |
| 2024 | Remote Sensing                           | Spoofing & Jamming | [A broadband information metasurface-assisted target jamming system for synthetic aperture radar](https://www.mdpi.com/2072-4292/16/9/1499) | |
| 2026 | The Web Conference (WWW)                 | Eavesdropping | [SuperEar: Eavesdropping on Mobile Voice Calls via Stealthy Acoustic Metamaterials](https://eprints.whiterose.ac.uk/id/eprint/237283/1/www26.pdf) | [💻](https://github.com/helo0507/Super-Ear) |
| 2025 | IEEE TIFS                                | Spoofing      | [A Portable and Stealthy Inaudible Voice Attack Based on Acoustic Metamaterials](https://doi.org/10.1109/TIFS.2025.3597233) | |

# 🛡️Defenses
The defense taxonomy is determined by the role of the RIS in the protected architecture. **Securing RIS-assisted systems** assumes that a legitimate RIS is already part of the system. **Countermeasures against malicious RISs** address attacks in which the adversary controls an unauthorized or compromised RIS. **RIS as a defensive tool** covers systems that introduce an additional friendly RIS specifically for protection. A paper may appear in more than one category if it evaluates multiple architectures.

## Securing RIS-Assisted Systems
| Year | Publication                              | Threat Type  | Paper                                                        | Code💻 / Demo✅ |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ | --------------- |
| 2022 | IEEE Access                              | Jamming       | [Anti-jamming RIS communications using DQN-based algorithm](https://ieeexplore.ieee.org/iel7/6287639/9668973/09732955.pdf) | |
| 2023 | GLOBECOM 2023                            | Jamming       | [An anti-jamming strategy for disco intelligent reflecting surfaces based fully-passive jamming attacks](https://arxiv.org/pdf/2307.03629) | |
| 2023 | Electronics                              | Jamming & Eavesdropping | [RIS-assisted robust beamforming for UAV anti-jamming and eavesdropping communications: A deep reinforcement learning approach](https://www.mdpi.com/2079-9292/12/21/4490) | |
| 2026 | IEEE TWC                                 | Eavesdropping | [Hiding in Plain Sight: RIS-Aided Target Obfuscation in ISAC](https://doi.org/10.1109/TWC.2026.3675857) | |
| 2022 | IEEE Transactions on Vehicular Technology | Eavesdropping | [Reconfigurable intelligent surface-assisted secure mobile edge computing networks](https://ieeexplore.ieee.org/abstract/document/9741383/) | |
| 2022 | IEEE Wireless Communications             | Eavesdropping | [Secure beamforming for IRS-enhanced NOMA networks](https://discovery.ucl.ac.uk/id/eprint/10153220/1/IRS_NOMA.pdf) | |
| 2024 | Sensors                                  | Eavesdropping | [An Underwater source location privacy protection scheme based on game theory in a multi-attacker cooperation scenario](https://www.mdpi.com/1424-8220/24/9/2851) | |
| 2024 | Photonics                                | Eavesdropping | [Reconfigurable Intelligent Surface-Aided Security Enhancement for Vehicle-to-Vehicle Visible Light Communications](https://search.proquest.com/openview/5e81221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | |
| 2022 | The Journal of Supercomputing            | Eavesdropping | [Security performance analysis of RIS-assisted UAV wireless communication in industrial IoT](https://doi.org/10.1007/s11227-021-04095-7) | |
| 2022 | ICC 2022                                 | Eavesdropping | [Robust design for STAR-RIS secured Internet of Medical Things](https://discovery.ucl.ac.uk/id/eprint/10153132/1/ICC22-m88403-wang%20final.pdf) | |
| 2024 | IEEE Transactions on Communications      | Eavesdropping | [Security Enhancement for RIS-Aided MEC Systems with Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10707344/) | |
| 2025 | ICNC 2025                                | Eavesdropping | [Secure-IRS: Defending Against Adversarial Physical-Layer Sensing in ISAC System](http://www.conf-icnc.org/2025/papers/p436-chen.pdf) | [✅](https://www.youtube.com/watch?v=oii3aj86tP0) |
| 2023 | IEEE Transactions on Industrial Informatics | Eavesdropping | [Deep reinforcement learning for RIS-aided secure mobile edge computing in industrial Internet of Things](https://ieeexplore.ieee.org/abstract/document/10186000/) | |
| 2022 | Physical Communication                   | Eavesdropping | [Deep reinforcement learning based IRS-assisted mobile edge computing under physical-layer security](https://www.sciencedirect.com/science/article/pii/S1874490722001732) | |
| 2025 | IEEE Transactions on Vehicular Technology | Eavesdropping | [RIS Assisted Near-Field NOMA Communications: A Security-Fairness Trade-Off](https://doi.org/10.1109/TVT.2025.3545253) | |
| 2025 | IEEE TWC                                 | Eavesdropping | [Double-RIS-Assisted Orbital Angular Momentum Near-Field Secure Communications](https://doi.org/10.1109/TWC.2025.3545368) | |
| 2024 | Frontiers of Information Technology & Electronic Engineering | Jamming & Eavesdropping | [XL-RIS Empowered Near-Field Physical Layer Security Against Jamming and Eavesdropping Attacks](https://doi.org/10.1631/FITEE.2400477) | |
| 2025 | Drones                                   | Eavesdropping | [Cooperative Jamming for RIS-Assisted UAV-WSN Against Aerial Malicious Eavesdropping](https://doi.org/10.3390/drones9060431) | |

## Countermeasures Against Malicious RISs
### Early Detection of Unauthorized RIS
| Year | Publication                    | Paper                                                        | Code💻 / Demo✅ |
| ---- | ------------------------------ | ------------------------------------------------------------ | --------------- |
| 2023 | Optics Express                 | [Detection and mapping of specular surfaces using multibounce lidar returns](https://opg.optica.org/viewmedia.cfm?uri=oe-31-4-6370) | |
| 2025 | ICC 2025                       | [On the Detection of Non-Cooperative RISs: Scan B-Testing via Deep Support Vector Data Description](https://arxiv.org/pdf/2411.03237) | |
| 2025 | arXiv                          | [Analysis and Detection of RIS-based Spoofing in Integrated Sensing and Communication (ISAC)](https://arxiv.org/pdf/2508.18100) | |
| 2022 | IEEE Pervasive Computing       | [See no evil: Discovering covert surveillance devices using thermal imaging](https://tuhat.helsinki.fi/ws/portalfiles/portal/214664118/Discovering_Covert_Surveillance_Devices_using_Thermal_Imaging.pdf) | |
| 2025 | IEEE TIFS                      | [MRIS-SAD: Malicious RIS Spoofing Attack Detection Based on Hybrid Deep Autoencoder](https://doi.org/10.1109/TIFS.2025.3601397) | |

### System-level Defenses
| Year | Publication                    | Paper                                                        | Code💻 / Demo✅ |
| ---- | ------------------------------ | ------------------------------------------------------------ | --------------- |
| 2020 | IEEE TWC                       | [Intelligent Reflecting Surface Aided Pilot Contamination Attack and Its Countermeasure](https://arxiv.org/pdf/2009.08512) | |
| 2024 | IEEE SPAWC 2024                | [Benign and Malicious Reconfigurable Intelligent Surfaces in MISO Wiretap Channels](https://ieeexplore.ieee.org/abstract/document/10693994/) | |
| 2023 | IEEE Wireless Communications Letters | [A Countermeasure Against RIS Jamming Attack in Physical-Layer Key Generation](https://ieeexplore.ieee.org/abstract/document/10247269/) | |
| 2023 | IEEE OJ-COMS                   | [Counteracting eavesdropper attacks through reconfigurable intelligent surfaces: A new threat model and secrecy rate optimization](https://ieeexplore.ieee.org/iel7/8782661/8901158/10143983.pdf) | |
| 2024 | IEEE Wireless Communications Letters | [Malicious RIS Versus Massive MIMO: Securing Multiple Access Against RIS-Based Jamming Attacks](https://ieeexplore.ieee.org/document/10402016/) | |

## RIS as a Defensive Tool
| Year | Publication                              | Threat Type  | Paper                                                        | Code💻 / Demo✅ |
| ---- | ---------------------------------------- | ------------ | ------------------------------------------------------------ | --------------- |
| 2025 | IEEE PIMRC 2025                          | Eavesdropping | [Optimizing Indoor RIS-Aided Physical-Layer Security: A Codebook-Generation Methodology and Measurement-Based Analysis](https://doi.org/10.1109/PIMRC62392.2025.11275086) | |
| 2024 | GLOBECOM 2024                            | Eavesdropping | [Online DRL-based Beam Selection for RIS-Aided Physical Layer Security: An Experimental Study](https://doi.org/10.1109/GLOBECOM52923.2024.10901057) | |
| 2023 | IEEE OJ-COMS                             | Eavesdropping | [Counteracting eavesdropper attacks through reconfigurable intelligent surfaces: A new threat model and secrecy rate optimization](https://ieeexplore.ieee.org/iel7/8782661/8901158/10143983.pdf) | |
| 2024 | Photonics                                | Eavesdropping | [Reconfigurable Intelligent Surface-Aided Security Enhancement for Vehicle-to-Vehicle Visible Light Communications](https://search.proquest.com/openview/5e81221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | |
| 2022 | IEEE S&P 2022                            | Eavesdropping | [IRShield: A countermeasure against adversarial physical-layer wireless sensing](https://arxiv.org/pdf/2112.01967) | [💻](https://zenodo.org/records/6367411) |
| 2022 | MobiCom '22                              | Eavesdropping | [Protego: securing wireless communication via programmable metasurface](https://search.proquest.com/openview/5281221c0172c992adcdde1cc4b31b8a/1?pq-origsite=gscholar&cbl=2032352) | |
| 2023 | Applied Physics Letters                  | Eavesdropping | [Physical-level secure wireless communication using random-signal-excited reprogrammable metasurface](https://pubs.aip.org/aip/apl/article/122/5/051704/2874729) | |
| 2025 | Nature Communications                    | Eavesdropping | [Chaotic information metasurface for direct physical-layer secure communication](https://www.nature.com/articles/s41467-025-60725-1.pdf) | |
| 2026 | arXiv                                    | Eavesdropping | [Invisible Walls: Privacy-Preserving ISAC Empowered by Reconfigurable Intelligent Surfaces](https://arxiv.org/abs/2601.04488) | |
| 2024 | Optica                                   | Eavesdropping | [Audio misinformation encoding via an on-phone sub-terahertz metasurface](https://opg.optica.org/viewmedia.cfm?seq=0&uri=optica-11-8-1113) | |
| 2025 | IEEE S&P 2025                            | Eavesdropping | [Spoofing eavesdroppers with audio misinformation](https://ieeexplore.ieee.org/abstract/document/11023283/) | [✅](https://sites.google.com/view/zhambyl-shaikhanov/spoofing-eve?authuser=0) |
| 2023 | IEEE CNS 2023                            | Eavesdropping | [RMDM: Using Random Meta-Atoms to Send Directional Misinformation to Eavesdroppers](https://networks.blogs.rice.edu/files/2023/09/RMDM-CNS.pdf) | |
| 2024 | IEEE Wireless Communications Letters     | Eavesdropping | [Intelligent reflecting surface-aided radar spoofing](https://arxiv.org/pdf/2405.06951) | |
| 2025 | IEEE CNS 2025                            | Eavesdropping | [MetaHeart: Spoofing Vibrational Biometrics via Dynamic Metasurfaces](https://networks.rice.edu/files/2025/08/MetaHeart.pdf) | |
| 2025 | Nature Communications                    | Eavesdropping | [Anti-radar based on metasurface](https://www.nature.com/articles/s41467-025-62633-w.pdf) | [✅](https://static-content.springer.com/esm/art%3A10.1038%2Fs41467-025-62633-w/MediaObjects/41467_2025_62633_MOESM3_ESM.mp4) |
| 2024 | IEEE Systems Journal                     | Jamming      | [Self-Sustainable Active Reconfigurable Intelligent Surfaces for Antijamming in Wireless Communications](https://arxiv.org/pdf/2406.09447) | |
| 2023 | Entropy                                  | Jamming      | [A communication anti-jamming scheme assisted by RIS with angular response](https://www.mdpi.com/1099-4300/25/12/1638) | |
| 2023 | Electronics                              | Jamming & Eavesdropping | [RIS-assisted robust beamforming for UAV anti-jamming and eavesdropping communications: A deep reinforcement learning approach](https://www.mdpi.com/2079-9292/12/21/4490) | |
| 2023 | IEEE Access                              | Spoofing     | [Mitigating inaudible ultrasound attacks on voice assistants with acoustic metamaterials](https://ieeexplore.ieee.org/iel7/6287639/6514899/10100683.pdf) | |
| 2023 | JASA                                     | Spoofing     | [3D printed acoustic metamaterial filters for the mitigation of inaudible ultrasound attacks on smart speakers](https://pubs.aip.org/asa/jasa/article-abstract/153/3_supplement/A197/2885933) | |
| 2025 | MobiCom 2025                             | Spoofing     | [MetaGuardian: Enhancing Voice Assistant Security through Advanced Acoustic Metamaterials](https://arxiv.org/pdf/2508.09728) | [💻](https://github.com/Meta-Guardian/MetaGuardian) |

### Physical-Layer Authentication
| Year | Publication                              | Threat Type            | Paper                                                        | Code💻 / Demo✅ |
| ---- | ---------------------------------------- | ---------------------- | ------------------------------------------------------------ | --------------- |
| 2024 | IEEE TWC                                 | Spoofing               | [RIS-Assisted Wireless Link Signatures for Specific Emitter Identification](https://ieeexplore.ieee.org/document/10682524/) | |
| 2025 | IEEE Transactions on Consumer Electronics | Spoofing             | [Efficient Gaussian Process Classification-Based Physical-Layer Authentication with Configurable Fingerprints for 6G-Enabled IoT](https://ieeexplore.ieee.org/document/10947359/) | |
| 2024 | IEEE TIFS                                | Spoofing               | [Analysis of Challenge-Response Authentication with Reconfigurable Intelligent Surfaces](https://doi.org/10.1109/TIFS.2024.3471185) | |
| 2025 | IEEE Internet of Things Journal          | Spoofing & Eavesdropping | [A Robust Reconfigurable Intelligent Surface-Aided Physical Layer Authentication Scheme Under Confidentiality Constraints](https://ieeexplore.ieee.org/document/10930486/) | |
| 2025 | IEEE Internet of Things Journal          | Spoofing               | [Voltage Profile-Driven Physical Layer Authentication for RIS-Aided Backscattering Tag-to-Tag Networks](https://ieeexplore.ieee.org/document/11172352/) | |

# 🛠️Tools
| Year | Publication / Organization            | Resources                                                    |
| ---- | ------------------------------------- | ------------------------------------------------------------ |
| 2024 | Mathworks                             | [Introduction to Reconfigurable Intelligent Surfaces (RIS)](https://www.mathworks.com/help/phased/ug/introduction-to-reconfigurable-intelligent-surfaces.html) | 
| 2024 | Mathworks                             | [Radar Sensing with Reconfigurable Intelligent Surfaces (RIS)](https://www.mathworks.com/help/phased/ug/reconfigurable-intelligent-surfaces-ris-aided-sensing.html) |
| 2024 | Mathworks                             | [Model Reconfigurable Intelligent Surfaces with CDL Channels](https://www.mathworks.com/help/5g/ug/model-reconfigurable-intelligent-surfaces-with-cdl-channels.html) |
| 2019 | ASU Wireless Intelligence Lab         | [DeepMIMO](https://deepmimo.net) |
| 2020 | Koç University CoreLab               | [SimRIS Channel Simulator v2.0](https://github.com/ifyildirim/SimRIS-Channel-Simulator) |
| 2022 | NVIDIA                                | [Sionna RT v0.19.2 (RIS-supported release)](https://github.com/NVlabs/sionna/releases/tag/v0.19.2) |
| 2024 | InterDigital                          | [NeoRadium](https://github.com/InterDigitalInc/NeoRadium) |
| 2023 | ISAP 2023                             | [Open Source RIS](https://github.com/mheinri/OpenSourceRIS) |
| 2024 | University of Trento                 | [CoopeRIS: RIS Simulation for Cooperative Driving](https://github.com/michele-segata/cooperis) |
| 2026 | Telefónica Scientific Research       | [DDRD: Data-Driven RIS Deployment](https://github.com/Telefonica-Scientific-Research/DDRD) |
| Continuously updated | GitHub | [RIS-Codes-Collection](https://github.com/ken0225/RIS-Codes-Collection) |
