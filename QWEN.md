# Curated Undergraduate Computer Science Thesis Ideas (Batch 1 of 20)

*Note: Due to output length constraints, this collection is provided in sequential batches. This batch contains 10 fully detailed, high-impact thesis ideas. Save this text as a `.md` file.*

## Idea 1
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Federated Learning for Privacy-Preserving Predictive Modeling of Neurodegenerative Diseases Using Wearable Sensor Data |
| **2. Description** | Early detection of neurodegenerative diseases like Parkinson's and Alzheimer's relies heavily on continuous monitoring of patient motor and cognitive functions. However, transmitting sensitive physiological data to centralized servers raises severe privacy concerns and violates healthcare regulations like HIPAA. This research proposes a federated learning (FL) framework that trains predictive models locally on patients' edge devices (smartwatches and smartphones) using data from wearable sensors (accelerometers, gyroscopes). By only sharing model weight updates instead of raw data, the system ensures patient privacy while collaboratively improving a global predictive model. The expected contribution is a novel FL aggregation algorithm optimized for heterogeneous, non-IID wearable data, resulting in a highly accurate, privacy-preserving decision-support system for early diagnosis and disease progression tracking. |
| **3. Target Domain** | Healthcare, Bioinformatics |
| **4. Statement of the Problem (SOP)** | 1. How can non-IID wearable sensor data be effectively aggregated in a federated learning environment? <br> 2. What edge-optimization techniques minimize battery drain during local model training on wearable devices? <br> 3. How does the proposed FL framework compare to centralized models in predicting early-stage neurodegenerative symptoms? |
| **5. Technologies** | Python, PyTorch, TensorFlow Federated, MQTT, Wearable APIs (Apple HealthKit, Google Fit), Edge AI |
| **6. Research Category** | Artificial Intelligence, Distributed Systems, Healthcare Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Mobile Application, Federated Learning Backend, Predictive AI Model, Research Paper |
| **10. Possible Future Extensions** | Integration with electronic health records (EHR), multimodal data fusion (voice + gait), commercialization as a SaaS platform for neurology clinics. |
| **11. References / Inspiration** | Recent advances in Federated Learning (McMahan et al.), Arxiv papers on digital biomarkers for Parkinson's, PhysioNet datasets. |

## Idea 2
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Mitigating Deepfake Audio in Real-Time Voice Communication using Multimodal Acoustic-Visual Anomaly Detection |
| **2. Description** | The proliferation of AI-generated audio deepfakes poses a significant threat to secure voice communication, enabling fraud and social engineering attacks. Current detection mechanisms often rely solely on acoustic features and struggle with real-time processing or high-fidelity neural vocoders. This thesis proposes a multimodal anomaly detection system that analyzes both acoustic artifacts and visual lip-sync inconsistencies in real-time video calls. By leveraging self-supervised learning models (e.g., Wav2Vec 2.0 and VideoMAE), the system extracts latent representations of audio and video streams to detect discrepancies. The primary contribution is a lightweight, real-time inference engine capable of flagging spoofed audio with minimal latency, providing a robust defense mechanism for teleconferencing platforms and banking voice authentication systems. |
| **3. Target Domain** | Cybersecurity, Media Forensics |
| **4. Statement of the Problem (SOP)** | 1. What are the distinct acoustic artifacts produced by state-of-the-art neural vocoders? <br> 2. How can multimodal fusion of audio and video features improve deepfake detection accuracy in low-bandwidth networks? <br> 3. What architectural optimizations allow this model to run in real-time on consumer hardware? |
| **5. Technologies** | Python, PyTorch, Hugging Face Transformers, WebRTC, ONNX Runtime, C++ |
| **6. Research Category** | Cybersecurity, Computer Vision, Audio Processing |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Real-time Detection Engine, WebRTC Plugin, Benchmarking Dataset |
| **10. Possible Future Extensions** | Extension to full-body avatar deepfakes, integration with enterprise communication platforms (Zoom/Teams API). |
| **11. References / Inspiration** | ASVspoof challenge datasets, papers on audiovisual deepfake detection, Wav2Vec 2.0 architecture. |

## Idea 3
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Blockchain-Based Supply Chain Provenance and Cold-Chain Integrity for Pharmaceutical Logistics |
| **2. Description** | Pharmaceutical cold chain logistics require strict temperature control to maintain drug efficacy. Counterfeit drugs and broken cold chains cause severe health risks and financial losses. This thesis proposes a permissioned blockchain system (e.g., Hyperledger Fabric) integrated with IoT temperature and humidity sensors to track drug provenance from manufacturer to pharmacy. Smart contracts automatically flag and quarantine shipments that violate temperature thresholds. The expected contribution is a highly scalable, tamper-proof tracking architecture that ensures data immutability, enhances transparency, and automates compliance reporting in pharmaceutical supply chains. |
| **3. Target Domain** | Supply Chain, Healthcare, Logistics |
| **4. Statement of the Problem (SOP)** | 1. How can high-frequency IoT sensor data be securely and efficiently anchored to a permissioned blockchain without causing network congestion? <br> 2. What smart contract logic optimally handles automated quarantine and alerting for cold-chain violations? <br> 3. How does the proposed system ensure data privacy and competitive confidentiality among competing pharmaceutical distributors? |
| **5. Technologies** | Hyperledger Fabric, Solidity, Node.js, React, MQTT, Raspberry Pi, Temperature/Humidity Sensors |
| **6. Research Category** | Distributed Systems, Internet of Things (IoT), Software Engineering |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Web Dashboard, Smart Contracts, IoT Sensor Prototype, System Architecture Document |
| **10. Possible Future Extensions** | Integration with national health databases, AI for predictive supply chain disruptions, tokenization of pharmaceutical assets. |
| **11. References / Inspiration** | Hyperledger documentation, WHO reports on counterfeit medicines, IBM Food Trust architecture. |

## Idea 4
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Edge-AI Powered Adaptive Traffic Light Control System Using Computer Vision and Deep Reinforcement Learning |
| **2. Description** | Urban traffic congestion causes significant economic loss and carbon emissions. Traditional traffic lights rely on fixed timers or simple induction loops, failing to adapt to dynamic traffic flows. This research proposes an Edge-AI system using YOLOv8 for real-time vehicle detection and Deep Reinforcement Learning (DRL) to dynamically adjust traffic light phases. By processing video feeds locally on edge devices (e.g., NVIDIA Jetson), the system minimizes latency and bandwidth usage. The primary contribution is a novel DRL reward function that balances average waiting time, vehicle throughput, and emergency vehicle prioritization, resulting in a scalable, intelligent intersection management system. |
| **3. Target Domain** | Smart Cities, Transportation, Civil Engineering |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight computer vision models be deployed on edge devices for accurate, real-time vehicle counting under adverse weather conditions? <br> 2. What reward functions in Deep Reinforcement Learning yield the lowest average waiting times and highest throughput at multi-lane intersections? <br> 3. How can the system securely prioritize emergency vehicles without disrupting overall traffic flow optimization? |
| **5. Technologies** | Python, PyTorch, YOLOv8, OpenCV, NVIDIA Jetson Nano, SUMO (Traffic Simulator), DeepRL |
| **6. Research Category** | Artificial Intelligence, Computer Vision, Embedded Systems |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Edge AI Prototype, Traffic Simulation Environment, Control Algorithm, Performance Metrics Report |
| **10. Possible Future Extensions** | Multi-intersection coordination via V2X (Vehicle-to-Everything) communication, integration with pedestrian tracking for crosswalk safety. |
| **11. References / Inspiration** | Papers on DRL for traffic signal control, YOLO architecture, SUMO simulation documentation. |

## Idea 5
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Retrieval-Augmented Generation (RAG) for Context-Aware Legal Document Analysis and Summarization in Low-Resource Jurisdictions |
| **2. Description** | Legal professionals spend excessive time reviewing case files, statutes, and precedents. While Large Language Models (LLMs) offer summarization, they frequently hallucinate when applied to specific legal domains without expensive fine-tuning. This thesis implements a Retrieval-Augmented Generation (RAG) pipeline using a local vector database to provide accurate, context-aware legal summarization and Q&A for a specific jurisdiction (e.g., local municipal or provincial laws). By retrieving only the most relevant legal clauses before generating an answer, the system drastically reduces hallucinations. The contribution is an optimized RAG framework tailored for complex, hierarchical legal texts, providing a highly reliable decision-support tool for legal practitioners. |
| **3. Target Domain** | Legal Technology, Natural Language Processing |
| **4. Statement of the Problem (SOP)** | 1. How does a RAG pipeline reduce hallucination rates in domain-specific legal queries compared to zero-shot or few-shot LLM prompting? <br> 2. What chunking, embedding, and retrieval strategies yield the highest accuracy for lengthy, hierarchical legal documents? <br> 3. How can the system ensure strict data privacy and confidentiality for sensitive client files during the retrieval and generation process? |
| **5. Technologies** | Python, LangChain, LlamaIndex, Hugging Face, Qdrant/ChromaDB, Llama-3/Mistral, FastAPI |
| **6. Research Category** | Natural Language Processing, Artificial Intelligence, Software Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | Web Application, RAG Pipeline, Vector Database, Evaluation Metrics Report |
| **10. Possible Future Extensions** | Multi-lingual legal support, automated contract drafting, integration with court e-filing systems. |
| **11. References / Inspiration** | Lewis et al. (RAG original paper), local legal repositories, LangChain documentation. |

## Idea 6
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | IoT and Drone-Based Precision Agriculture System Using Multispectral Imagery and Soil Sensor Fusion for Nutrient Management |
| **2. Description** | Inefficient water and fertilizer use degrades soil health and wastes resources. This thesis develops a precision agriculture system that fuses data from ground-based soil NPK (Nitrogen, Phosphorus, Potassium) sensors and drone-based multispectral imagery. A machine learning model processes this spatially aligned data to generate precise, zone-specific irrigation and fertilization prescriptions. The expected contribution is a robust data fusion algorithm that bridges the gap between micro-level soil data and macro-level aerial imagery, enabling farmers to optimize crop yields while minimizing environmental impact through targeted resource application. |
| **3. Target Domain** | Agriculture, Environmental Science, IoT |
| **4. Statement of the Problem (SOP)** | 1. How can drone-based multispectral imagery and ground sensor data be accurately spatially and temporally aligned? <br> 2. What machine learning models best predict crop nutrient deficiencies based on combined multispectral indices and soil NPK data? <br> 3. How can a low-power, wide-area network (LoRaWAN) architecture be designed to ensure reliable connectivity for IoT sensors in remote rural farms? |
| **5. Technologies** | Python, Scikit-learn, LoRaWAN, Raspberry Pi, DroneKit, OpenCV, GIS Software (QGIS) |
| **6. Research Category** | Internet of Things (IoT), Machine Learning, Data Science |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | IoT Sensor Network, Drone Data Processing Pipeline, Farm Management Dashboard |
| **10. Possible Future Extensions** | Automated drone spraying mechanisms, integration with satellite weather and soil moisture data, predictive crop yield modeling. |
| **11. References / Inspiration** | FAO reports on precision agriculture, LoRaWAN specifications, NDVI/NDRE research papers. |

## Idea 7
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Performance Evaluation and Integration of Post-Quantum Cryptography Algorithms for Secure IoT Communication in Smart Grids |
| **2. Description** | The advent of quantum computers threatens current RSA and ECC encryption standards widely used in IoT devices. This thesis evaluates and integrates Post-Quantum Cryptography (PQC) algorithms (e.g., CRYSTALS-Kyber, Dilithium) into a constrained IoT environment, specifically targeting Smart Grid sensors. The research benchmarks the computational overhead, energy consumption, and latency of PQC against traditional cryptography on resource-constrained microcontrollers. The primary contribution is a hybrid cryptographic scheme (ECC + PQC) optimized for secure key exchange in IoT networks, ensuring long-term data security against future quantum attacks while maintaining real-time grid communication requirements. |
| **3. Target Domain** | Cybersecurity, Smart Grids, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. What is the exact computational, memory, and energy overhead of NIST-approved PQC algorithms on resource-constrained IoT microcontrollers? <br> 2. How can hybrid cryptographic schemes (ECC + PQC) be implemented to ensure secure, backward-compatible key exchange in IoT networks? <br> 3. How does the proposed PQC-integrated system perform under network latency, packet loss, and high-throughput conditions typical of Smart Grids? |
| **5. Technologies** | C/C++, liboqs (Open Quantum Safe), MQTT, ARM Cortex-M, Wireshark, OpenSSL |
| **6. Research Category** | Cybersecurity, Embedded Systems, Networking |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Cryptographic Library, IoT Prototype, Performance Benchmarking Report |
| **10. Possible Future Extensions** | Hardware-level acceleration of PQC algorithms, standardization compliance testing, application to V2G (Vehicle-to-Grid) communications. |
| **11. References / Inspiration** | NIST PQC standardization reports, liboqs GitHub repository, IEEE papers on Smart Grid security. |

## Idea 8
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | AI-Driven Early Detection of Diabetic Retinopathy Using Lightweight, Mobile-Deployed Convolutional Neural Networks |
| **2. Description** | Diabetic retinopathy is a leading cause of blindness globally, particularly in rural areas lacking access to ophthalmologists and high-end diagnostic equipment. This research proposes a lightweight, mobile-deployed Convolutional Neural Network (CNN) that analyzes retinal fundus images captured via smartphone adapters. By employing model quantization, pruning, and knowledge distillation, the system provides offline, real-time screening directly on the device. The expected contribution is a highly optimized, clinically viable mobile application that democratizes access to early eye disease screening, complete with a robust evaluation against standard clinical diagnostic benchmarks. |
| **3. Target Domain** | Healthcare, Computer Vision, Mobile Computing |
| **4. Statement of the Problem (SOP)** | 1. How can model quantization and pruning maintain high diagnostic accuracy while drastically reducing model size and inference time for mobile deployment? <br> 2. What data augmentation and synthetic data techniques best address the severe class imbalance typically found in retinal disease datasets? <br> 3. How does the optimized model perform on low-quality, noisy, or poorly illuminated images captured in non-clinical, real-world settings? |
| **5. Technologies** | Python, TensorFlow Lite, Keras, Android Studio, OpenCV, MobileNet/EfficientNet |
| **6. Research Category** | Artificial Intelligence, Computer Vision, Software Engineering |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | Mobile Application, Optimized CNN Model, Clinical Validation Report |
| **10. Possible Future Extensions** | Cloud-based doctor review integration, extension to detect other ocular diseases (glaucoma, cataracts), integration with portable fundus cameras. |
| **11. References / Inspiration** | Kaggle Diabetic Retinopathy Detection dataset, APTOS dataset, MobileNet architecture papers. |

## Idea 9
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Decentralized Identity Management and Academic Credential Verification Using Zero-Knowledge Proofs and Verifiable Credentials |
| **2. Description** | Fake degrees and slow transcript verification processes plague the education and hiring sectors. This thesis designs a Decentralized Identifier (DID) and Verifiable Credentials (VC) system utilizing Zero-Knowledge Proofs (ZKPs). Graduates can cryptographically prove they hold a degree from a specific university or maintain a minimum GPA without revealing their exact grades, transcripts, or personal identifiable information (PII). The primary contribution is a privacy-preserving, user-centric identity wallet architecture that eliminates the need for trusted third-party verification agencies, drastically reducing fraud and administrative overhead in academic credentialing. |
| **3. Target Domain** | Education, Blockchain, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. How can ZKPs (e.g., zk-SNARKs) be effectively utilized to verify complex academic credentials without exposing sensitive student data? <br> 2. What is the optimal blockchain architecture (e.g., Polygon, Hyperledger Indy) for storing DIDs and credential schemas while ensuring high throughput and low costs? <br> 3. How does the system handle secure key recovery and social recovery if a student loses access to their digital identity wallet? |
| **5. Technologies** | Solidity, Rust, Hyperledger Indy/Aries, React Native, ZK-SNARKs, IPFS |
| **6. Research Category** | Distributed Systems, Cybersecurity, Human-Computer Interaction |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Mobile Wallet App, University Issuer Portal, Smart Contracts, ZKP Circuit Design |
| **10. Possible Future Extensions** | Cross-border credential recognition, integration with national digital ID systems, extension to professional certifications and micro-credentials. |
| **11. References / Inspiration** | W3C Verifiable Credentials standards, Zcash/ZK-SNARK documentation, Hyperledger Aries frameworks. |

## Idea 10
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Continuous Sign Language Translation Using Wearable IMU Sensors and Transformer Sequence Models |
| **2. Description** | Vision-based sign language translation systems frequently struggle with occlusions, variable lighting conditions, and complex backgrounds. This thesis proposes a robust, multimodal approach combining wearable Inertial Measurement Unit (IMU) sensors on the hands, wrists, and arms with a Transformer-based sequence model. The system captures the kinematics of continuous sign language and translates it into text and synthesized speech in real-time. The expected contribution is a novel temporal data fusion technique that accurately classifies complex hand shapes and movement trajectories, resulting in a low-latency, highly accurate, and privacy-preserving translation wearable that operates entirely independent of cameras. |
| **3. Target Domain** | Human-Computer Interaction, Accessibility, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can high-frequency temporal data from multiple IMU sensors be fused to accurately classify complex hand shapes, orientations, and movement trajectories? <br> 2. What sequence modeling architectures (e.g., LSTMs vs. Transformers) yield the highest translation accuracy and lowest word error rate for continuous, unconstrained signing? <br> 3. How can the system minimize computational latency to enable natural, real-time conversational flow on edge devices? |
| **5. Technologies** | Python, PyTorch, ESP32/Arduino, IMU Sensors (MPU6050/BNO055), BLE, Hugging Face Transformers |
| **6. Research Category** | Human-Computer Interaction, Embedded Systems, Machine Learning |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Wearable Sensor Prototype, Translation Software, Mobile App, Dataset Collection |
| **10. Possible Future Extensions** | Bidirectional translation (speech to haptic feedback), expansion to full-body sign language tracking, integration with smart glasses for heads-up display. |
| **11. References / Inspiration** | Papers on IMU-based gesture recognition, WLASL (Word-Level Sign Language) dataset, Transformer architecture for time-series data. |


# Curated Undergraduate Computer Science Thesis Ideas (Batch 2 of 20)

## Idea 11
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Carbon Sequestration Verification in Reforestation Projects Using Satellite Imagery and Vision Transformers |
| **2. Description** | Voluntary carbon markets suffer from fraud, inaccurate biomass estimation, and high manual verification costs. This research proposes an automated verification system utilizing Vision Transformers (ViTs) on multispectral satellite imagery (e.g., Sentinel-2) to accurately estimate above-ground biomass and carbon sequestration rates in reforestation zones. Unlike traditional Convolutional Neural Networks, ViTs capture global spatial dependencies, improving the detection of subtle vegetation health changes and canopy density over time. The primary contribution is a highly scalable, cloud-based pipeline that processes temporal satellite data to generate tamper-proof carbon credit verification reports, significantly increasing transparency and trust in environmental markets. |
| **3. Target Domain** | Environmental Science, Data Science, Green Tech |
| **4. Statement of the Problem (SOP)** | 1. How do Vision Transformers compare to CNNs in estimating above-ground biomass from multispectral satellite imagery? <br> 2. What temporal analysis techniques best differentiate between natural seasonal canopy variations and actual deforestation or degradation? <br> 3. How can the system mitigate the impact of persistent cloud cover on optical satellite imagery to ensure continuous monitoring? |
| **5. Technologies** | Python, PyTorch, Google Earth Engine, Sentinel-2 API, Vision Transformers (ViT), FastAPI |
| **6. Research Category** | Computer Vision, Artificial Intelligence, Environmental Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Biomass Estimation Model, Web Dashboard, Cloud Processing Pipeline, Verification API |
| **10. Possible Future Extensions** | Integration with LiDAR data for 3D canopy modeling, drone-based ground-truthing, tokenization of verified carbon credits on a blockchain. |
| **11. References / Inspiration** | FAO REDD+ guidelines, Sentinel-2 documentation, recent papers on ViTs for remote sensing. |

## Idea 12
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Implementing Microsegmentation and Zero-Trust Networking in Serverless Architectures Using Extended Berkeley Packet Filter (eBPF) |
| **2. Description** | Serverless computing and microservices rely on ephemeral containers and functions, rendering traditional IP-based firewalls and heavy sidecar proxies inefficient and latency-inducing. This thesis explores the implementation of kernel-level microsegmentation and Zero-Trust networking using the Extended Berkeley Packet Filter (eBPF). By attaching eBPF programs directly to network interfaces and system calls, the system enforces fine-grained security policies with minimal overhead. The expected contribution is a comprehensive performance evaluation and a custom eBPF-based security agent tailored for serverless environments, demonstrating superior throughput and lower latency compared to traditional service mesh solutions like Istio. |
| **3. Target Domain** | Cloud Computing, Cybersecurity, Distributed Systems |
| **4. Statement of the Problem (SOP)** | 1. What is the precise computational and memory overhead of eBPF-based packet filtering compared to sidecar proxies in high-throughput serverless environments? <br> 2. How can dynamic, ephemeral identities be securely managed and enforced at the kernel level without relying on centralized control planes? <br> 3. What are the limitations of eBPF instruction set constraints when implementing complex Layer 7 (application layer) security policies? |
| **5. Technologies** | C, Go, eBPF, Cilium, Kubernetes, Linux Kernel, Prometheus |
| **6. Research Category** | Cybersecurity, Cloud Computing, Networking |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | eBPF Security Agent, Kubernetes Controller, Performance Benchmarking Report |
| **10. Possible Future Extensions** | Integration with WebAssembly (Wasm) for user-space policy extension, AI-driven anomaly detection directly in kernel space. |
| **11. References / Inspiration** | eBPF.io documentation, Cilium architecture, Linux kernel networking papers. |

## Idea 13
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Low-Latency Haptic Feedback System for Remote Minimally Invasive Surgical Training Using Digital Twins and Edge Computing |
| **2. Description** | Remote surgical training and teleoperation are severely limited by network latency and the lack of realistic tactile feedback, which can lead to tissue damage during procedures. This research develops a low-latency haptic feedback system integrated with a real-time Digital Twin of the surgical environment. By offloading physics simulations and haptic rendering to an edge computing node, the system minimizes the motion-to-photon and motion-to-haptic delays. The primary contribution is a novel synchronization protocol between the physical haptic device, the edge server, and the digital twin, ensuring high-fidelity force feedback even over fluctuating network conditions. |
| **3. Target Domain** | Healthcare, Robotics, Human-Computer Interaction |
| **4. Statement of the Problem (SOP)** | 1. What are the critical latency thresholds required to maintain haptic fidelity and prevent user disorientation in remote surgical simulations? <br> 2. How can physics-based tissue deformation models be optimized to run in real-time on edge computing nodes? <br> 3. What predictive algorithms best compensate for network jitter and packet loss in continuous haptic data streams? |
| **5. Technologies** | C++, ROS 2, Unity3D, NVIDIA Omniverse, Haptic SDKs, 5G/Edge Testbeds |
| **6. Research Category** | Human-Computer Interaction, Embedded Systems, Robotics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Haptic Simulation Environment, Digital Twin Model, Latency Analysis Report |
| **10. Possible Future Extensions** | Integration with AI for autonomous surgical assistance, multi-user collaborative surgical training environments. |
| **11. References / Inspiration** | IEEE Transactions on Haptics, ROS 2 Control documentation, digital twin frameworks in healthcare. |

## Idea 14
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Context-Aware Automated Code Review and Vulnerability Remediation Using Fine-Tuned Large Language Models and Static Analysis Integration |
| **2. Description** | Manual code review is a bottleneck in modern CI/CD pipelines, and while Large Language Models (LLMs) can generate code, they frequently introduce subtle vulnerabilities or hallucinate fixes. This thesis proposes a hybrid automated code review system that combines fine-tuned LLMs with traditional Abstract Syntax Tree (AST) parsing and static analysis tools. The AST provides structural context and enforces syntactic correctness, guiding the LLM to generate secure, context-aware patches for identified vulnerabilities (e.g., SQL injection, XSS). The expected contribution is a highly accurate, low-false-positive GitHub bot that seamlessly integrates into developer workflows, significantly improving software security posture. |
| **3. Target Domain** | Software Engineering, Artificial Intelligence, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. How does the integration of AST structural context reduce the hallucination rate and vulnerability introduction rate of LLM-generated code patches? <br> 2. What fine-tuning strategies (e.g., LoRA) are most effective for adapting open-source code LLMs to specific enterprise coding standards? <br> 3. How can the system effectively balance the trade-off between strict security enforcement and developer acceptance rates? |
| **5. Technologies** | Python, LangChain, AST Parsers, CodeLlama/DeepSeek, SonarQube, GitHub API |
| **6. Research Category** | Software Engineering, Natural Language Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | GitHub Bot, Fine-tuned LLM, Evaluation Dataset, CI/CD Integration Guide |
| **10. Possible Future Extensions** | Autonomous pull request generation for technical debt, integration with dynamic application security testing (DAST) tools. |
| **11. References / Inspiration** | Devign dataset, CodeLlama research papers, SonarQube rule documentation. |

## Idea 15
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Decentralized Parametric Crop Insurance Platform Using IoT Soil Sensors and Blockchain Oracles for Automated Claims Processing |
| **2. Description** | Traditional crop insurance involves lengthy claims assessments, high administrative overhead, and delayed payouts, which are devastating for smallholder farmers. This thesis designs a decentralized parametric insurance platform where payouts are automatically triggered by predefined environmental conditions (e.g., soil moisture dropping below a critical threshold for a specific duration). Utilizing low-cost IoT soil sensors and a decentralized oracle network (e.g., Chainlink) to feed tamper-proof data into smart contracts, the system ensures instant, transparent claims processing. The primary contribution is a robust, hardware-to-blockchain architecture that minimizes oracle manipulation risks and reduces insurance operational costs. |
| **3. Target Domain** | FinTech, Agriculture, Blockchain |
| **4. Statement of the Problem (SOP)** | 1. How can IoT sensor data be cryptographically secured at the hardware level to prevent tampering before it reaches the blockchain oracle? <br> 2. What smart contract logic optimally handles complex, multi-variable parametric triggers (e.g., combining soil moisture and local weather APIs)? <br> 3. How does the cost of deploying and maintaining the IoT network compare to the financial savings from automated claims processing? |
| **5. Technologies** | Solidity, Chainlink, LoRaWAN, ESP32, React, IPFS |
| **6. Research Category** | Distributed Systems, Internet of Things (IoT), FinTech |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | Smart Contracts, IoT Node Prototype, Web Portal for Farmers/Insurers |
| **10. Possible Future Extensions** | Integration with satellite weather data for broader coverage, tokenization of reinsurance risk, micro-insurance models. |
| **11. References / Inspiration** | Chainlink documentation, World Bank reports on parametric insurance, LoRaWAN specifications. |

## Idea 16
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Edge-AI Based Volumetric Estimation of Road Surface Anomalies Using Monocular Vision and LiDAR Sensor Fusion for Municipal Maintenance |
| **2. Description** | Potholes and road degradation cause severe vehicle damage and accidents. While 2D computer vision can detect potholes, municipal engineering departments require 3D volumetric data to estimate the asphalt needed for repairs. This research proposes an Edge-AI system that fuses monocular camera data with low-resolution LiDAR to accurately estimate the depth and volume of road anomalies in real-time. Deployed on municipal vehicles, the system maps the GPS coordinates and repair requirements of road networks. The expected contribution is a lightweight sensor fusion algorithm optimized for edge devices, providing actionable, quantitative maintenance data rather than simple binary detection. |
| **3. Target Domain** | Smart Cities, Civil Engineering, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can monocular depth estimation and sparse LiDAR point clouds be effectively fused to accurately calculate the volume of irregular road anomalies? <br> 2. What edge-computing optimizations are required to run sensor fusion algorithms in real-time on moving vehicles without excessive power consumption? <br> 3. How does the system maintain accuracy under varying lighting conditions, shadows, and wet road surfaces? |
| **5. Technologies** | Python, ROS 2, OpenCV, YOLOv8, NVIDIA Jetson, Ouster/Velodyne LiDAR |
| **6. Research Category** | Computer Vision, Embedded Systems, Internet of Things (IoT) |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Edge Device Prototype, 3D Mapping Dashboard, Sensor Fusion Algorithm |
| **10. Possible Future Extensions** | Integration with autonomous road-patching robots, crowd-sourced mapping via consumer dashcams, predictive road degradation modeling. |
| **11. References / Inspiration** | KITTI dataset, municipal public works APIs, papers on monocular-LiDAR fusion. |

## Idea 17
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Predicting Drug-Target Interactions Using Heterogeneous Graph Neural Networks and Molecular SMILES Representations |
| **2. Description** | Identifying viable drug-target interactions (DTIs) is a critical, yet expensive and time-consuming, phase in drug discovery. This thesis applies Heterogeneous Graph Neural Networks (HGNNs) to model the complex relationships between chemical compounds, proteins, and biological pathways. By converting molecular SMILES strings into graph structures and integrating them with protein sequence embeddings, the HGNN learns latent representations to predict binding affinities. The primary contribution is a novel graph construction methodology that captures both local molecular topology and global biological context, significantly improving the accuracy of DTI prediction for novel, unseen compounds (the cold-start problem). |
| **3. Target Domain** | Bioinformatics, Artificial Intelligence, Chemistry |
| **4. Statement of the Problem (SOP)** | 1. How do heterogeneous graph representations of molecular SMILES and protein sequences improve DTI prediction accuracy compared to homogeneous graphs? <br> 2. What graph neural network architectures (e.g., GraphSAGE, GAT) best capture the long-range dependencies in complex biological networks? <br> 3. How can the model effectively address the "cold-start" problem when predicting interactions for entirely novel chemical entities? |
| **5. Technologies** | Python, PyTorch Geometric, RDKit, DeepChem, Hugging Face Transformers |
| **6. Research Category** | Artificial Intelligence, Data Science, Bioinformatics |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | HGNN Model, Prediction API, Benchmarking Report against Baselines |
| **10. Possible Future Extensions** | Generative AI for de novo drug design, integration with clinical trial simulation data, multi-target drug synergy prediction. |
| **11. References / Inspiration** | ChEMBL database, PyTorch Geometric documentation, recent papers on GNNs in drug discovery. |

## Idea 18
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Distributed Acoustic Sensor Network for Urban Anomaly Detection and Triangulation Using Edge-Based Audio Event Classification |
| **2. Description** | Urban environments face challenges in rapidly detecting and locating critical acoustic events such as gunshots, vehicular collisions, or glass breaking, especially in areas with CCTV blind spots. This thesis develops a distributed network of low-cost acoustic sensor nodes that perform edge-based audio event classification. By processing audio locally using lightweight neural networks, the system preserves privacy (no raw audio is transmitted) and reduces bandwidth. When an anomaly is detected, nodes share timestamped event metadata to triangulate the exact location using Time-Difference-of-Arrival (TDoA) algorithms. The contribution is a scalable, privacy-preserving urban security infrastructure that significantly reduces emergency response times. |
| **3. Target Domain** | Smart Cities, Cybersecurity, Internet of Things (IoT) |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight audio classification models maintain high accuracy in highly noisy, complex urban acoustic environments? <br> 2. What is the precision limit of TDoA triangulation using low-cost, unsynchronized IoT microcontrollers in a distributed network? <br> 3. How can the system securely authenticate sensor nodes to prevent spoofing or false alarm injection attacks? |
| **5. Technologies** | Python, TensorFlow Lite, Raspberry Pi/ESP32, I2S Microphones, MQTT, WebSockets |
| **6. Research Category** | Internet of Things (IoT), Audio Processing, Embedded Systems |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Sensor Node Prototype, Triangulation Dashboard, Urban Audio Dataset |
| **10. Possible Future Extensions** | Integration with automated drone dispatch systems, multi-modal (audio + visual) edge fusion for event verification. |
| **11. References / Inspiration** | ESC-50 dataset, urban acoustic research papers, ShotSpotter architecture analysis. |

## Idea 19
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Adaptive E-Learning Platform Utilizing Knowledge Tracing and Webcam-Based Affective Computing for Real-Time Engagement Optimization |
| **2. Description** | High dropout rates in online education are often caused by a lack of personalized pacing and undetected student disengagement. This research develops an adaptive e-learning platform that combines Deep Knowledge Tracing (DKT) with edge-processed, webcam-based affective computing. The system analyzes facial micro-expressions and gaze patterns locally on the student's device to detect confusion, boredom, or frustration, without transmitting sensitive video feeds. This affective state data is fused with the DKT model to dynamically adjust the difficulty, format, or pacing of subsequent learning materials. The expected contribution is a privacy-first, multimodal student modeling framework that significantly improves learning outcomes and retention. |
| **3. Target Domain** | Education, Human-Computer Interaction, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How can affective states (confusion, boredom) be accurately classified using lightweight edge models without violating student privacy? <br> 2. What mathematical models best integrate continuous affective state data with discrete knowledge tracing algorithms? <br> 3. Which adaptive intervention strategies (e.g., changing media type, altering difficulty) yield the highest re-engagement rates? |
| **5. Technologies** | React, Python, MediaPipe, PyTorch, FastAPI, PostgreSQL |
| **6. Research Category** | Human-Computer Interaction, Artificial Intelligence, EdTech |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Web Platform, Adaptive Algorithm, User Study Report |
| **10. Possible Future Extensions** | Integration with VR/AR learning environments, LLM-based personalized Socratic tutoring based on affective state. |
| **11. References / Inspiration** | ASSISTments dataset, MediaPipe Face Mesh, Deep Knowledge Tracing (DKT) papers. |

## Idea 20
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Carbon-Aware Workload Orchestration in Geographically Distributed Kubernetes Clusters Using Real-Time Grid Emission APIs |
| **2. Description** | Data centers are massive consumers of electricity, and the carbon intensity of the power grid varies significantly by geographic location and time of day. This thesis develops a custom Kubernetes scheduler plugin that orchestrates delay-tolerant batch workloads across geographically distributed clusters based on real-time carbon emission data. By integrating with grid emission APIs, the scheduler shifts workloads to regions currently powered by renewable energy or shifts execution to off-peak hours with lower grid carbon intensity. The primary contribution is a comprehensive evaluation of the trade-offs between computational latency, network transfer emissions, and overall carbon reduction, providing a practical framework for Green IT in cloud-native environments. |
| **3. Target Domain** | Cloud Computing, Green IT, Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. What is the exact trade-off between network data transfer emissions and compute carbon savings when migrating workloads across geographic zones? <br> 2. How can a Kubernetes scheduler dynamically adapt to rapid fluctuations in real-time grid carbon intensity without causing excessive pod churn? <br> 3. How does carbon-aware scheduling impact the Service Level Objectives (SLOs) and job completion times of distributed microservices? |
| **5. Technologies** | Go, Kubernetes, Prometheus, Electricity Maps API, Docker, Helm |
| **6. Research Category** | Cloud Computing, Distributed Systems, Green IT |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | K8s Scheduler Plugin, Carbon Dashboard, Simulation Results |
| **10. Possible Future Extensions** | Integration with cloud spot pricing for dual financial and carbon optimization, thermal-aware scheduling for liquid-cooled data centers. |
| **11. References / Inspiration** | Electricity Maps API, Kubernetes Scheduler Framework documentation, Green Software Foundation principles. |


# Curated Undergraduate Computer Science Thesis Ideas (Batch 3 of 20)

## Idea 21
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Edge AI-Driven Acoustic Monitoring and Classification of Agricultural Pests Using TinyML on Low-Power IoT Nodes |
| **2. Description** | Agricultural pest outbreaks cause massive crop losses, and traditional monitoring relies heavily on manual visual inspection or expensive, slow pheromone traps. This research proposes a network of low-power IoT acoustic sensors deployed in orchards to continuously monitor the environment for the specific wing-beat frequencies and mating calls of target pests (e.g., fruit flies or moths). By deploying TinyML models directly on microcontrollers, the system filters out complex background noise (wind, birds, machinery) and only transmits alert metadata. The expected contribution is a highly optimized, energy-efficient audio classification pipeline that enables early, localized pest intervention, drastically reducing broad-spectrum pesticide use and supporting precision agriculture. |
| **3. Target Domain** | Agriculture, Internet of Things (IoT), Environmental Science |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight TinyML models accurately isolate specific insect acoustic signatures from complex environmental background noise? <br> 2. What power-management strategies maximize the operational lifespan of solar-powered acoustic IoT nodes in remote agricultural settings? <br> 3. How does early acoustic detection correlate with actual pest population density compared to traditional monitoring methods? |
| **5. Technologies** | C/C++, TensorFlow Lite for Microcontrollers, ESP32, I2S MEMS Microphones, LoRaWAN, Edge Impulse |
| **6. Research Category** | Embedded Systems, Audio Processing, Internet of Things (IoT) |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | IoT Sensor Prototype, TinyML Audio Model, Farm Management Dashboard |
| **10. Possible Future Extensions** | Integration with automated drone spraying mechanisms, multi-modal sensor fusion (acoustic + visual), expansion to livestock health monitoring. |
| **11. References / Inspiration** | Edge Impulse documentation, research on bioacoustics in entomology, LoRaWAN agricultural deployments. |

## Idea 22
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Detection and Mitigation of Indirect Prompt Injection in Retrieval-Augmented Generation (RAG) Systems |
| **2. Description** | As enterprises integrate Large Language Models (LLMs) into customer-facing applications via RAG architectures, they become highly vulnerable to indirect prompt injection attacks embedded within retrieved external documents. This thesis develops a real-time, intermediary security gateway that intercepts and sanitizes context payloads before they reach the LLM. By combining deterministic rule-based filtering with a lightweight, fine-tuned classification model trained on adversarial prompt datasets, the system detects malicious intent with minimal latency. The primary contribution is a novel defense-in-depth architecture for LLM applications that mitigates data exfiltration and unauthorized actions originating from untrusted external data sources while preserving the utility of benign queries. |
| **3. Target Domain** | Cybersecurity, Artificial Intelligence, Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. What are the most effective feature extraction techniques for detecting semantic adversarial attacks hidden within large blocks of retrieved text? <br> 2. How can a security gateway mitigate indirect prompt injection without degrading the context window or altering the semantic meaning of benign documents? <br> 3. What is the latency and computational overhead of the proposed defense mechanism on real-time LLM inference pipelines? |
| **5. Technologies** | Python, FastAPI, Hugging Face Transformers, LangChain, Redis, OWASP LLM Top 10 guidelines |
| **6. Research Category** | Cybersecurity, Natural Language Processing |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Security Gateway API, Adversarial Prompt Dataset, Latency Benchmarking Report |
| **10. Possible Future Extensions** | Automated self-healing of RAG pipelines, integration with dynamic taint analysis for tracking data provenance through LLM attention layers. |
| **11. References / Inspiration** | OWASP Top 10 for LLM Applications, academic papers on indirect prompt injection (e.g., Greshake et al.), RAG security frameworks. |

## Idea 23
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Non-Invasive Continuous Blood Glucose Estimation Using Multimodal Fusion of Photoplethysmography (PPG) and Electrochemical Sweat Sensors |
| **2. Description** | Continuous glucose monitoring (CGM) is vital for diabetes management, but current gold-standard devices require invasive subcutaneous needles. This research explores a non-invasive approach by fusing photoplethysmography (PPG) signals from consumer smartwatches with data from wearable electrochemical sweat sensors. A multimodal deep learning model analyzes the morphological features of the PPG waveform alongside interstitial glucose levels in sweat to estimate blood glucose continuously. The expected contribution is a robust data fusion algorithm that compensates for the physiological lag and noise inherent in non-invasive modalities, providing a comfortable, needle-free alternative for diabetic patients to manage their metabolic health. |
| **3. Target Domain** | Healthcare, Bioinformatics, Wearable Technology |
| **4. Statement of the Problem (SOP)** | 1. How do morphological features of PPG waveforms correlate with acute fluctuations in blood glucose levels across different demographics? <br> 2. What multimodal fusion architectures best synchronize and weigh asynchronous data streams from optical (PPG) and electrochemical (sweat) sensors? <br> 3. How does the proposed system perform in real-world conditions involving motion artifacts, varying skin tones, and ambient temperature changes? |
| **5. Technologies** | Python, PyTorch, Apple HealthKit / Android Wear APIs, Signal Processing (SciPy), Time-Series Analysis, BLE |
| **6. Research Category** | Artificial Intelligence, Healthcare Informatics, Signal Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Multimodal Fusion Model, Mobile Companion App, Clinical Validation Analysis |
| **10. Possible Future Extensions** | Integration with continuous ketone monitoring, predictive hypoglycemia alerting algorithms, FDA regulatory pathway analysis for digital therapeutics. |
| **11. References / Inspiration** | PhysioNet PPG datasets, research on non-invasive glucose monitoring, multimodal sensor fusion literature. |

## Idea 24
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Distributed Acoustic Leak Detection and Triangulation in Municipal Water Networks Using Edge-Based Cross-Correlation |
| **2. Description** | Municipal water networks lose significant volumes of treated water due to undetected underground leaks, leading to financial losses and infrastructure damage. This thesis proposes a distributed acoustic monitoring system using low-cost hydrophones attached to fire hydrants and valves. By employing edge-based cross-correlation algorithms and machine learning, the system detects the specific acoustic signatures of pressurized water escaping from pipes and triangulates the leak location. The primary contribution is a scalable, low-power IoT architecture that enables continuous, proactive leak detection in aging water infrastructure without the need for expensive, specialized acoustic loggers, directly supporting sustainable urban water management. |
| **3. Target Domain** | Smart Cities, Civil Engineering, Internet of Things (IoT) |
| **4. Statement of the Problem (SOP)** | 1. What machine learning models most accurately classify the acoustic signatures of water leaks versus transient environmental noise (e.g., traffic, pumps)? <br> 2. How can time-synchronization be achieved across distributed, low-cost IoT nodes to enable precise acoustic cross-correlation and leak triangulation? <br> 3. What data compression techniques minimize LoRaWAN bandwidth usage while preserving the high-frequency acoustic features necessary for leak detection? |
| **5. Technologies** | C++, Python, Raspberry Pi Pico, Piezoelectric Sensors, LoRaWAN, Digital Signal Processing (DSP), TimescaleDB |
| **6. Research Category** | Internet of Things (IoT), Signal Processing, Embedded Systems |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | IoT Sensor Node, Triangulation Algorithm, Municipal Dashboard |
| **10. Possible Future Extensions** | Integration with hydraulic simulation models (EPANET) for pressure management, predictive maintenance scheduling based on pipe material and age. |
| **11. References / Inspiration** | Acoustic leak detection literature, LoRaWAN time synchronization protocols, municipal water loss audit guidelines (IWA). |

## Idea 25
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Tokenization of Plastic Waste for Circular Economy Tracking Using Computer Vision and Blockchain Smart Contracts |
| **2. Description** | Inefficient informal waste collection and lack of financial incentives hinder global plastic recycling efforts. This research designs a decentralized platform that incentivizes plastic waste collection by integrating computer vision for automated waste classification with blockchain-based token rewards. Users deposit waste into smart bins equipped with cameras and load cells; an edge AI model classifies the plastic type (e.g., PET, HDPE) and weight, triggering a smart contract to mint and transfer utility tokens to the user's digital wallet. The expected contribution is a verifiable, tamper-proof circular economy framework that provides granular data on waste flows while economically empowering informal waste pickers. |
| **3. Target Domain** | Environmental Science, Blockchain, FinTech |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight computer vision models be optimized to accurately classify heavily degraded, crumpled, or dirty plastic waste in real-time on edge devices? <br> 2. What tokenomic models and smart contract architectures best prevent fraud (e.g., depositing non-recyclables or reusing the same waste)? <br> 3. How does the integration of verifiable credentials ensure the ethical and transparent integration of informal waste collectors into the digital economy? |
| **5. Technologies** | Solidity, Python, YOLOv8, Raspberry Pi, Load Cells, Polygon/Ethereum, React Native |
| **6. Research Category** | Distributed Systems, Computer Vision, Green Tech |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Smart Bin Prototype, Smart Contracts, Mobile Wallet Application |
| **10. Possible Future Extensions** | Integration with corporate ESG reporting APIs, automated sorting robotic arms triggered by the vision system, carbon credit generation. |
| **11. References / Inspiration** | Plastic Bank operational models, YOLO object detection papers, ERC-20 and ERC-1155 token standards. |

## Idea 26
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Adaptive Brain-Computer Interface (BCI) for Hands-Free Smart Home Control Using Hybrid SSVEP and P300 Paradigms |
| **2. Description** | Individuals with severe motor impairments (e.g., ALS, spinal cord injuries) struggle to interact with their environment. This thesis develops a Brain-Computer Interface (BCI) system using consumer-grade, non-invasive EEG headsets to control smart home appliances. By implementing a hybrid paradigm that combines Steady-State Visually Evoked Potentials (SSVEP) for high-speed selection and P300 event-related potentials for confirmation, the system maximizes Information Transfer Rate (ITR) while minimizing user fatigue. The primary contribution is an adaptive signal processing pipeline that dynamically adjusts to the user's cognitive state and environmental noise, providing a reliable, hands-free home automation interface. |
| **3. Target Domain** | Accessibility, Human-Computer Interaction, Biomedical Engineering |
| **4. Statement of the Problem (SOP)** | 1. How does a hybrid SSVEP-P300 paradigm improve the Information Transfer Rate (ITR) and reduce error rates compared to single-paradigm BCI systems? <br> 2. What spatial filtering and feature extraction techniques best isolate neural signals from ocular and muscular artifacts in uncontrolled home environments? <br> 3. How can the system dynamically adapt stimulus frequencies and thresholds based on real-time measurements of user cognitive fatigue? |
| **5. Technologies** | Python, OpenBCI/Emotiv SDK, SciPy, Scikit-learn, Home Assistant API, WebSockets, EEG Signal Processing |
| **6. Research Category** | Human-Computer Interaction, Signal Processing, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | BCI Software Application, Smart Home Integration Module, User Study Evaluation |
| **10. Possible Future Extensions** | Integration with powered wheelchairs for mobility control, continuous affective state monitoring for automated environmental adjustments (e.g., lighting, temperature). |
| **11. References / Inspiration** | BCI competition datasets, literature on hybrid BCI paradigms, Home Assistant API documentation. |

## Idea 27
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Autonomous Generation of Executable Integration Tests from User Stories Using LLM Agents and Codebase-Aware RAG |
| **2. Description** | Generating comprehensive unit and integration tests from natural language requirements is a time-consuming task that often leads to incomplete test coverage in agile environments. This research proposes an autonomous AI agent framework that parses Jira tickets or user stories, generates a formal behavioral model, and automatically synthesizes executable test code. By utilizing Large Language Models equipped with Retrieval-Augmented Generation (RAG) to understand the specific codebase architecture and existing test patterns, the agent ensures the generated tests are syntactically correct and contextually relevant. The expected contribution is a measurable reduction in manual testing effort and an increase in code reliability within CI/CD pipelines. |
| **3. Target Domain** | Software Engineering, Artificial Intelligence, DevOps |
| **4. Statement of the Problem (SOP)** | 1. How can LLMs accurately translate ambiguous natural language user stories into deterministic, executable behavioral models (e.g., Cucumber/Gherkin)? <br> 2. What RAG strategies are most effective for providing the LLM with the necessary codebase context to generate accurate integration tests without exceeding context limits? <br> 3. How does the autonomous generation of tests impact overall code coverage and defect escape rates compared to traditional manual test writing? |
| **5. Technologies** | Python, LangChain, Llama-3 / GPT-4 API, Jira API, PyTest, AST Parsing, Git |
| **6. Research Category** | Software Engineering, Natural Language Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | AI Agent Framework, CI/CD Pipeline Integration, Empirical Evaluation Report |
| **10. Possible Future Extensions** | Automated generation of UI test scripts (e.g., Selenium/Playwright), self-healing test code when the underlying application API changes. |
| **11. References / Inspiration** | Research on LLMs for code generation, LangChain agent architectures, agile software testing methodologies. |

## Idea 28
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Energy-Aware Delay-Tolerant Mesh Networking for Post-Disaster Communication Using Heterogeneous IoT and Mobile Devices |
| **2. Description** | Natural disasters frequently destroy centralized cellular and internet infrastructure, severely hampering rescue operations and civilian communication. This thesis develops a Delay-Tolerant Networking (DTN) architecture that utilizes a hybrid mesh network of LoRaWAN nodes and smartphone Bluetooth/Wi-Fi Direct connections. The system employs opportunistic routing and data muling, where messages are stored and forwarded by moving nodes (e.g., rescue vehicles or drones) until they reach a functional gateway. The primary contribution is a novel, energy-aware routing protocol optimized for highly volatile, post-disaster network topologies, ensuring critical SOS messages and resource requests reach coordination centers despite intermittent connectivity. |
| **3. Target Domain** | Networking, Disaster Risk Reduction, Telecommunications |
| **4. Statement of the Problem (SOP)** | 1. What opportunistic routing algorithms provide the highest message delivery probability and lowest latency in highly volatile, sparse mesh networks? <br> 2. How can energy consumption be dynamically balanced across heterogeneous nodes (low-power IoT vs. battery-rich smartphones) to prolong overall network survivability? <br> 3. How does the system prevent message duplication and ensure data integrity without relying on a centralized coordination server? |
| **5. Technologies** | C++, Go, LoRa (Meshtastic), Android Wi-Fi Direct/Bluetooth APIs, DTN Protocols (Bundle Protocol), NS-3 Simulator |
| **6. Research Category** | Networking, Distributed Systems, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Routing Protocol Implementation, Network Simulation Results, Mobile App Prototype |
| **10. Possible Future Extensions** | Integration with UAV (drone) swarms for automated aerial data muling, cryptographic message prioritization for emergency services. |
| **11. References / Inspiration** | Delay-Tolerant Networking (DTN) RFCs, Meshtastic documentation, research on post-disaster opportunistic networks. |

## Idea 29
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Zero-Shot Robotic Manipulation in Unstructured Warehouse Environments Using Vision-Language-Action (VLA) Foundation Models |
| **2. Description** | Traditional robotic manipulation requires extensive task-specific programming and fails when encountering novel objects in unstructured environments. This research investigates the application of Vision-Language-Action (VLA) models to enable zero-shot or few-shot robotic manipulation based on natural language commands. By fine-tuning an open-source VLA model on a custom dataset of robotic arm interactions, the system learns to map visual observations and text instructions directly to continuous robot control actions. The expected contribution is a practical framework for deploying foundation models in physical warehouse environments, significantly reducing the engineering overhead required for robotic task generalization and improving supply chain automation. |
| **3. Target Domain** | Robotics, Artificial Intelligence, Logistics |
| **4. Statement of the Problem (SOP)** | 1. How do Vision-Language-Action (VLA) models perform in zero-shot manipulation tasks compared to traditional reinforcement learning approaches in unstructured environments? <br> 2. What data collection and fine-tuning strategies are most effective for adapting large VLA models to specific, low-cost robotic hardware? <br> 3. How can the system ensure safe physical interactions and prevent destructive actions when the VLA model encounters out-of-distribution visual inputs? |
| **5. Technologies** | Python, PyTorch, ROS 2, OpenVLA / Hugging Face, Isaac Sim / Gazebo, Universal Robots / Arduino Robotic Arm |
| **6. Research Category** | Robotics, Computer Vision, Artificial Intelligence |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Fine-tuned VLA Model, Robotic Control Pipeline, Simulation vs. Real-World Evaluation |
| **10. Possible Future Extensions** | Multi-robot collaboration via shared language models, integration with tactile sensors for closed-loop force feedback during manipulation. |
| **11. References / Inspiration** | OpenVLA / RT-2 research papers, ROS 2 manipulation packages, NVIDIA Isaac Sim documentation. |

## Idea 30
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Privacy-Preserving Credit Scoring for Unbanked Populations Using Federated Learning on Decentralized Alternative Data |
| **2. Description** | Access to credit is often denied to individuals with thin traditional financial histories, while utilizing alternative data (e.g., mobile usage, utility payments) raises severe privacy concerns. This thesis proposes a privacy-preserving credit scoring system utilizing Federated Learning (FL) and secure multi-party computation. Financial institutions and alternative data providers collaboratively train a credit risk model without ever sharing raw customer transaction logs or personal identifiers. The primary contribution is a robust FL framework tailored for highly imbalanced, tabular financial data, enabling the creation of inclusive, highly accurate credit models while strictly adhering to data privacy regulations like GDPR. |
| **3. Target Domain** | FinTech, Data Science, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. What aggregation algorithms in Federated Learning best handle the highly non-IID and imbalanced nature of tabular financial data across different institutions? <br> 2. How can differential privacy be integrated into the FL pipeline to prevent model inversion attacks and protect individual data points? <br> 3. How does the predictive performance of the federated credit scoring model compare to a centralized model trained on pooled, raw data? |
| **5. Technologies** | Python, PySyft / Flower, XGBoost / LightGBM, Pandas, Secure Enclaves (Intel SGX), PostgreSQL |
| **6. Research Category** | Artificial Intelligence, Data Science, Distributed Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Federated Learning Pipeline, Credit Scoring Model, Privacy Audit Report |
| **10. Possible Future Extensions** | Integration with decentralized finance (DeFi) smart contracts for automated micro-loan disbursement, cross-border federated credit systems. |
| **11. References / Inspiration** | Flower framework documentation, research on federated learning for tabular data, GDPR compliance guidelines for AI. |

# Curated Undergraduate Computer Science Thesis Ideas (Batch 4 of 20)

## Idea 31
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Quantum-Enhanced Feature Selection for High-Dimensional Genomic Data Classification Using Hybrid Classical-Quantum Pipelines |
| **2. Description** | Genomic datasets, such as RNA-Seq, suffer from the "curse of dimensionality," containing tens of thousands of gene expression features but relatively few patient samples. Classical machine learning models often overfit or struggle to identify the most biologically relevant gene markers. This research explores a hybrid classical-quantum pipeline utilizing Variational Quantum Eigensolvers (VQE) or Quantum Support Vector Machines (QSVM) to perform feature selection on high-dimensional genomic data. By mapping feature selection to a Quadratic Unconstrained Binary Optimization (QUBO) problem, the quantum processor can efficiently search the combinatorial space for optimal gene subsets. The primary contribution is a comparative analysis of quantum versus classical feature selection methods, demonstrating how near-term Noisy Intermediate-Scale Quantum (NISQ) devices can accelerate biomarker discovery in precision medicine. |
| **3. Target Domain** | Bioinformatics, Quantum Computing, Healthcare |
| **4. Statement of the Problem (SOP)** | 1. How can high-dimensional genomic feature selection be effectively mapped to a QUBO formulation for quantum annealers or gate-based quantum computers? <br> 2. How do hybrid classical-quantum feature selection pipelines compare to classical algorithms (e.g., LASSO, Random Forests) in terms of classification accuracy and computational overhead? <br> 3. What error mitigation techniques are necessary to maintain feature selection stability on noisy NISQ hardware? |
| **5. Technologies** | Python, Qiskit, PennyLane, Scikit-learn, QUBO Solvers, RNA-Seq Datasets (e.g., TCGA) |
| **6. Research Category** | Quantum Computing, Artificial Intelligence, Bioinformatics |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Hybrid Quantum-Classical Pipeline, Biomarker Analysis Report, Benchmarking Framework |
| **10. Possible Future Extensions** | Integration with quantum machine learning for survival analysis, application to proteomics and metabolomics data. |
| **11. References / Inspiration** | IBM Quantum documentation, PennyLane quantum machine learning demos, literature on QUBO formulations for feature selection. |

## Idea 32
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Indoor Navigation and Obstacle Avoidance for the Visually Impaired Using Spatial Audio and Edge-Based Visual SLAM |
| **2. Description** | GPS-based navigation is ineffective indoors, leaving visually impaired individuals vulnerable to dynamic obstacles and complex architectural layouts. This thesis proposes a wearable navigation system that utilizes edge-based Visual Simultaneous Localization and Mapping (vSLAM) via a stereo-camera rig to map indoor environments in real-time. Instead of relying on visual displays, the system translates spatial depth data and navigational waypoints into 3D spatial audio cues (earcons) and haptic feedback. The expected contribution is a low-latency, cognitively intuitive sensory substitution interface that allows users to safely navigate unmapped indoor spaces, significantly enhancing independence and accessibility in public buildings. |
| **3. Target Domain** | Accessibility, Human-Computer Interaction, Robotics |
| **4. Statement of the Problem (SOP)** | 1. How can vSLAM algorithms be optimized to run with minimal latency on edge computing devices while maintaining localization accuracy? <br> 2. What spatial audio rendering techniques minimize cognitive load and prevent auditory masking in noisy indoor environments? <br> 3. How does the system effectively differentiate between static architectural features (walls, stairs) and dynamic obstacles (moving people) for accurate haptic/audio alerting? |
| **5. Technologies** | C++, ROS 2, ORB-SLAM3, Intel RealSense, Spatial Audio APIs, Edge AI Hardware |
| **6. Research Category** | Human-Computer Interaction, Computer Vision, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Wearable Prototype, Spatial Audio Engine, User Study Evaluation |
| **10. Possible Future Extensions** | Integration with semantic segmentation for audio labeling of objects (e.g., "chair on left"), outdoor-to-indoor seamless navigation transitions. |
| **11. References / Inspiration** | ORB-SLAM3 documentation, research on sensory substitution for the blind, spatial audio psychoacoustics literature. |

## Idea 33
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | V2X Message Authentication and Anomaly Detection in Connected Vehicles Using Hardware Security Modules and Lightweight PKI |
| **2. Description** | Vehicle-to-Everything (V2X) communication relies on the continuous broadcast of Basic Safety Messages (BSMs) to prevent collisions. However, these networks are highly vulnerable to Sybil attacks, message spoofing, and replay attacks. Traditional Public Key Infrastructure (PKI) is often too computationally heavy for the high-frequency, low-latency requirements of V2X. This research proposes a lightweight PKI architecture integrated with vehicular Hardware Security Modules (HSMs) for secure, high-speed cryptographic signing. Furthermore, it implements an edge-based machine learning anomaly detection system to identify rogue vehicles broadcasting falsified kinematic data. The contribution is a comprehensive, hardware-backed security framework that ensures the integrity of autonomous vehicular networks. |
| **3. Target Domain** | Cybersecurity, Automotive Engineering, IoT |
| **4. Statement of the Problem (SOP)** | 1. What is the exact latency overhead of utilizing HSMs for high-frequency BSM signing compared to software-based cryptographic implementations? <br> 2. How can a lightweight PKI architecture efficiently manage certificate revocation lists (CRLs) in highly dynamic, fast-moving vehicular networks? <br> 3. What time-series anomaly detection models best identify spoofed kinematic data (e.g., false acceleration or position) without generating excessive false positives? |
| **5. Technologies** | C++, AUTOSAR, OpenSSL, SUMO (Traffic Simulator), Wireshark, Machine Learning (Isolation Forests) |
| **6. Research Category** | Cybersecurity, Networking, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | V2X Security Simulator, Lightweight PKI Protocol, Anomaly Detection Model |
| **10. Possible Future Extensions** | Integration with 5G network slicing for prioritized security traffic, blockchain-based decentralized trust management for V2X. |
| **11. References / Inspiration** | IEEE 1609.2 V2X security standards, SUMO V2X simulation documentation, automotive HSM architecture papers. |

## Idea 34
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Refactoring of Legacy Monoliths into Microservices Using LLM-Driven Dependency Graph Analysis |
| **2. Description** | Migrating legacy monolithic applications to microservices is a highly manual, error-prone process that requires deep domain knowledge to identify bounded contexts. This thesis proposes an automated refactoring assistant that combines Large Language Models (LLMs) with static code analysis to parse legacy codebases and construct a comprehensive dependency graph. By applying graph clustering algorithms to this LLM-enriched graph, the system recommends optimal microservice boundaries, identifies shared databases, and suggests data migration strategies. The primary contribution is an AI-assisted software engineering tool that drastically reduces the architectural debt and planning time required for enterprise cloud modernization. |
| **3. Target Domain** | Software Engineering, Artificial Intelligence, Cloud Computing |
| **4. Statement of the Problem (SOP)** | 1. How accurately can LLMs infer implicit business logic and bounded contexts from legacy source code and database schemas? <br> 2. What graph clustering algorithms yield the most cohesive and loosely coupled microservice boundaries based on static dependency graphs? <br> 3. How can the system automatically generate data migration scripts and API gateway configurations based on the recommended refactoring architecture? |
| **5. Technologies** | Python, LangChain, Neo4j (Graph DB), AST Parsers, Docker, Llama-3 / GPT-4 API |
| **6. Research Category** | Software Engineering, Natural Language Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Refactoring Analysis Tool, Dependency Graph Visualizer, Migration Recommendation Engine |
| **10. Possible Future Extensions** | Automated generation of infrastructure-as-code (Terraform) for the proposed microservices, continuous architectural drift monitoring. |
| **11. References / Inspiration** | Domain-Driven Design (DDD) principles, research on automated microservice extraction, LangChain graph integrations. |

## Idea 35
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Predicting Urban Heat Island (UHI) Effects Using Digital Twin and Microclimate Simulation Driven by IoT Sensor Fusion |
| **2. Description** | Urban Heat Islands (UHI) exacerbate energy consumption and pose severe public health risks during heatwaves. City planners lack hyper-local, real-time tools to evaluate the impact of urban design on microclimates. This research develops a localized Digital Twin that fuses data from a network of low-cost IoT temperature and humidity sensors with 3D city building geometry and traffic density APIs. By feeding this real-time data into a simplified computational fluid dynamics (CFD) or machine learning surrogate model, the system predicts hyper-local temperature variations and simulates the cooling impact of proposed interventions (e.g., adding green roofs or changing pavement materials). The contribution is an actionable, data-driven urban planning dashboard for climate-resilient city design. |
| **3. Target Domain** | Smart Cities, Environmental Science, Civil Engineering |
| **4. Statement of the Problem (SOP)** | 1. How can low-cost IoT environmental sensors be dynamically calibrated against reference meteorological stations to ensure data reliability? <br> 2. What surrogate machine learning models can accurately approximate complex CFD microclimate simulations in real-time for interactive urban planning? <br> 3. How do different urban geometries and material albedos quantitatively impact localized UHI severity under varying traffic congestion levels? |
| **5. Technologies** | Python, Unity3D / NVIDIA Omniverse, OpenFOAM, LoRaWAN, TimescaleDB, GIS Data |
| **6. Research Category** | Data Science, Internet of Things (IoT), Environmental Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Digital Twin Dashboard, IoT Sensor Network, Predictive Microclimate Model |
| **10. Possible Future Extensions** | Integration with smart grid data to correlate UHI with peak cooling energy demand, AR visualization for urban planners on-site. |
| **11. References / Inspiration** | OpenFOAM documentation, urban microclimate research papers, digital twin frameworks for smart cities. |

## Idea 36
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | AlphaFold-Inspired Protein-Ligand Binding Affinity Prediction Using 3D Equivariant Graph Neural Networks for Targeted Drug Repurposing |
| **2. Description** | Drug repurposing—finding new therapeutic uses for existing, approved drugs—significantly accelerates the drug discovery pipeline. However, predicting how a known drug molecule (ligand) binds to a novel protein target requires understanding complex 3D spatial geometries, which traditional molecular dynamics simulations handle too slowly. This thesis applies 3D Equivariant Graph Neural Networks (such as EGNN or SchNet) to predict protein-ligand binding affinity directly from 3D structural data. The primary contribution is a highly scalable, deep learning-based screening pipeline that identifies high-probability drug repurposing candidates without the massive computational cost of physics-based simulations, democratizing early-stage pharmacological research. |
| **3. Target Domain** | Bioinformatics, Artificial Intelligence, Pharmacology |
| **4. Statement of the Problem (SOP)** | 1. How do 3D equivariant graph neural networks outperform standard 2D graph convolutional networks in capturing spatial molecular interactions? <br> 2. How can the model effectively account for the conformational flexibility and induced-fit effects of protein binding pockets? <br> 3. What is the generalization capability of the model when predicting binding affinities for entirely unseen protein targets and novel ligand scaffolds? |
| **5. Technologies** | Python, PyTorch Geometric, RDKit, PyMOL, PDBbind Dataset, Hugging Face |
| **6. Research Category** | Artificial Intelligence, Bioinformatics, Data Science |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | 3D GNN Prediction Model, Drug Repurposing Pipeline, Benchmarking Analysis |
| **10. Possible Future Extensions** | Integration with generative AI for de novo ligand optimization, multi-target polypharmacology modeling. |
| **11. References / Inspiration** | AlphaFold database, PyTorch Geometric documentation, literature on 3D equivariant neural networks (e.g., Satorras et al.). |

## Idea 37
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Cross-Chain Interoperability Protocol for Tracking Conflict-Free Minerals Using Zero-Knowledge Rollups |
| **2. Description** | Global supply chains for critical minerals (e.g., cobalt, lithium) span multiple jurisdictions and blockchain networks, making it difficult to verify ethical sourcing without exposing sensitive corporate trade secrets. This thesis designs a cross-chain interoperability protocol utilizing Zero-Knowledge Rollups (ZK-Rollups) to aggregate and verify supply chain events across different ledgers. By generating cryptographic proofs that a mineral batch complies with conflict-free regulations without revealing the exact origin, volume, or buyer, the system ensures privacy and scalability. The expected contribution is a secure, privacy-preserving framework for ESG (Environmental, Social, and Governance) compliance that enables seamless, trustless data transfer between disparate enterprise blockchains. |
| **3. Target Domain** | Blockchain, Supply Chain, FinTech |
| **4. Statement of the Problem (SOP)** | 1. How can Zero-Knowledge circuits be optimized to efficiently prove complex supply chain compliance rules (e.g., mass balance, origin verification)? <br> 2. What cross-chain messaging architectures ensure secure and atomic verification of ZK proofs between heterogeneous blockchain networks? <br> 3. How does the computational overhead of generating and verifying ZK-Rollups impact the overall throughput and latency of a global supply chain network? |
| **5. Technologies** | Solidity, Circom / SnarkyJS, Polygon / Ethereum, Chainlink CCIP, React, IPFS |
| **6. Research Category** | Distributed Systems, Cybersecurity, Supply Chain Management |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | ZK Circuit Designs, Cross-Chain Smart Contracts, Privacy Audit Report |
| **10. Possible Future Extensions** | Integration with automated customs and border control APIs, extension to carbon footprint tracking and carbon credit retirement. |
| **11. References / Inspiration** | Zero-Knowledge proof documentation (zkSync, StarkNet), W3C Supply Chain standards, cross-chain interoperability protocols. |

## Idea 38
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Detecting AI-Generated Plagiarism in Coding Assignments Using Stylometric Analysis and Execution Trace Comparison |
| **2. Description** | The widespread availability of Large Language Models (LLMs) has rendered traditional code plagiarism detection tools (like MOSS) largely ineffective, as AI can easily generate syntactically unique but logically identical solutions. This thesis proposes a novel detection framework that analyzes both code stylometry (e.g., AST depth, variable naming entropy, comment structure) and runtime execution traces (e.g., memory allocation patterns, branch coverage, system calls) inside a sandboxed environment. By training a classifier on the behavioral and structural fingerprints of AI-generated code versus human-written code, the system provides educators with a robust tool to maintain academic integrity in computer science programs. |
| **3. Target Domain** | Education, Cybersecurity, Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. What specific Abstract Syntax Tree (AST) and stylometric features uniquely characterize code generated by state-of-the-art LLMs compared to novice human programmers? <br> 2. How do runtime execution traces (memory and CPU profiles) differ between human-optimized and AI-generated algorithms? <br> 3. What is the false-positive rate of the proposed detection system across varying student skill levels and different programming paradigms (OOP vs. Functional)? |
| **5. Technologies** | Python, AST Parsers, Docker (for sandboxing), Scikit-learn, Valgrind, MOSS API |
| **6. Research Category** | Software Engineering, Artificial Intelligence, Education |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | Plagiarism Detection Engine, Sandboxed Execution Environment, Academic Dataset |
| **10. Possible Future Extensions** | Real-time IDE plugin for formative feedback, detection of AI-assisted code obfuscation techniques, integration with university LMS platforms. |
| **11. References / Inspiration** | Research on code stylometry, LLM code generation benchmarks, academic integrity guidelines in CS education. |

## Idea 39
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Vision-Guided Precision Micro-Dosing of Herbicides Using Edge AI and Robotic Actuation for Sustainable Agriculture |
| **2. Description** | Blanket application of herbicides in agriculture leads to chemical runoff, soil degradation, and the evolution of herbicide-resistant weeds. This research develops an autonomous agricultural rover equipped with edge-based computer vision and a precision micro-dosing actuation system. Using optimized YOLO models, the rover identifies weeds in real-time amidst dense crop canopies and triggers targeted micro-sprayers or localized laser emitters only on the identified weeds. The primary contribution is a highly accurate, low-latency perception-to-actuation pipeline that drastically reduces chemical usage, promoting sustainable farming practices and lowering operational costs for small-to-medium-scale farmers. |
| **3. Target Domain** | Agriculture, Robotics, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can Edge AI models maintain high classification accuracy for weed detection under varying lighting conditions and severe occlusion in dense crop canopies? <br> 2. What is the optimal control loop latency required to accurately align a micro-dosing actuator with a moving target on an uneven agricultural terrain? <br> 3. How does the reduction in chemical volume achieved by precision micro-dosing correlate with overall crop yield and weed suppression rates? |
| **5. Technologies** | Python, ROS 2, NVIDIA Jetson, YOLOv8, Arduino, Solenoid Valves / Laser Modules, OpenCV |
| **6. Research Category** | Robotics, Computer Vision, Embedded Systems |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Autonomous Rover Prototype, Vision-Guided Actuation System, Field Trial Report |
| **10. Possible Future Extensions** | Swarm robotics for large-scale field coverage, integration with multispectral imaging for plant health assessment, automated crop harvesting. |
| **11. References / Inspiration** | Precision agriculture literature, ROS 2 navigation stacks, YOLO object detection benchmarks for agriculture. |

## Idea 40
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Cold-Start Mitigation in Serverless Computing Using Predictive Pre-warming Based on Time-Series Forecasting of API Gateway Traffic |
| **2. Description** | Serverless architectures offer immense scalability but suffer from "cold starts"—the latency incurred when initializing a new container to handle a request. This latency severely impacts user experience in real-time applications. This thesis proposes a predictive pre-warming system that analyzes API gateway traffic patterns using advanced time-series forecasting models (e.g., Temporal Fusion Transformers). By predicting impending traffic bursts, the system proactively initializes and keeps containers warm before requests arrive. The expected contribution is a dynamic, cost-effective scaling algorithm that minimizes cold-start latency while preventing the excessive financial overhead of keeping unnecessary containers perpetually active. |
| **3. Target Domain** | Cloud Computing, Distributed Systems, Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. How accurately can Temporal Fusion Transformers predict bursty, non-stationary API traffic patterns compared to traditional ARIMA or Prophet models? <br> 2. What is the optimal trade-off between the financial cost of pre-warming containers and the performance penalty of cold starts under varying SLA requirements? <br> 3. How can the predictive pre-warming system be seamlessly integrated into existing Kubernetes auto-scalers (e.g., Knative, KEDA) without disrupting standard scaling logic? |
| **5. Technologies** | Go, Kubernetes, Knative / KEDA, Prometheus, PyTorch (Time-Series), Grafana |
| **6. Research Category** | Cloud Computing, Distributed Systems, Artificial Intelligence |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Predictive Auto-scaler Plugin, Traffic Forecasting Model, Cost-Latency Analysis Report |
| **10. Possible Future Extensions** | Integration with spot-instance pricing for financial optimization, multi-tenant predictive scaling in shared cloud environments. |
| **11. References / Inspiration** | Knative documentation, research on serverless cold-start mitigation, Temporal Fusion Transformer architecture papers. |


# Curated Undergraduate Computer Science Thesis Ideas (Batch 5 of 20)

## Idea 41
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Decentralized Peer-to-Peer Energy Trading in Microgrids Using Multi-Agent Reinforcement Learning and Blockchain Smart Contracts |
| **2. Description** | Microgrids enable localized renewable energy generation, but surplus energy is often wasted or sold back to the main grid at suboptimal rates. This research proposes a Peer-to-Peer (P2P) energy trading platform utilizing Multi-Agent Reinforcement Learning (MARL) and blockchain smart contracts. Prosumers (producers and consumers) deploy MARL agents to dynamically optimize their bidding and pricing strategies based on local supply, demand, and weather forecasts. The blockchain ensures transparent, trustless settlement of micro-transactions without a centralized utility broker. The primary contribution is a decentralized market mechanism that maximizes local renewable utilization and financial returns for prosumers while maintaining local grid stability and minimizing transmission losses. |
| **3. Target Domain** | Smart Grids, Renewable Energy, FinTech |
| **4. Statement of the Problem (SOP)** | 1. How can MARL agents optimize bidding strategies in a highly volatile, decentralized P2P energy market with non-stationary reward functions? <br> 2. What smart contract architectures minimize transaction fees and latency for high-frequency micro-transactions in localized energy trading? <br> 3. How does the proposed decentralized trading system maintain local grid voltage and frequency stability during sudden shifts in P2P energy routing? |
| **5. Technologies** | Python, PyTorch (RLlib), Solidity, Hyperledger Fabric / Polygon, GridLAB-D Simulator, MQTT |
| **6. Research Category** | Artificial Intelligence, Distributed Systems, Energy Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | MARL Trading Agents, Smart Contract Suite, Microgrid Simulation Environment, Economic Analysis Report |
| **10. Possible Future Extensions** | Integration with electric vehicle (EV) vehicle-to-grid (V2G) systems, predictive battery degradation modeling for trading agents. |
| **11. References / Inspiration** | GridLAB-D documentation, research on MARL in energy markets, ERC-20 token standards for utility billing. |

## Idea 42
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Privacy-Preserving Extraction of Social Determinants of Health (SDOH) from Unstructured Clinical Notes Using Federated Large Language Models |
| **2. Description** | Social Determinants of Health (SDOH)—such as housing instability, food insecurity, and transportation access—profoundly impact patient outcomes but are rarely captured in structured Electronic Health Records (EHR). This thesis develops an NLP pipeline using fine-tuned, privacy-preserving Large Language Models to automatically extract and categorize SDOH from unstructured clinical notes. By employing federated learning, the model can be trained across multiple hospital networks without exposing Protected Health Information (PHI) or centralizing sensitive text data. The expected contribution is a highly accurate, HIPAA-compliant extraction tool that enables healthcare providers to identify at-risk populations and deploy targeted social interventions without violating patient privacy. |
| **3. Target Domain** | Healthcare, Natural Language Processing, Bioinformatics |
| **4. Statement of the Problem (SOP)** | 1. What prompting and parameter-efficient fine-tuning (PEFT) strategies maximize the extraction accuracy of implicit SDOH indicators from highly unstructured, noisy clinical text? <br> 2. How can federated aggregation algorithms handle the severe non-IID nature of clinical documentation styles across different hospital departments? <br> 3. How does the automated extraction of SDOH features impact the predictive accuracy of hospital readmission and mortality risk models? |
| **5. Technologies** | Python, Hugging Face Transformers, PySyft / Flower, spaCy, MIMIC-IV Dataset, FastAPI |
| **6. Research Category** | Natural Language Processing, Artificial Intelligence, Healthcare Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Federated NLP Pipeline, SDOH Extraction Model, Predictive Risk Model Integration |
| **10. Possible Future Extensions** | Multilingual SDOH extraction for diverse patient populations, automated generation of social work referral drafts based on extracted risks. |
| **11. References / Inspiration** | MIMIC-IV clinical notes, literature on SDOH impact on readmissions, federated learning for NLP frameworks. |

## Idea 43
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Architecture-Agnostic Firmware Vulnerability Detection in IoT Devices Using Binary Code Similarity and Graph Neural Networks |
| **2. Description** | The proliferation of IoT devices has expanded the attack surface, with many devices running outdated, unpatched firmware. Traditional static analysis tools struggle with the diverse instruction set architectures (ARM, MIPS, RISC-V) and stripped binaries typical of IoT firmware. This research proposes a vulnerability detection framework that converts compiled IoT binaries into Control Flow Graphs (CFGs) and applies Graph Neural Networks (GNNs) to identify malicious patterns or known vulnerabilities (e.g., buffer overflows, use-after-free). By training on a diverse dataset of cross-architecture binaries, the system achieves architecture-agnostic vulnerability detection. The primary contribution is a scalable, automated binary analysis tool that significantly improves the security auditing of closed-source IoT ecosystems. |
| **3. Target Domain** | Cybersecurity, Internet of Things (IoT), Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. How can Control Flow Graphs (CFGs) be normalized to enable cross-architecture vulnerability detection using Graph Neural Networks? <br> 2. What graph embedding techniques best capture the semantic and structural properties of stripped IoT binaries lacking symbol tables? <br> 3. How does the proposed GNN-based framework compare to traditional symbolic execution tools in terms of false-positive rates and computational overhead? |
| **5. Technologies** | Python, PyTorch Geometric, Ghidra / Radare2, NetworkX, Binary Analysis Datasets, Docker |
| **6. Research Category** | Cybersecurity, Artificial Intelligence, Software Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Binary-to-Graph Pipeline, GNN Vulnerability Classifier, Cross-Architecture Benchmark Dataset |
| **10. Possible Future Extensions** | Integration with CI/CD pipelines for automated firmware auditing, automated generation of proof-of-concept exploits for detected vulnerabilities. |
| **11. References / Inspiration** | Ghidra reverse engineering documentation, research on binary code similarity, GNN applications in program analysis. |

## Idea 44
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Early Detection of Crop Nutrient Deficiencies Using Hyperspectral Imaging and Physics-Informed Neural Networks (PINNs) |
| **2. Description** | Visual symptoms of crop nutrient deficiencies often appear only after significant yield loss has occurred. This thesis proposes an early detection system utilizing hyperspectral imaging combined with Physics-Informed Neural Networks (PINNs). Unlike standard deep learning models that treat spectral data purely statistically, PINNs integrate known biophysical models of plant light reflectance and chlorophyll absorption into the neural network's loss function. This hybrid approach allows the system to accurately quantify specific nutrient levels (Nitrogen, Phosphorus, Potassium) before visible symptoms manifest. The expected contribution is a highly robust, interpretable AI model that bridges the gap between remote sensing physics and data-driven agriculture, enabling precise, preemptive fertilizer application. |
| **3. Target Domain** | Agriculture, Environmental Science, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can biophysical models of plant canopy reflectance be mathematically integrated into the loss functions of Physics-Informed Neural Networks (PINNs)? <br> 2. How do PINNs compare to standard Convolutional Neural Networks in generalizing crop nutrient predictions across different growth stages and environmental lighting conditions? <br> 3. What is the minimum spectral resolution required to accurately differentiate between macro and micronutrient deficiencies using this physics-driven approach? |
| **5. Technologies** | Python, PyTorch, Scikit-Image, PROSAIL Radiative Transfer Model, Hyperspectral Datasets, OpenCV |
| **6. Research Category** | Artificial Intelligence, Remote Sensing, Precision Agriculture |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | PINN Nutrient Model, Hyperspectral Data Pipeline, Field Validation Report |
| **10. Possible Future Extensions** | Deployment on UAV-based multispectral cameras, integration with automated variable-rate fertilizer application machinery. |
| **11. References / Inspiration** | PROSAIL model documentation, literature on Physics-Informed Neural Networks (Karniadakis et al.), hyperspectral agriculture datasets. |

## Idea 45
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Decentralized UAV Swarm Coordination for Post-Disaster Search and Rescue Using Federated Deep Reinforcement Learning |
| **2. Description** | Search and Rescue (SAR) operations in post-disaster environments are hindered by destroyed communication infrastructure and vast, unstructured search areas. This research develops a decentralized coordination protocol for Unmanned Aerial Vehicle (UAV) swarms utilizing Federated Deep Reinforcement Learning (FDRL). Each UAV explores its local environment, detecting survivors via thermal and visual sensors, and shares only model weight updates with neighboring drones via an ad-hoc mesh network. This enables the swarm to collaboratively learn optimal search patterns and survivor localization strategies without relying on a central command server. The primary contribution is a resilient, bandwidth-efficient swarm intelligence framework that drastically reduces search times in GPS-denied, communication-degraded disaster zones. |
| **3. Target Domain** | Disaster Risk Reduction, Robotics, Networking |
| **4. Statement of the Problem (SOP)** | 1. How can FDRL algorithms maintain convergence and cooperative behavior in highly volatile, intermittent ad-hoc mesh networks? <br> 2. What reward functions best balance the trade-off between exploration of unknown areas and exploitation of detected survivor clusters in a UAV swarm? <br> 3. How does the system dynamically reconfigure search patterns and redistribute coverage when individual UAVs fail or run out of battery? |
| **5. Technologies** | Python, ROS 2, PyTorch, AirSim / Gazebo, Multi-Agent RL (MADDPG), LoRa / Wi-Fi Mesh |
| **6. Research Category** | Robotics, Artificial Intelligence, Distributed Systems |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Swarm Simulation Environment, FDRL Coordination Algorithm, Network Resilience Analysis |
| **10. Possible Future Extensions** | Integration with heterogeneous swarms (UAVs and ground rovers), acoustic payload integration for detecting calls for help under rubble. |
| **11. References / Inspiration** | AirSim multi-vehicle documentation, research on federated reinforcement learning, swarm robotics coordination literature. |

## Idea 46
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Detection of Synthetic Identity Fraud in Digital Financial Onboarding Using Graph Neural Networks and Generative Adversarial Networks |
| **2. Description** | Synthetic identity fraud, where criminals combine real and fabricated information to create new, fictitious identities, is a rapidly growing financial crime. Traditional rule-based systems fail to detect these identities because they lack a historical credit footprint. This thesis proposes a detection framework that combines Graph Neural Networks (GNNs) to map the hidden relationships between shared PII (e.g., phone numbers, addresses, IP addresses) across multiple applications, alongside Generative Adversarial Networks (GANs) to simulate synthetic fraud patterns for robust model training. The expected contribution is a highly proactive, graph-based fraud detection engine that identifies synthetic identity rings during the digital onboarding process before credit lines are extended. |
| **3. Target Domain** | FinTech, Cybersecurity, Data Science |
| **4. Statement of the Problem (SOP)** | 1. How can Graph Neural Networks effectively identify latent, multi-hop relationships between seemingly unrelated loan applications to detect synthetic identity rings? <br> 2. What GAN architectures are most effective at generating realistic synthetic fraud datasets to overcome the severe class imbalance and lack of labeled training data? <br> 3. How does the integration of graph-based topological features improve the precision-recall trade-off compared to traditional tabular feature engineering in fraud detection? |
| **5. Technologies** | Python, PyTorch Geometric, Neo4j, Scikit-learn, GANs, Synthetic Financial Datasets |
| **6. Research Category** | Artificial Intelligence, Cybersecurity, FinTech |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | GNN Fraud Detection Model, GAN Data Augmentation Pipeline, Graph Database Schema |
| **10. Possible Future Extensions** | Real-time streaming graph analytics for transaction monitoring, integration with decentralized identity (DID) verification protocols. |
| **11. References / Inspiration** | Graph neural network literature for fraud detection, GANs for tabular data generation, financial crime regulatory reports. |

## Idea 47
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Generation of API Documentation and Client SDKs from Source Code Using AST Parsing and Code-Specialized LLMs |
| **2. Description** | Maintaining accurate, up-to-date API documentation and Software Development Kits (SDKs) is a persistent challenge in fast-paced software development, often leading to developer frustration and integration errors. This thesis proposes an automated documentation generator that parses Abstract Syntax Trees (ASTs) and utilizes Code-specialized Large Language Models to infer endpoint behaviors, parameter constraints, and edge cases directly from the source code and unit tests. The system automatically generates OpenAPI (Swagger) specifications, interactive web documentation, and client SDKs in multiple languages. The primary contribution is a continuous integration tool that ensures documentation remains perfectly synchronized with the codebase, drastically reducing technical debt and improving developer experience (DX). |
| **3. Target Domain** | Software Engineering, Artificial Intelligence, DevOps |
| **4. Statement of the Problem (SOP)** | 1. How accurately can Code LLMs infer implicit API constraints, authentication requirements, and edge cases from ASTs and unit tests without explicit developer annotations? <br> 2. What AST parsing strategies are most effective for handling complex, multi-language microservice architectures and dynamic typing? <br> 3. How does automated documentation generation impact developer onboarding time and API integration error rates compared to manually maintained documentation? |
| **5. Technologies** | Python, Tree-sitter (AST Parsing), CodeLlama / StarCoder, OpenAPI Generator, Docker, GitHub Actions |
| **6. Research Category** | Software Engineering, Natural Language Processing |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | CI/CD Documentation Plugin, AST-to-OpenAPI Engine, Empirical DX Evaluation Report |
| **10. Possible Future Extensions** | Automated generation of Postman collections and mock servers, self-healing documentation that updates based on production traffic analysis. |
| **11. References / Inspiration** | Tree-sitter documentation, OpenAPI specification standards, research on LLMs for software maintenance. |

## Idea 48
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Distributed Acoustic Monitoring of Deforestation and Illegal Logging Using Edge AI and LoRaWAN Mesh Networking in Remote Forests |
| **2. Description** | Illegal logging in remote, densely forested regions often goes undetected until massive ecological damage has occurred. Satellite imagery is frequently obstructed by cloud cover, and real-time video monitoring requires prohibitive bandwidth. This thesis develops a distributed acoustic sensor network utilizing Edge AI to detect the specific audio signatures of chainsaws, heavy machinery, and unauthorized vehicle movement. By deploying TinyML models on solar-powered microcontrollers, the nodes process audio locally and transmit only compressed alert metadata via LoRaWAN mesh networks. The expected contribution is a highly scalable, low-power, and weather-independent early warning system that enables rapid ranger deployment to intercept illegal logging operations in real-time. |
| **3. Target Domain** | Environmental Science, Internet of Things (IoT), Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can TinyML models accurately isolate anthropogenic machinery sounds from complex, high-decibel natural forest ambient noise (e.g., heavy rain, cicadas)? <br> 2. What LoRaWAN mesh routing protocols maximize the delivery rate of critical alert metadata in dense, topographically complex forest environments? <br> 3. How can the system accurately triangulate the location of acoustic events using asynchronous, low-cost microcontrollers without GPS synchronization? |
| **5. Technologies** | C/C++, TensorFlow Lite Micro, Edge Impulse, ESP32, LoRaWAN, I2S MEMS Microphones, Solar Power Management |
| **6. Research Category** | Embedded Systems, Audio Processing, Internet of Things (IoT) |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Solar-Powered Sensor Node, TinyML Audio Classifier, Ranger Alert Dashboard |
| **10. Possible Future Extensions** | Integration with automated PTZ (Pan-Tilt-Zoom) camera traps, acoustic detection of specific endangered species for biodiversity monitoring. |
| **11. References / Inspiration** | Rainforest Connection (RFCx) architecture, Edge Impulse audio classification tutorials, LoRaWAN mesh networking protocols. |

## Idea 49
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Adaptive Virtual Reality (VR) Laboratory Simulations for STEM Education Using Eye-Tracking and Real-Time Cognitive Load Estimation |
| **2. Description** | Virtual Reality (VR) offers immersive STEM laboratory simulations, but poorly designed interfaces can induce cognitive overload, nausea, and diminished learning outcomes. This research proposes an adaptive VR laboratory environment that utilizes integrated eye-tracking and physiological sensors (heart rate variability) to estimate the user's real-time cognitive load. Based on this continuous assessment, the system dynamically adjusts the complexity of the simulation, the density of UI elements, and the pacing of instructional prompts. The primary contribution is a closed-loop, biologically responsive educational framework that optimizes the learning curve for individual students, making complex scientific concepts more accessible and reducing VR-induced fatigue. |
| **3. Target Domain** | Education, Human-Computer Interaction, Virtual Reality |
| **4. Statement of the Problem (SOP)** | 1. How accurately can real-time cognitive load be estimated using a fusion of eye-tracking metrics (pupil dilation, saccade velocity) and physiological signals in a VR environment? <br> 2. What adaptive UI and simulation pacing strategies most effectively reduce cognitive overload without compromising the educational rigor of the STEM laboratory? <br> 3. How does biologically responsive VR adaptation impact long-term knowledge retention and user comfort compared to static VR simulations? |
| **5. Technologies** | C#, Unity3D, VR SDKs (Oculus/SteamVR), Tobii Eye-Tracking SDK, Python (Signal Processing), Polar Heart Rate Monitors |
| **6. Research Category** | Human-Computer Interaction, Virtual Reality, Educational Technology |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Adaptive VR STEM Lab, Cognitive Load Estimation Algorithm, User Study and Learning Outcomes Report |
| **10. Possible Future Extensions** | Integration with EEG headsets for deeper neural state analysis, multi-user collaborative VR labs with shared cognitive load balancing. |
| **11. References / Inspiration** | Cognitive Load Theory (Sweller), Unity XR interaction toolkit, research on physiological computing in VR. |

## Idea 50
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Optimization of Shared Micro-Mobility Rebalancing Using Spatiotemporal Graph Neural Networks and Predictive Demand Modeling |
| **2. Description** | Shared micro-mobility networks (e-scooters and e-bikes) suffer from severe spatial imbalances, where vehicles accumulate in low-demand areas while high-demand zones experience shortages. Manual rebalancing is expensive and carbon-intensive. This thesis proposes a predictive rebalancing optimization system using Spatiotemporal Graph Neural Networks (ST-GNNs). By modeling the city as a dynamic graph where nodes are zones and edges represent historical travel flows, the ST-GNN predicts hyper-local demand surges. The system then generates optimal routing instructions for gig-economy riders or autonomous rebalancing vehicles. The expected contribution is a highly efficient, predictive logistics algorithm that maximizes fleet utilization, reduces operational emissions, and improves user availability. |
| **3. Target Domain** | Transportation, Smart Cities, Data Science |
| **4. Statement of the Problem (SOP)** | 1. How do Spatiotemporal Graph Neural Networks capture the complex, non-linear spatial dependencies and temporal periodicity of micro-mobility demand compared to traditional time-series models? <br> 2. What multi-objective optimization algorithms best balance the financial cost of rebalancing routes against the predicted revenue of meeting localized demand surges? <br> 3. How can the system dynamically integrate real-time external factors (e.g., sudden weather changes, public transit delays, local events) into its predictive rebalancing graph? |
| **5. Technologies** | Python, PyTorch Geometric, NetworkX, OSMnx (OpenStreetMap), DCRNN / ASTGCN Models, Routing APIs (OSRM) |
| **6. Research Category** | Artificial Intelligence, Data Science, Transportation Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | ST-GNN Demand Predictor, Rebalancing Routing Algorithm, Fleet Simulation Dashboard |
| **10. Possible Future Extensions** | Integration with dynamic pricing models to incentivize user-driven rebalancing, predictive maintenance routing based on vehicle battery and diagnostic telemetry. |
| **11. References / Inspiration** | Spatiotemporal Graph Neural Network literature, open micro-mobility datasets (e.g., GBFS), operations research on vehicle routing problems (VRP). |


# Curated Undergraduate Computer Science Thesis Ideas (Batch 6 of 20)

## Idea 51
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Non-Invasive Fetal Electrocardiogram (fECG) Extraction and Arrhythmia Detection Using Blind Source Separation and Edge AI |
| **2. Description** | Continuous fetal heart rate monitoring is critical for detecting hypoxia and arrhythmias during pregnancy, but standard ultrasound is intermittent and Doppler is prone to motion artifacts. Non-invasive abdominal electrocardiography (aECG) captures both maternal and fetal signals, but the fetal signal is extremely weak and buried in noise. This research proposes an edge-deployed AI pipeline that combines advanced Blind Source Separation (BSS) techniques, such as Independent Component Analysis (ICA), with lightweight temporal convolutional networks to isolate and analyze the fECG in real-time. The primary contribution is a robust, low-power wearable algorithm that provides continuous, clinical-grade fetal cardiac monitoring outside the hospital, enabling early intervention for high-risk pregnancies while preserving maternal comfort. |
| **3. Target Domain** | Healthcare, Biomedical Engineering, Edge AI |
| **4. Statement of the Problem (SOP)** | 1. How can BSS algorithms be optimized to reliably separate the fECG from the dominant mECG and muscle artifacts on resource-constrained edge devices? <br> 2. What lightweight neural network architectures provide the highest accuracy for detecting fetal arrhythmias from the isolated fECG signal? <br> 3. How does the proposed wearable system perform in terms of signal fidelity during maternal physical activity and postural changes? |
| **5. Technologies** | Python, C++, SciPy, TensorFlow Lite, ESP32, Dry-plate ECG sensors |
| **6. Research Category** | Signal Processing, Artificial Intelligence, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Wearable Prototype, Edge AI Signal Processing Pipeline, Clinical Validation Report |
| **10. Possible Future Extensions** | Integration with maternal heart rate variability (HRV) analysis for pre-eclampsia prediction, cloud-based longitudinal trend analysis for obstetricians. |
| **11. References / Inspiration** | PhysioNet Non-Invasive Fetal ECG Database, literature on Blind Source Separation, Edge AI in biomedical wearables. |

## Idea 52
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | LLM-Guided Firmware Fuzzing for IoT Devices Using Semantic Mutation and Hardware-in-the-Loop Emulation |
| **2. Description** | IoT firmware is notoriously insecure, yet traditional fuzzing techniques struggle with the complex, stateful protocols and proprietary binary formats typical of embedded systems. This thesis proposes an intelligent fuzzing framework that leverages Large Language Models (LLMs) to understand decompiled IoT code and generate semantically meaningful, state-aware test payloads. By integrating this LLM-guided mutation engine with a Hardware-in-the-Loop (HiL) emulation environment (e.g., QEMU or Unicorn Engine), the system can dynamically bypass shallow execution paths and trigger deep, hidden vulnerabilities like memory corruption or logic flaws. The expected contribution is a highly automated, AI-driven security testing tool that significantly increases code coverage and vulnerability discovery rates in closed-source IoT firmware compared to random or grammar-based fuzzers. |
| **3. Target Domain** | Cybersecurity, Software Engineering, IoT |
| **4. Statement of the Problem (SOP)** | 1. How can LLMs be prompted to generate valid, state-aware input sequences that satisfy complex IoT protocol checksums and handshake requirements? <br> 2. What is the performance overhead and code-coverage improvement of LLM-guided semantic mutation compared to traditional coverage-guided fuzzers on ARM-based IoT firmware? <br> 3. How can hardware-in-the-loop emulation be optimized to scale the execution of thousands of LLM-generated test cases without prohibitive computational costs? |
| **5. Technologies** | Python, Ghidra / IDA Pro, QEMU / Unicorn Engine, Llama-3 API, AFL++ |
| **6. Research Category** | Cybersecurity, Artificial Intelligence |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Intelligent Fuzzing Engine, Emulation Environment, Vulnerability Discovery Benchmark Report |
| **10. Possible Future Extensions** | Automated generation of proof-of-concept exploits, integration with CI/CD pipelines for continuous firmware security auditing. |
| **11. References / Inspiration** | AFL++ documentation, research on LLMs for software testing, Unicorn Engine emulation frameworks. |

## Idea 53
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Carbon-Aware Query Routing and Execution Optimization in Geo-Distributed Relational Databases Using Real-Time Grid Intensity APIs |
| **2. Description** | Database operations, particularly complex analytical queries, consume significant computational resources and energy. While cloud providers offer geo-redundancy, queries are typically routed based solely on network latency. This research develops a middleware proxy for geo-distributed SQL databases that dynamically routes read-heavy analytical queries to data centers currently powered by low-carbon energy grids. By integrating real-time grid carbon intensity APIs and estimating the computational carbon footprint of query execution plans, the system optimizes for a combined metric of latency and carbon emissions. The primary contribution is a novel, carbon-aware query optimizer that enables enterprises to drastically reduce the Scope 3 emissions of their data infrastructure without violating strict Service Level Agreements (SLAs). |
| **3. Target Domain** | Cloud Computing, Green IT, Database Systems |
| **4. Statement of the Problem (SOP)** | 1. How accurately can the computational carbon footprint of complex SQL execution plans be estimated prior to query execution? <br> 2. What multi-objective optimization algorithms best balance the trade-off between query execution latency, network transfer costs, and regional carbon grid intensity? <br> 3. How does carbon-aware query routing impact data consistency and replication lag in geo-distributed, eventually consistent database architectures? |
| **5. Technologies** | Go, PostgreSQL / MySQL, Prometheus, Electricity Maps API, Kubernetes |
| **6. Research Category** | Distributed Systems, Green IT, Software Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Database Middleware Proxy, Carbon Estimation Engine, Performance vs. Emissions Analysis Report |
| **10. Possible Future Extensions** | Integration with cloud spot-instance pricing for dual financial and carbon optimization, thermal-aware routing for liquid-cooled data centers. |
| **11. References / Inspiration** | Electricity Maps API documentation, Green Software Foundation principles, distributed database query optimization literature. |

## Idea 54
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Tactile-Sensor-Enabled Soft Robotic Gripper for Delicate Fruit Harvesting Using Multimodal Reinforcement Learning |
| **2. Description** | Automated harvesting of delicate fruits (e.g., strawberries, tomatoes) remains a major challenge in agricultural robotics due to the risk of bruising and the high variability in fruit size and occlusion. Rigid grippers cause damage, while standard soft grippers lack the proprioceptive feedback required to adjust grip force dynamically. This thesis designs a soft pneumatic gripper embedded with flexible, high-resolution tactile sensors. A multimodal Deep Reinforcement Learning (DRL) agent fuses visual data (for pose estimation) with real-time tactile feedback to optimize the grasping trajectory and applied force. The expected contribution is a bio-inspired, adaptive grasping control policy that maximizes harvest success rates while minimizing fruit damage, advancing the viability of autonomous precision agriculture. |
| **3. Target Domain** | Robotics, Agriculture, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can flexible tactile sensor arrays be integrated into soft pneumatic actuators without compromising the gripper's compliance and durability? <br> 2. What multimodal reinforcement learning architectures best fuse sparse visual feedback with high-frequency tactile data to optimize dynamic grip force? <br> 3. How does the proposed tactile-enabled soft gripper compare to rigid and vision-only soft grippers in terms of fruit damage rates and harvesting speed under varying lighting and occlusion conditions? |
| **5. Technologies** | Python, ROS 2, PyTorch (RL), Soft Lithography, Arduino / Teensy, FlexiForce Sensors |
| **6. Research Category** | Robotics, Artificial Intelligence, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Soft Gripper Prototype, Multimodal RL Control Policy, Harvesting Efficiency Benchmark |
| **10. Possible Future Extensions** | Integration with automated mobile manipulators (rovers), predictive ripeness assessment using tactile firmness feedback. |
| **11. References / Inspiration** | Soft robotics literature, Deep Reinforcement Learning for manipulation, agricultural automation case studies. |

## Idea 55
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Continuous Silent Speech Recognition Using Surface Electromyography (sEMG) and Temporal Convolutional Transformers for Accessible Communication |
| **2. Description** | Individuals who have lost their vocal cords (e.g., due to laryngectomy) or suffer from severe motor speech disorders rely on slow, cumbersome text-to-speech interfaces. Silent speech interfaces (SSIs) offer a natural alternative by decoding the neuromuscular signals of articulation before sound is produced. This research develops a continuous SSI system using non-invasive surface Electromyography (sEMG) sensors placed on the jaw and neck. By employing Temporal Convolutional Transformers, the system captures both the local muscle activation patterns and the long-range temporal dependencies of continuous speech. The primary contribution is a highly accurate, user-adaptive decoding model that translates subvocalized speech into text or synthesized audio in real-time, significantly improving the communication speed and social integration of speech-impaired individuals. |
| **3. Target Domain** | Human-Computer Interaction, Biomedical Engineering, Accessibility |
| **4. Statement of the Problem (SOP)** | 1. How do Temporal Convolutional Transformers compare to standard RNNs and CNNs in decoding continuous, unconstrained speech from high-dimensional, noisy sEMG signals? <br> 2. What signal processing and artifact rejection techniques are most effective for isolating articulatory muscle activity from gross motor movements (e.g., head turning, swallowing)? <br> 3. How rapidly can the SSI model adapt to a new user's unique neuromuscular baseline using few-shot or transfer learning techniques? |
| **5. Technologies** | Python, PyTorch, OpenBCI / Myo Armband, SciPy, Hugging Face Transformers |
| **6. Research Category** | Signal Processing, Artificial Intelligence, Human-Computer Interaction |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | SSI Decoding Model, Real-time Translation Application, User Study on Communication Speed |
| **10. Possible Future Extensions** | Integration with AR glasses for heads-up text display, expansion to tonal languages, personalized voice cloning based on historical audio data. |
| **11. References / Inspiration** | Silent Speech Interface literature, Temporal Convolutional Networks (TCNs), sEMG signal processing research. |

## Idea 56
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Fractional Ownership and Automated Yield Distribution of Community Solar Microgrids Using ERC-3643 (T-REX) Compliant Smart Contracts |
| **2. Description** | Community solar projects democratize access to renewable energy, but traditional legal and financial structures make fractional ownership illiquid, administratively heavy, and inaccessible to retail investors. This thesis develops a decentralized finance (DeFi) platform utilizing the ERC-3643 (T-REX) standard to tokenize fractional ownership of local solar microgrids. Unlike standard utility tokens, T-REX ensures regulatory compliance by embedding on-chain identity (KYC/AML) and transfer rules directly into the token contract. Furthermore, the system integrates IoT smart meters to automatically calculate and distribute energy yield dividends in stablecoins to token holders. The expected contribution is a legally compliant, automated Web3 infrastructure that lowers the barrier to entry for green energy investments and accelerates local microgrid financing. |
| **3. Target Domain** | FinTech, Blockchain, Renewable Energy |
| **4. Statement of the Problem (SOP)** | 1. How can the ERC-3643 (T-REX) standard be optimized to handle high-frequency, micro-dividend distributions from IoT energy meters without incurring prohibitive gas fees? <br> 2. What decentralized oracle architectures ensure the tamper-proof ingestion of physical energy generation data into the smart contract settlement layer? <br> 3. How does the on-chain compliance mechanism of T-REX impact the secondary market liquidity of tokenized renewable energy assets compared to unconstrained ERC-20 tokens? |
| **5. Technologies** | Solidity, Hardhat, Chainlink Oracles, Polygon / Ethereum, React, IoT Smart Meter APIs |
| **6. Research Category** | Distributed Systems, FinTech, Internet of Things (IoT) |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | T-REX Smart Contract Suite, Oracle Integration Layer, Web3 Investor Dashboard |
| **10. Possible Future Extensions** | Tokenization of carbon credits generated by the microgrid, integration with peer-to-peer local energy trading markets. |
| **11. References / Inspiration** | ERC-3643 (T-REX) documentation, Tokeny Solutions whitepapers, Chainlink IoT integration guides. |

## Idea 57
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Assessment of Coral Reef Bleaching and Structural Complexity Using Underwater Photogrammetry and 3D Point Cloud Segmentation |
| **2. Description** | Coral reefs are critical marine ecosystems highly vulnerable to climate-induced bleaching. Traditional monitoring relies on 2D photographic transects, which fail to capture the 3D structural complexity (rugosity) vital for biodiversity. This research proposes an automated pipeline that reconstructs high-fidelity 3D point clouds of reef sections from diver-captured underwater video using Structure-from-Motion (SfM) photogrammetry. A 3D deep learning model (e.g., PointNet++ or VoxelNet) is then trained to segment the point cloud, classifying coral genera, identifying bleached regions, and calculating precise volumetric rugosity metrics. The primary contribution is a scalable, non-invasive marine biology tool that provides quantitative, 3D ecological data, vastly improving the accuracy of reef health assessments and conservation prioritization. |
| **3. Target Domain** | Environmental Science, Computer Vision, Marine Biology |
| **4. Statement of the Problem (SOP)** | 1. How do 3D point cloud segmentation models compare to 2D image classifiers in accurately identifying early-stage coral bleaching under variable underwater lighting and turbidity? <br> 2. What photogrammetric optimization techniques minimize the computational overhead of reconstructing high-resolution 3D reef models from standard consumer-grade action cameras? <br> 3. How strongly do the automated 3D rugosity metrics correlate with traditional, manual chain-and-tape physical measurements of reef structural complexity? |
| **5. Technologies** | Python, Open3D, PyTorch3D, COLMAP / Meshroom, OpenCV, CloudCompare |
| **6. Research Category** | Computer Vision, Data Science, Environmental Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | 3D Reconstruction Pipeline, Point Cloud Segmentation Model, Ecological Metrics Dashboard |
| **10. Possible Future Extensions** | Integration with autonomous underwater vehicles (AUVs) for automated transect capture, temporal change detection for long-term reef degradation tracking. |
| **11. References / Inspiration** | Structure-from-Motion (SfM) literature, PointNet++ architecture, marine spatial ecology methodologies. |

## Idea 58
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Detection and Root Cause Analysis of Flaky Tests in CI/CD Pipelines Using Execution Trace Analysis and Graph Embeddings |
| **2. Description** | Flaky tests—tests that nondeterministically pass or fail without code changes—severely degrade developer trust and slow down Continuous Integration/Continuous Deployment (CI/CD) pipelines. Traditional approaches rely on expensive, repeated test executions to identify flakiness. This thesis proposes a proactive detection framework that analyzes the execution traces (e.g., system calls, file I/O, thread synchronization) of tests during a single CI run. By representing these traces as directed graphs and applying graph embedding techniques, a machine learning classifier identifies the structural signatures of flakiness, such as hidden race conditions or improper environment teardown. The expected contribution is a highly efficient, static/dynamic hybrid analysis tool that flags flaky tests before they pollute the CI pipeline, saving immense computational resources. |
| **3. Target Domain** | Software Engineering, DevOps, Data Science |
| **4. Statement of the Problem (SOP)** | 1. What specific execution trace features (e.g., thread interleaving, asynchronous I/O patterns) are the strongest predictors of test flakiness in concurrent software systems? <br> 2. How do graph embedding techniques applied to execution traces outperform traditional tabular feature engineering in classifying flaky versus stable tests? <br> 3. How can the system provide actionable root-cause analysis (e.g., pinpointing the exact shared resource causing a race condition) to developers based on the flagged trace anomalies? |
| **5. Technologies** | Java / Python, JaCoCo / Strace, Neo4j, PyTorch Geometric, Jenkins / GitHub Actions API |
| **6. Research Category** | Software Engineering, Artificial Intelligence |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Trace Analysis Engine, Flakiness Prediction Model, CI/CD Integration Plugin |
| **10. Possible Future Extensions** | Automated generation of deterministic test refactoring suggestions, predictive modeling of test suite degradation over time. |
| **11. References / Inspiration** | Research on software test flakiness, graph representation learning, CI/CD pipeline optimization literature. |

## Idea 59
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Cross-Lingual Legal Contract Alignment and Contradiction Detection Using Multilingual Dense Retrieval and Natural Language Inference |
| **2. Description** | In international trade and multinational corporate governance, legal teams must frequently compare contracts drafted in different languages to ensure semantic equivalence and identify contradictory clauses. Manual translation and comparison are expensive and prone to nuance loss. This thesis develops an NLP pipeline that utilizes multilingual dense retrieval models to align corresponding clauses across bilingual contract pairs, followed by a cross-lingual Natural Language Inference (NLI) model to detect semantic contradictions or omissions. The primary contribution is a specialized, domain-adapted AI framework that handles the highly formal, structured nature of legal text, providing legal professionals with an automated, reliable tool for cross-border contract auditing and risk mitigation. |
| **3. Target Domain** | Legal Technology, Natural Language Processing, International Business |
| **4. Statement of the Problem (SOP)** | 1. How can multilingual dense retrieval models be fine-tuned to accurately align structurally disparate but semantically equivalent clauses in complex legal contracts? <br> 2. What cross-lingual NLI architectures are most effective at identifying subtle legal contradictions and omissions across languages with vastly different syntactic structures? <br> 3. How does the system handle the translation of highly domain-specific legal terminology and localized jurisdictional concepts without relying on lossy intermediate machine translation? |
| **5. Technologies** | Python, Hugging Face Transformers (mBERT / XLM-R), SentenceTransformers, FAISS, FastAPI |
| **6. Research Category** | Natural Language Processing, Artificial Intelligence |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Contract Alignment Engine, Contradiction Detection Model, Web-based Legal Auditing Interface |
| **10. Possible Future Extensions** | Integration with automated contract redlining tools, expansion to multi-party, multi-language treaty analysis. |
| **11. References / Inspiration** | Multilingual NLI datasets (XNLI), dense retrieval literature (DPR), legal NLP research (e.g., LegalBERT). |

## Idea 60
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Privacy-Preserving Pedestrian Trajectory Prediction and Crowd Analytics Using Low-Resolution LiDAR and Federated Edge Computing |
| **2. Description** | Urban planners and smart city operators require accurate pedestrian flow data to optimize infrastructure, but traditional camera-based analytics raise severe privacy and surveillance concerns. This research proposes a privacy-first crowd analytics system using low-resolution, 3D LiDAR sensors deployed at edge nodes. LiDAR captures spatial depth and movement without recording identifiable facial features or RGB imagery. A federated edge computing architecture trains Spatiotemporal Graph Neural Networks (ST-GNNs) locally on the edge devices to predict pedestrian trajectories and detect anomalous crowd behaviors (e.g., sudden stampedes or accidents), sharing only model weights with a central server. The expected contribution is a highly accurate, GDPR-compliant urban analytics framework that provides actionable mobility insights while mathematically guaranteeing individual privacy. |
| **3. Target Domain** | Smart Cities, Computer Vision, Edge Computing |
| **4. Statement of the Problem (SOP)** | 1. How accurately can low-resolution 3D LiDAR point clouds be clustered and tracked to predict complex, multi-agent pedestrian trajectories in highly occluded urban intersections? <br> 2. What federated learning aggregation strategies best handle the heterogeneous spatial layouts and varying crowd densities across different edge-deployed LiDAR nodes? <br> 3. How does the predictive accuracy of the federated ST-GNN model compare to a centralized model trained on pooled, raw LiDAR data, and what are the exact bandwidth savings achieved? |
| **5. Technologies** | Python, PyTorch, ROS 2, Ouster / Velodyne LiDAR, NVIDIA Jetson, Flower (Federated Learning) |
| **6. Research Category** | Computer Vision, Distributed Systems, Human-Computer Interaction |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | LiDAR Perception Pipeline, Federated ST-GNN Model, Smart City Analytics Dashboard |
| **10. Possible Future Extensions** | Sensor fusion with anonymized Wi-Fi/Bluetooth MAC address tracking for origin-destination matrix generation, integration with adaptive traffic light controllers. |
| **11. References / Inspiration** | 3D LiDAR point cloud processing literature, Spatiotemporal Graph Neural Networks, GDPR guidelines for smart city surveillance. |

# Curated Undergraduate Computer Science Thesis Ideas (Batch 7 of 20)

## Idea 61
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | On-Orbit Space Debris Tracking and Collision Avoidance Using Federated Learning on Edge Satellites |
| **2. Description** | The proliferation of Low Earth Orbit (LEO) satellite constellations has drastically increased the risk of catastrophic collisions with space debris. Relying on ground-based radar and telemetry introduces unacceptable latency for high-velocity collision avoidance maneuvers. This research proposes a decentralized, on-orbit edge computing architecture where satellites utilize onboard optical sensors and federated learning to collaboratively track debris and predict collision probabilities. By sharing only model weight updates and localized orbital trajectories via inter-satellite laser links or RF mesh networks, the swarm maintains a unified, high-fidelity spatial awareness map without relying on ground stations. The primary contribution is a resilient, bandwidth-efficient space situational awareness framework that enables autonomous, real-time collision avoidance in GPS-denied and communication-degraded orbital environments. |
| **3. Target Domain** | Aerospace Engineering, Distributed Systems, Edge Computing |
| **4. Statement of the Problem (SOP)** | 1. How can federated learning aggregation algorithms be optimized to handle the severe communication delays, intermittent connectivity, and Doppler shifts inherent in LEO satellite mesh networks? <br> 2. What lightweight computer vision and orbital mechanics models can be deployed on radiation-hardened, resource-constrained satellite edge processors to track uncooperative debris? <br> 3. How does a decentralized, on-orbit tracking swarm compare to centralized ground-based space situational awareness networks in terms of collision warning lead time and false-positive rates? |
| **5. Technologies** | C++, Python, Orekit (Astrodynamics), TensorFlow Federated, CubeSat Simulators (e.g., 42), MQTT / CCSDS Protocols |
| **6. Research Category** | Distributed Systems, Artificial Intelligence, Aerospace Informatics |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Orbital Simulation Environment, Federated Edge AI Pipeline, Collision Avoidance Algorithm |
| **10. Possible Future Extensions** | Integration with autonomous onboard propulsion systems for automated maneuver execution, swarm-based debris removal coordination. |
| **11. References / Inspiration** | CCSDS (Consultative Committee for Space Data Systems) standards, ESA space debris reports, federated learning in non-terrestrial networks. |

## Idea 62
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Generative AI for the Discovery of Novel Solid-State Battery Electrolytes Using 3D Equivariant Graph Generative Models |
| **2. Description** | Solid-state batteries promise higher energy density and improved safety over traditional lithium-ion cells, but discovering solid electrolytes with high ionic conductivity and thermodynamic stability relies on slow, expensive trial-and-error laboratory synthesis. This thesis applies 3D Equivariant Graph Generative Models to design novel crystalline electrolyte structures. By representing atoms and bonds as 3D graphs, the model learns the physical symmetries and spatial constraints of stable crystal lattices, generating new candidate materials optimized for specific ionic transport properties. The expected contribution is an accelerated, AI-driven materials discovery pipeline that filters millions of theoretical structures down to a highly probable subset for physical synthesis, significantly reducing the R&D timeline for next-generation energy storage. |
| **3. Target Domain** | Materials Science, Artificial Intelligence, Renewable Energy |
| **4. Statement of the Problem (SOP)** | 1. How can 3D equivariant neural networks effectively capture the rotational and translational symmetries required to generate physically valid crystal lattices? <br> 2. What surrogate machine learning models can accurately predict the ionic conductivity and thermodynamic stability of generated materials without relying on computationally prohibitive Density Functional Theory (DFT) calculations? <br> 3. How does the generative model balance the exploration of novel chemical spaces with the exploitation of known, stable structural motifs? |
| **5. Technologies** | Python, PyTorch Geometric, Pymatgen, Materials Project API, SchNet / EGNN Architectures |
| **6. Research Category** | Artificial Intelligence, Cheminformatics, Data Science |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Generative Crystal Model, Materials Screening Pipeline, Candidate Material Dataset |
| **10. Possible Future Extensions** | Integration with automated robotic laboratories (self-driving labs) for physical synthesis and testing, multi-objective optimization for electrochemical stability windows. |
| **11. References / Inspiration** | Materials Project database, literature on 3D equivariant graph neural networks, AI-driven drug and materials discovery papers. |

## Idea 63
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Translation of Complex Mathematical Notation into Refreshable Tactile Braille Using Vision-Language Models and OCR |
| **2. Description** | Visually impaired students in STEM fields face significant barriers when accessing complex mathematical equations, as standard Optical Character Recognition (OCR) fails to capture 2D spatial relationships (e.g., fractions, integrals, matrices). This research develops a real-time translation system that utilizes Vision-Language Models (VLMs) to parse printed or handwritten mathematical notation into structured MathML. A deterministic mapping engine then converts this semantic structure into Nemeth or Unified English Braille (UEB) code, outputting it directly to a refreshable tactile Braille display via Bluetooth. The primary contribution is an accessible, low-latency educational tool that preserves the structural integrity of advanced mathematics, empowering blind students to independently study and solve complex equations. |
| **3. Target Domain** | Accessibility, Education, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How accurately can Vision-Language Models parse the complex 2D spatial hierarchies of handwritten and printed mathematical notation compared to traditional OCR engines? <br> 2. What deterministic parsing algorithms ensure the lossless translation of MathML into standardized Nemeth Braille code without introducing syntactic ambiguities? <br> 3. How does the end-to-end latency of the vision-to-tactile pipeline impact the reading fluency and cognitive load of visually impaired STEM students? |
| **5. Technologies** | Python, Pix2Tex / LaTeX-OCR, MathJax, React Native, Serial / BLE Communication, Braille Display APIs |
| **6. Research Category** | Human-Computer Interaction, Computer Vision, Accessibility |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Mobile Translation App, MathML-to-Braille Parser, User Study with Visually Impaired Students |
| **10. Possible Future Extensions** | Integration with audio-tactile feedback for interactive equation solving, expansion to chemical formulas and physics diagrams. |
| **11. References / Inspiration** | Nemeth Braille code specifications, Mathpix API architecture, research on accessible STEM education. |

## Idea 64
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Detection of Serverless Function Hijacking and Cryptojacking Using eBPF and Behavioral Anomaly Detection |
| **2. Description** | Serverless computing environments (e.g., AWS Lambda, Knative) are highly attractive targets for cryptojacking and function hijacking due to their ephemeral nature and automatic scaling capabilities. Traditional antivirus and sidecar proxies are often too slow or lack the kernel-level visibility required to detect stealthy resource abuse in milliseconds. This thesis implements a security agent utilizing the Extended Berkeley Packet Filter (eBPF) to monitor system calls, network sockets, and CPU micro-architectural events directly within the serverless sandbox. By applying lightweight behavioral anomaly detection to these eBPF traces, the system can instantly identify and terminate unauthorized cryptographic mining threads. The contribution is a highly efficient, kernel-level defense mechanism tailored specifically for the unique threat landscape of serverless architectures. |
| **3. Target Domain** | Cybersecurity, Cloud Computing, DevOps |
| **4. Statement of the Problem (SOP)** | 1. What specific system call sequences and CPU cache-miss patterns uniquely characterize stealthy crypto-mining workloads in ephemeral serverless containers? <br> 2. How can eBPF programs be designed to enforce security policies with near-zero latency overhead in high-throughput, auto-scaling serverless environments? <br> 3. How does the proposed eBPF-based anomaly detector differentiate between legitimate, compute-heavy serverless tasks (e.g., image processing) and malicious cryptojacking? |
| **5. Technologies** | C, Go, eBPF (libbpf / Cilium), AWS Lambda / Knative, Prometheus, Linux Kernel |
| **6. Research Category** | Cybersecurity, Cloud Computing, Systems Programming |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | eBPF Security Agent, Serverless Threat Dataset, Performance Overhead Analysis Report |
| **10. Possible Future Extensions** | Automated generation of Web Application Firewall (WAF) rules based on detected hijacking vectors, integration with cloud billing APIs to halt financial bleed. |
| **11. References / Inspiration** | eBPF.io documentation, OWASP Serverless Top 10, research on kernel-level malware detection. |

## Idea 65
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Non-Destructive Subterranean Root System Mapping and Moisture Profiling Using Ground-Penetrating Radar and Edge-Based Deep Learning |
| **2. Description** | Developing drought-resistant crops requires a deep understanding of subterranean root architecture and soil moisture dynamics. Traditional methods involve destructive excavation, which kills the plant and prevents longitudinal study. This research proposes a non-destructive phenotyping rover equipped with Ground-Penetrating Radar (GPR) and Edge AI. The system captures 2D GPR B-scans and utilizes a Convolutional Neural Network to filter soil clutter and reconstruct 3D volumetric models of the root system, simultaneously estimating localized soil moisture content based on radar wave velocity. The primary contribution is a field-deployable, automated phenotyping tool that enables agricultural scientists to track root growth and water uptake in real-time without disturbing the crop. |
| **3. Target Domain** | Agriculture, Signal Processing, Robotics |
| **4. Statement of the Problem (SOP)** | 1. How can deep learning models effectively filter high-frequency GPR clutter caused by rocks and soil heterogeneity to isolate hyperbolic root reflections? <br> 2. What algorithmic techniques best reconstruct continuous 3D root architectures from sequential, noisy 2D GPR B-scans captured by a moving rover? <br> 3. How accurately can localized soil moisture gradients be estimated using the dielectric permittivity variations derived from GPR wave propagation velocities? |
| **5. Technologies** | Python, PyTorch, OpenCV, ROS 2, GPR Hardware APIs (e.g., MALA, Sensors & Software), NVIDIA Jetson |
| **6. Research Category** | Computer Vision, Embedded Systems, Precision Agriculture |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | GPR Perception Pipeline, 3D Root Reconstruction Algorithm, Autonomous Rover Prototype |
| **10. Possible Future Extensions** | Sensor fusion with multispectral drone imagery to correlate above-ground plant stress with subterranean root deficits, integration with automated irrigation systems. |
| **11. References / Inspiration** | Ground-Penetrating Radar signal processing literature, agricultural phenotyping research, ROS 2 navigation stacks. |

## Idea 66
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Mitigating Maximal Extractable Value (MEV) Attacks in Decentralized Exchanges Using Threshold Cryptography and Private Mempool Routing |
| **2. Description** | Maximal Extractable Value (MEV) exploits, such as front-running and sandwich attacks, extract billions of dollars from retail users on Decentralized Exchanges (DEXs) by exploiting the transparency of public blockchain mempools. This thesis designs a decentralized, privacy-preserving transaction routing protocol utilizing Threshold Cryptography. User transactions are encrypted and distributed to a decentralized committee of network nodes. The transaction payload is only decrypted and executed once it is guaranteed to be included in a block, rendering it invisible to MEV searchers during the pending state. The expected contribution is a cryptographically secure, decentralized alternative to centralized private relays, protecting DEX users from predatory trading bots while maintaining the trustless ethos of public blockchains. |
| **3. Target Domain** | Blockchain, FinTech, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. How can Threshold Signature Schemes (TSS) be optimized to encrypt and decrypt high-frequency DEX transaction payloads without introducing prohibitive latency? <br> 2. What incentive mechanisms and game-theoretic models prevent collusion among the threshold decryption committee to leak transaction data to MEV searchers? <br> 3. How does the integration of private mempool routing impact the overall throughput, gas efficiency, and block space utilization of the underlying Layer 1 blockchain? |
| **5. Technologies** | Solidity, Rust, Circom, Threshold Cryptography Libraries, Foundry, Ethereum / Polygon |
| **6. Research Category** | Distributed Systems, Cybersecurity, Cryptography |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Threshold Encryption Smart Contracts, Private Routing Node Software, MEV Simulation Report |
| **10. Possible Future Extensions** | Integration with Layer 2 rollups for sub-second encrypted settlement, expansion to protect decentralized lending and liquidation protocols from MEV. |
| **11. References / Inspiration** | Flashbots MEV research, Threshold Signature Scheme (TSS) documentation, DEX architecture whitepapers (e.g., Uniswap). |

## Idea 67
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Intent-Driven Control of a Soft Upper-Limb Exoskeleton for Stroke Rehabilitation Using Multimodal Fusion of sEMG and fNIRS |
| **2. Description** | Repetitive task training is critical for neuroplasticity and motor recovery in stroke survivors, but rigid robotic exoskeletons are often uncomfortable and misaligned with human kinematics. This research develops a soft, pneumatic upper-limb exoskeleton controlled by a multimodal intent recognition system. By fusing surface Electromyography (sEMG) to detect residual muscle activation and functional Near-Infrared Spectroscopy (fNIRS) to measure cortical blood flow (motor intent), the system can accurately predict the patient's desired movement even if they suffer from severe muscle weakness. The primary contribution is a highly responsive, patient-adaptive biofeedback loop that provides "assist-as-needed" support, maximizing therapeutic engagement and accelerating stroke rehabilitation outcomes. |
| **3. Target Domain** | Biomedical Engineering, Robotics, Healthcare |
| **4. Statement of the Problem (SOP)** | 1. How can asynchronous sEMG and fNIRS signals be temporally aligned and fused to robustly classify motor intent in patients with severe neuromuscular impairment? <br> 2. What control algorithms minimize the latency between intent detection and pneumatic actuation to ensure the assistance feels natural and synchronized with the user? <br> 3. How does the system dynamically adapt its assistance thresholds to account for patient fatigue and signal degradation over a prolonged therapy session? |
| **5. Technologies** | Python, C++, ROS 2, Scikit-learn, OpenBCI / fNIRS Headsets, Pneumatic Artificial Muscles, Microcontrollers |
| **6. Research Category** | Robotics, Human-Computer Interaction, Signal Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Soft Exoskeleton Prototype, Multimodal Intent Classifier, Clinical Feasibility Study |
| **10. Possible Future Extensions** | Integration with VR gamification for cognitive-motor dual-task training, automated generation of personalized rehabilitation progression plans using AI. |
| **11. References / Inspiration** | Soft robotics actuation literature, Brain-Computer Interface (BCI) motor imagery research, neurorehabilitation clinical guidelines. |

## Idea 68
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Carbon-Aware LLM Inference Optimization via Dynamic KV-Cache Eviction and Hardware-Adaptive Quantization |
| **2. Description** | The autoregressive decoding phase of Large Language Model (LLM) inference is highly memory-bandwidth bound, leading to massive energy consumption in data centers. This thesis proposes a carbon-aware LLM serving engine that dynamically adjusts its internal memory management based on real-time electrical grid carbon intensity. When grid carbon intensity is high, the system aggressively applies dynamic KV-cache eviction and lower-bit quantization to reduce memory transfers and GPU power draw, accepting a marginal drop in output perplexity. When grid energy is green, it maximizes cache retention for optimal quality. The primary contribution is a novel serving framework that mathematically balances the trade-off between LLM generation quality and Scope 2 carbon emissions, advancing Green AI infrastructure. |
| **3. Target Domain** | Green IT, Artificial Intelligence, Cloud Computing |
| **4. Statement of the Problem (SOP)** | 1. How do aggressive, dynamic KV-cache eviction policies impact the perplexity, coherence, and factual accuracy of LLM outputs across different reasoning tasks? <br> 2. What is the precise correlation between GPU memory bandwidth utilization, KV-cache size, and real-time energy consumption during the autoregressive decoding phase? <br> 3. How can the serving engine dynamically switch quantization levels and eviction thresholds on-the-fly without incurring prohibitive context-reloading latency? |
| **5. Technologies** | Python, C++, vLLM / Hugging Face, PyTorch, Electricity Maps API, NVIDIA Triton Inference Server |
| **6. Research Category** | Artificial Intelligence, Green IT, Systems Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Carbon-Aware Serving Engine, Quality vs. Emissions Benchmarking Suite, API Gateway |
| **10. Possible Future Extensions** | Integration with data center cooling systems for thermal-aware inference routing, extension to multimodal (vision-language) model optimization. |
| **11. References / Inspiration** | vLLM PagedAttention documentation, Green Software Foundation specifications, research on LLM memory bottlenecks. |

## Idea 69
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Dynamic Multi-Agent Pathfinding (MAPF) for Human-Shared Autonomous Warehouses Using Spatiotemporal Graph Attention Networks |
| **2. Description** | Autonomous Mobile Robots (AMRs) in modern warehouses must navigate efficiently while sharing narrow aisles with human workers. Traditional Multi-Agent Pathfinding (MAPF) algorithms, like Conflict-Based Search, struggle to scale in real-time when faced with the unpredictable, dynamic trajectories of human pedestrians. This research develops a decentralized navigation framework utilizing Spatiotemporal Graph Attention Networks (ST-GAT). The AMRs model the warehouse as a dynamic graph, using attention mechanisms to predict the short-term intent and trajectories of nearby humans, allowing them to proactively reroute and prevent bottlenecks or safety incidents. The expected contribution is a highly scalable, socially compliant navigation stack that maximizes warehouse throughput while strictly adhering to human-robot safety margins. |
| **3. Target Domain** | Robotics, Logistics, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How can ST-GAT models accurately predict the non-linear, intent-driven trajectories of human workers in highly cluttered, occluded warehouse environments? <br> 2. What decentralized MAPF algorithms best utilize these human trajectory predictions to re-plan AMR paths in real-time without causing systemic gridlock? <br> 3. How does the system balance the trade-off between maintaining strict safety buffers around humans and maximizing overall logistical throughput and task completion speed? |
| **5. Technologies** | Python, PyTorch, ROS 2 Navigation (Nav2), Gazebo Simulator, OpenAI Gym, LiDAR / Depth Camera APIs |
| **6. Research Category** | Robotics, Artificial Intelligence, Logistics Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | ST-GAT Prediction Model, Decentralized MAPF Planner, Warehouse Simulation Environment |
| **10. Possible Future Extensions** | Integration with warehouse management systems (WMS) for predictive task assignment, multi-robot cooperative manipulation in human-shared spaces. |
| **11. References / Inspiration** | Multi-Agent Pathfinding (MAPF) literature, Spatiotemporal Graph Neural Networks, human-robot interaction (HRI) in logistics. |

## Idea 70
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Detection and Explanation of Predatory Clauses in Consumer Terms of Service Using Contrastive Learning and Legal Ontologies |
| **2. Description** | Consumers routinely click "I Agree" on lengthy Terms of Service (ToS) agreements that contain predatory clauses, such as forced arbitration, extreme data harvesting, and unilateral modification rights. This thesis develops an NLP browser extension that automatically scans and highlights unfair contractual terms in real-time. By utilizing contrastive learning aligned with a structured legal ontology of consumer protection laws (e.g., GDPR, CCPA), the model identifies semantic deviations from fair baseline contracts. Furthermore, it employs an LLM to generate plain-language explanations of the specific risks associated with each flagged clause. The primary contribution is an accessible, transparent legal-tech tool that empowers consumers to make informed digital consent decisions and holds corporations accountable for dark patterns. |
| **3. Target Domain** | Legal Technology, Natural Language Processing, Consumer Protection |
| **4. Statement of the Problem (SOP)** | 1. How can contrastive learning be effectively aligned with structured legal ontologies to identify subtle, jurisdiction-specific predatory clauses in unstructured ToS text? <br> 2. What prompting and grounding strategies ensure the LLM generates accurate, plain-language explanations of legal risks without hallucinating unauthorized legal advice? <br> 3. How does the real-time processing of lengthy ToS documents impact browser performance and user cognitive load during the digital onboarding process? |
| **5. Technologies** | Python, Hugging Face Transformers (LegalBERT), Neo4j (Graph DB), spaCy, React (Browser Extension), FastAPI |
| **6. Research Category** | Natural Language Processing, Human-Computer Interaction, Legal Tech |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Intermediate |
| **9. Expected Deliverables** | Browser Extension, Legal Ontology Knowledge Graph, Clause Explanation Engine |
| **10. Possible Future Extensions** | Automated generation of "opt-out" emails or legal pushback templates, crowdsourced database of corporate ToS changes over time. |
| **11. References / Inspiration** | ToS;DR (Terms of Service; Didn't Read) dataset, LegalBERT research papers, consumer protection regulatory frameworks. |

# Curated Undergraduate Computer Science Thesis Ideas (Batch 8 of 20)

## Idea 71
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Privacy-Preserving Elderly Fall Detection and Gait Analysis Using Wi-Fi Channel State Information (CSI) and Edge AI |
| **2. Description** | Monitoring elderly individuals for falls and mobility degradation is critical for aging-in-place, but camera-based systems raise severe privacy concerns, and wearables suffer from low compliance. This research utilizes Wi-Fi Channel State Information (CSI), which captures the micro-Doppler shifts and multipath fading caused by human movement, to monitor activity without visual surveillance. By deploying a lightweight Convolutional Recurrent Neural Network (CRNN) on an edge gateway, the system classifies Activities of Daily Living (ADLs) and detects falls in real-time. The primary contribution is a non-intrusive, privacy-mathematically-guaranteed monitoring framework that operates using existing commercial Wi-Fi infrastructure, providing continuous health analytics while preserving the dignity and privacy of the user. |
| **3. Target Domain** | Healthcare, Internet of Things (IoT), Signal Processing |
| **4. Statement of the Problem (SOP)** | 1. How can high-dimensional, noisy Wi-Fi CSI data be effectively filtered and reduced to extract robust micro-Doppler signatures of human gait and falls? <br> 2. What edge-optimized neural network architectures best differentiate between critical falls and visually similar ADLs (e.g., sitting down quickly, lying on a bed)? <br> 3. How does the physical layout of a room and the presence of multiple occupants impact the localization accuracy and false-positive rate of the CSI-based detection system? |
| **5. Technologies** | Python, PyTorch, TensorFlow Lite, ESP32-C3 / Intel 5300 NIC, MQTT, Digital Signal Processing (DSP) |
| **6. Research Category** | Signal Processing, Embedded Systems, Healthcare Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | CSI Data Collection Pipeline, Edge AI Classification Model, Caregiver Alert Dashboard |
| **10. Possible Future Extensions** | Integration with smart home automation (e.g., turning on lights if a fall is detected at night), longitudinal gait analysis for early prediction of neurodegenerative decline. |
| **11. References / Inspiration** | Research on Wi-Fi sensing and CSI human activity recognition (HAR), edge AI deployment on microcontrollers. |

## Idea 72
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Portfolio Optimization and Risk Arbitrage in High-Frequency Trading Using Quantum Annealing and Hybrid Solvers |
| **2. Description** | High-Frequency Trading (HFT) and quantitative finance require solving NP-hard combinatorial portfolio optimization problems under strict, sub-millisecond latency constraints. Classical heuristics often get trapped in local minima when dealing with complex, non-linear market constraints. This thesis maps the Markowitz portfolio theory, augmented with real-world trading constraints (e.g., transaction costs, sector limits), into a Quadratic Unconstrained Binary Optimization (QUBO) formulation. By leveraging quantum annealers and hybrid classical-quantum solvers, the system evaluates vast asset combination spaces simultaneously. The expected contribution is a comparative latency and optimality analysis demonstrating how near-term quantum hardware can provide a competitive arbitrage edge in rapidly shifting financial markets. |
| **3. Target Domain** | FinTech, Quantum Computing, Financial Engineering |
| **4. Statement of the Problem (SOP)** | 1. How can complex, multi-asset financial constraints and non-linear transaction costs be efficiently mapped to a QUBO formulation without exceeding current qubit connectivity limits? <br> 2. How do quantum annealing and hybrid solvers compare to classical simulated annealing and mixed-integer programming in terms of solution optimality and time-to-solution for real-time HFT portfolios? <br> 3. How can the system mitigate the impact of market noise and data ingestion latency on the quantum optimization pipeline? |
| **5. Technologies** | Python, D-Wave Ocean SDK, Qiskit, Pandas, Financial Market APIs (e.g., Alpaca, Binance), QUBO Solvers |
| **6. Research Category** | Quantum Computing, Data Science, FinTech |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | QUBO Financial Model, Hybrid Quantum-Classical Solver, Backtesting and Latency Report |
| **10. Possible Future Extensions** | Integration with quantum machine learning for predictive alpha generation, application to decentralized finance (DeFi) liquidity pool optimization. |
| **11. References / Inspiration** | D-Wave financial use case documentation, literature on quantum portfolio optimization, Markowitz modern portfolio theory. |

## Idea 73
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Wearable Ultrasonic Spatial Mapping and LLM-Driven Haptic Scene Description for Deafblind Independent Navigation |
| **2. Description** | Individuals who are Deafblind lack access to the auditory and visual cues required for standard navigation apps, relying heavily on white canes that only detect ground-level obstacles. This research develops a wearable navigation vest equipped with an array of ultrasonic sensors to build a real-time, 3D local depth map of the environment. This spatial data is translated into intuitive vibrotactile gradients on the torso for obstacle avoidance. Simultaneously, a chest-mounted camera feeds visual data to a local Vision-Language Model (VLM), which generates semantic scene descriptions (e.g., "doorway on right, stairs ahead") translated into distinct, localized haptic patterns. The primary contribution is a multimodal, non-visual sensory substitution interface that drastically improves spatial awareness and independence for the Deafblind community. |
| **3. Target Domain** | Accessibility, Human-Computer Interaction, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can 3D ultrasonic point clouds be mathematically mapped to multi-actuator vibrotactile arrays to create an intuitive, cognitively low-load spatial gradient? <br> 2. What Vision-Language Model (VLM) prompting and quantization strategies allow for real-time, localized semantic scene description on edge hardware without network connectivity? <br> 3. How does the brain integrate and differentiate between continuous spatial haptic feedback (obstacles) and discrete semantic haptic patterns (scene descriptions) during active navigation? |
| **5. Technologies** | C++, ROS 2, Ultrasonic Sensor Arrays, LRA/ERM Haptic Motors, Llama-3 Vision API, Raspberry Pi / NVIDIA Jetson |
| **6. Research Category** | Human-Computer Interaction, Accessibility, Embedded Systems |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Haptic Navigation Vest Prototype, Spatial-to-Tactile Mapping Algorithm, User Feasibility Study |
| **10. Possible Future Extensions** | Integration with GPS and accessible mapping APIs (e.g., OpenStreetMap) for macro-navigation, bone-conduction audio fallback for users with residual hearing. |
| **11. References / Inspiration** | Sensory substitution literature (e.g., Paul Bach-y-Rita), haptic feedback psychoacoustics, VLM edge deployment research. |

## Idea 74
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Energy-Efficient Deep Learning Training via Dynamic Voltage and Frequency Scaling (DVFS) Optimization Using Deep Reinforcement Learning |
| **2. Description** | Training large-scale AI models consumes massive amounts of electrical energy, contributing significantly to data center carbon footprints. While GPUs operate at peak power by default, neural network training consists of alternating compute-bound (e.g., matrix multiplication) and memory-bound (e.g., data loading, activation transfers) phases. This thesis develops a Deep Reinforcement Learning (DRL) agent that interfaces with the GPU hardware management API to dynamically apply Dynamic Voltage and Frequency Scaling (DVFS) on a per-layer or per-batch basis. By underclocking the GPU during memory-bound phases, the system drastically reduces energy consumption with negligible impact on total training time. The contribution is a hardware-aware, Green AI optimization framework that maximizes performance-per-watt in enterprise training clusters. |
| **3. Target Domain** | Green IT, Systems Engineering, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How accurately can a DRL agent profile and predict the transition between compute-bound and memory-bound phases in complex, dynamic neural network architectures? <br> 2. What reward functions best optimize the strict trade-off between minimizing Joules-per-epoch and maintaining acceptable training throughput (time-to-accuracy)? <br> 3. How does the overhead of hardware-level DVFS switching via APIs (e.g., NVML) impact the stability and convergence of distributed training workloads? |
| **5. Technologies** | Python, C++, PyTorch, NVIDIA NVML API, Ray RLlib, Prometheus, Linux Kernel |
| **6. Research Category** | Systems Programming, Artificial Intelligence, Green IT |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | DRL DVFS Controller, Energy Profiling Suite, Performance vs. Power Benchmarking Report |
| **10. Possible Future Extensions** | Extension to multi-node distributed training clusters, integration with data center cooling systems for holistic thermal-energy management. |
| **11. References / Inspiration** | NVIDIA NVML documentation, research on Green AI and energy-efficient deep learning, DRL for systems optimization. |

## Idea 75
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Predicting Antimicrobial Resistance (AMR) Phenotypes in Bacterial Pathogens Using Transformer Models on Whole Genome Sequences |
| **2. Description** | Antimicrobial resistance (AMR) is a critical global health threat. Traditional phenotypic susceptibility testing requires days of bacterial culturing, delaying life-saving treatments. While Whole Genome Sequencing (WGS) is faster, mapping reads to known resistance databases misses novel or complex mutational mechanisms. This thesis applies genomic Transformer models (e.g., DNABERT) directly to raw WGS reads to predict phenotypic resistance to specific antibiotic classes. By treating DNA sequences as a language, the model learns the complex, long-range genomic context and epistatic interactions that confer resistance. The primary contribution is a rapid, culture-free diagnostic AI tool that accelerates precision antibiotic prescribing and aids in the surveillance of emerging superbugs. |
| **3. Target Domain** | Bioinformatics, Healthcare, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How can long, high-dimensional DNA sequences be effectively tokenized and processed by Transformer architectures without exceeding memory limits or losing critical genomic context? <br> 2. What data augmentation and loss-function weighting strategies best address the severe class imbalance inherent in clinical AMR datasets (where susceptible samples vastly outnumber resistant ones)? <br> 3. How can the attention mechanisms of the Transformer model be interpreted to identify novel, previously uncharacterized genetic markers associated with antimicrobial resistance? |
| **5. Technologies** | Python, PyTorch, Hugging Face (DNABERT), Biopython, NCBI Pathogen Detection Database, Scikit-learn |
| **6. Research Category** | Bioinformatics, Natural Language Processing, Artificial Intelligence |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Genomic Transformer Model, AMR Prediction Pipeline, Biological Marker Analysis Report |
| **10. Possible Future Extensions** | Integration with hospital Electronic Health Records (EHR) for real-time clinical decision support, extension to predict viral mutation and vaccine escape. |
| **11. References / Inspiration** | DNABERT architecture papers, NCBI AMR reference gene database, literature on AI in genomic epidemiology. |

## Idea 76
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Detection and Remediation of Infrastructure-as-Code (IaC) Drift and Security Misconfigurations Using LLMs and State Graph Analysis |
| **2. Description** | Cloud environments frequently experience "configuration drift," where the actual deployed infrastructure diverges from the defining Infrastructure-as-Code (IaC) templates (e.g., Terraform, Pulumi) due to manual hotfixes or automated scaling. This drift creates severe security vulnerabilities and compliance failures. This research develops an automated remediation engine that represents both the actual cloud state and the desired IaC state as directed property graphs. By analyzing the graph diffs, an integrated Large Language Model generates safe, executable IaC patches to reconcile the drift without destroying active resources. The expected contribution is a continuous compliance tool that autonomously maintains cloud security posture and eliminates manual DevOps overhead. |
| **3. Target Domain** | DevOps, Cloud Security, Software Engineering |
| **4. Statement of the Problem (SOP)** | 1. How can complex, nested cloud resource hierarchies and their dependencies be accurately modeled as directed property graphs for precise state-diff analysis? <br> 2. What prompting and guardrail strategies ensure the LLM generates syntactically valid and non-destructive IaC patches that do not cause unintended downtime? <br> 3. How does the automated remediation engine handle circular dependencies and state-locking conflicts inherent in modern IaC providers? |
| **5. Technologies** | Go, Python, Terraform AWS/Azure Providers, Neo4j, Llama-3 API, Cloud Provider SDKs |
| **6. Research Category** | Software Engineering, Cloud Computing, Cybersecurity |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | State Graph Diff Engine, LLM Remediation Generator, CI/CD Integration Plugin |
| **10. Possible Future Extensions** | Predictive drift analysis based on developer commit patterns, automated generation of compliance audit reports (e.g., SOC2, HIPAA) from the state graph. |
| **11. References / Inspiration** | Terraform state management documentation, graph database applications in IT operations, LLMs for code generation research. |

## Idea 77
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Affect-Aware Socratic Tutoring for Mathematical Word Problems Using LLMs and Webcam-Based Cognitive State Tracking |
| **2. Description** | While Large Language Models can solve complex math problems, simply providing the answer bypasses the learning process. This thesis develops an AI-driven Socratic tutor that guides students through mathematical word problems by asking sequential, targeted questions rather than giving direct solutions. Crucially, the system integrates webcam-based affective computing to monitor the student's cognitive state (e.g., frustration, confusion, boredom) in real-time. A dynamic dialogue policy adjusts the scaffolding, tone, and difficulty of the Socratic hints based on this emotional feedback. The primary contribution is a pedagogically sound, emotionally intelligent tutoring system that improves student engagement and deep conceptual understanding in STEM education. |
| **3. Target Domain** | EdTech, Human-Computer Interaction, Natural Language Processing |
| **4. Statement of the Problem (SOP)** | 1. How can LLM prompting frameworks be constrained to strictly enforce Socratic pedagogy, preventing the model from hallucinating direct answers or solving the problem prematurely? <br> 2. What multimodal fusion techniques best integrate discrete affective states (from facial micro-expressions) with the continuous dialogue state to optimize hint generation? <br> 3. How does affect-aware Socratic tutoring impact long-term knowledge retention and problem-solving independence compared to standard, direct-instruction LLM tutors? |
| **5. Technologies** | Python, LangChain, MediaPipe, Hugging Face, React, WebRTC, OpenAI / Llama API |
| **6. Research Category** | Educational Technology, Human-Computer Interaction, Artificial Intelligence |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Socratic Dialogue Engine, Affective State Tracker, Web-based Tutoring Interface, Learning Outcomes Study |
| **10. Possible Future Extensions** | Expansion to physics and chemistry problem solving, integration with speech-to-text for natural, spoken tutoring interactions. |
| **11. References / Inspiration** | Socratic method pedagogical literature, MediaPipe Face Mesh documentation, intelligent tutoring systems (ITS) research. |

## Idea 78
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Multi-Agent Reinforcement Learning for Bidirectional Vehicle-to-Grid (V2G) Energy Arbitrage and Battery Degradation Mitigation in EV Fleets |
| **2. Description** | Electric Vehicle (EV) fleets represent massive, distributed mobile energy storage capable of stabilizing the smart grid via Vehicle-to-Grid (V2G) bidirectional charging. However, frequent charging and discharging severely accelerates lithium-ion battery degradation, negating financial gains. This research utilizes Multi-Agent Reinforcement Learning (MARL) to coordinate a fleet of commercial EVs. The agents learn to optimize financial energy arbitrage (buying low, selling high to the grid) while strictly adhering to individual battery health constraints, route schedules, and local transformer capacity limits. The expected contribution is a scalable fleet management algorithm that unlocks the economic viability of V2G without compromising the operational lifespan of the vehicles. |
| **3. Target Domain** | Smart Grids, Transportation, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How can non-linear, chemistry-based battery degradation models be integrated as strict penalty functions within a MARL reward architecture? <br> 2. What decentralized MARL algorithms prevent localized grid overloads when multiple EV agents simultaneously decide to discharge power into the same distribution transformer? <br> 3. How does the system handle the stochastic nature of grid energy pricing, renewable energy generation, and individual EV driver route deviations? |
| **5. Technologies** | Python, PyTorch (RLlib), Ray, SUMO (Traffic Simulator), GridLAB-D / OpenDSS, EV Battery Simulation Models |
| **6. Research Category** | Artificial Intelligence, Energy Informatics, Transportation Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | MARL Fleet Coordinator, Battery Degradation Simulator, Financial vs. Health Trade-off Report |
| **10. Possible Future Extensions** | Integration with dynamic wireless charging lanes, peer-to-peer energy trading between moving EVs. |
| **11. References / Inspiration** | Multi-Agent Reinforcement Learning literature, V2G economic feasibility studies, lithium-ion battery degradation modeling. |

## Idea 79
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Mitigating Acoustic Side-Channel Attacks on 3D Printers and CNC Machines Using Real-Time Generative Audio Obfuscation |
| **2. Description** | Cyber-physical systems like 3D printers and CNC mills emit distinct acoustic signatures based on the stepper motor frequencies and mechanical vibrations dictated by their G-code toolpaths. Malicious actors can record these sounds and use machine learning to reconstruct proprietary physical designs (IP theft). This thesis develops an edge-based hardware security module that injects real-time, generative adversarial audio noise into the environment. This noise is specifically optimized to disrupt ML-based acoustic eavesdropping classifiers while preserving the specific frequency bands required for human operators to audibly detect mechanical faults (e.g., layer shifting, tool breakage). The contribution is a novel, physical-layer defense mechanism for protecting manufacturing IP in shared or untrusted spaces. |
| **3. Target Domain** | Cybersecurity, Hardware Security, Audio Processing |
| **4. Statement of the Problem (SOP)** | 1. How can adversarial machine learning techniques be used to generate audio perturbations that reliably fool CNN-based acoustic side-channel classifiers? <br> 2. What digital signal processing (DSP) filters ensure the generative obfuscation noise does not mask the critical, human-audible frequencies associated with mechanical hardware failures? <br> 3. What is the computational and latency overhead of generating and injecting adversarial audio in real-time on low-cost edge microcontrollers synchronized with the G-code execution? |
| **5. Technologies** | Python, C++, PyTorch, Raspberry Pi, I2S DACs, Digital Signal Processing (DSP), Adversarial ML Frameworks |
| **6. Research Category** | Cybersecurity, Embedded Systems, Audio Processing |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Adversarial Audio Generator, Hardware Obfuscation Prototype, IP Reconstruction Attack Benchmark |
| **10. Possible Future Extensions** | Extension to protect keystroke dynamics and ATM PIN pads, integration with active noise cancellation (ANC) headphones for localized operator protection. |
| **11. References / Inspiration** | Research on acoustic side-channel attacks on 3D printers, adversarial examples in audio processing, hardware security literature. |

## Idea 80
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Autonomous Precision Pruning in Dense Orchards Using 3D LiDAR Semantic Segmentation and Robotic Kinematic Path Planning |
| **2. Description** | Pruning fruit trees is a highly skilled, labor-intensive task critical for maximizing crop yield and preventing disease. Automating this process is hindered by the unstructured, occluded nature of tree canopies and the complex agronomic rules governing which branches to cut. This research develops an autonomous pruning system utilizing a mobile manipulator equipped with 3D LiDAR. A point-cloud segmentation model identifies structural wood versus fruiting spurs. An algorithmic planner then applies agronomic pruning rules to select optimal cuts and generates collision-free inverse kinematic paths for a robotic pruning saw. The primary contribution is a complete perception-to-action pipeline that addresses the severe labor shortages in specialty crop agriculture while maintaining high horticultural standards. |
| **3. Target Domain** | Agriculture, Robotics, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can 3D LiDAR point clouds be accurately segmented to differentiate between thin, occluded fruiting branches and structural wood under varying wind and lighting conditions? <br> 2. What algorithmic frameworks best translate complex, qualitative agronomic pruning rules into deterministic, mathematical cut-selection objectives? <br> 3. How can inverse kinematics and motion planning algorithms generate collision-free paths for a robotic end-effector operating deep inside a dense, highly cluttered tree canopy? |
| **5. Technologies** | C++, Python, ROS 2, Point Cloud Library (PCL), PyTorch3D, MoveIt!, Ouster / Velodyne LiDAR |
| **6. Research Category** | Robotics, Computer Vision, Agricultural Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | LiDAR Canopy Segmentation Model, Pruning Path Planner, Robotic Manipulator Simulation |
| **10. Possible Future Extensions** | Integration with multispectral cameras for disease-targeted pruning, reinforcement learning for long-term tree yield optimization based on pruning history. |
| **11. References / Inspiration** | MoveIt! motion planning documentation, 3D point cloud segmentation in agriculture, horticultural pruning guidelines. |

# Curated Undergraduate Computer Science Thesis Ideas (Batch 9 of 20)

## Idea 81
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Edge-AI Structural Health Monitoring of Self-Healing Concrete Using Embedded Piezoelectric Sensor Networks |
| **2. Description** | Self-healing concrete utilizes bacteria or microcapsules to repair micro-cracks, extending infrastructure lifespan. However, verifying the efficacy and location of the healing process non-destructively is challenging. This research proposes an embedded IoT sensor network using piezoelectric transducers to perform active acoustic emission and ultrasonic pulse velocity testing. Edge AI models analyze the acoustic wave propagation to detect micro-crack formation and subsequently monitor the acoustic impedance changes as the healing agent cures. The contribution is a real-time, non-destructive evaluation framework that provides civil engineers with quantitative data on structural integrity and self-healing efficacy. |
| **3. Target Domain** | Civil Engineering, Internet of Things (IoT), Smart Cities |
| **4. Statement of the Problem (SOP)** | 1. How can ultrasonic wave propagation features be extracted to differentiate between active micro-cracking and the curing process of self-healing agents? <br> 2. What edge-computing optimizations enable continuous, low-power acoustic monitoring on embedded piezoelectric sensor nodes? <br> 3. How does the density and placement of the sensor network impact the spatial resolution of crack localization in large concrete structures? |
| **5. Technologies** | C++, Python, TensorFlow Lite, Piezoelectric Transducers, ESP32, LoRaWAN |
| **6. Research Category** | Embedded Systems, Internet of Things (IoT), Signal Processing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Sensor Node Prototype, Edge AI Crack/Healing Classifier, Structural Dashboard |
| **10. Possible Future Extensions** | Integration with digital twins for predictive maintenance, autonomous drone-based sensor deployment for bridge inspection. |
| **11. References / Inspiration** | Research on self-healing concrete, piezoelectric structural health monitoring (SHM), edge AI deployment. |

## Idea 82
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Detecting Data Poisoning and Backdoor Injections in RAG Vector Databases Using Topological Data Analysis |
| **2. Description** | Retrieval-Augmented Generation (RAG) systems are highly vulnerable to data poisoning, where adversaries inject malicious documents into the vector database to manipulate LLM outputs. Traditional statistical anomaly detection struggles with high-dimensional embedding spaces. This thesis applies Topological Data Analysis (TDA), specifically persistent homology, to map the geometric and topological structures of the vector database. By identifying anomalous topological voids or dense clusters introduced by poisoned embeddings, the system detects and quarantines malicious injections before they reach the LLM. The primary contribution is a mathematically rigorous, geometry-aware security layer for enterprise RAG architectures. |
| **3. Target Domain** | Cybersecurity, Artificial Intelligence, Data Science |
| **4. Statement of the Problem (SOP)** | 1. How can persistent homology be computed efficiently on high-dimensional vector embeddings to detect topological anomalies indicative of data poisoning? <br> 2. What adversarial injection strategies are most effective at bypassing standard distance-metric outlier detection in vector databases? <br> 3. How does the TDA-based detection mechanism impact the retrieval latency and computational overhead of a real-time RAG pipeline? |
| **5. Technologies** | Python, Giotto-TDA / Ripser, PyTorch, FAISS / Qdrant, LangChain |
| **6. Research Category** | Cybersecurity, Artificial Intelligence, Mathematics |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | TDA Anomaly Detection Engine, Poisoning Attack Simulator, Security Audit Report |
| **10. Possible Future Extensions** | Automated remediation and re-indexing of vector databases, extension to multimodal (vision-language) RAG systems. |
| **11. References / Inspiration** | Topological Data Analysis literature, RAG security research, adversarial machine learning. |

## Idea 83
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Decentralized Acoustic SLAM and Microplastic Plume Tracking Using Autonomous Surface Vehicle (ASV) Swarms |
| **2. Description** | Tracking the dispersion of microplastics in coastal and riverine environments is hindered by the lack of real-time, in-situ sensing and the vastness of the search area. This research develops a swarm of low-cost Autonomous Surface Vehicles (ASVs) equipped with acoustic microplastic sensors and decentralized Simultaneous Localization and Mapping (SLAM). The ASVs utilize acoustic telemetry to share sparse environmental gradients and collaboratively map the microplastic plume using Gaussian Process regression. The expected contribution is a resilient, GPS-denied swarm intelligence framework that optimizes search paths to locate the source of microplastic pollution in dynamic aquatic environments. |
| **3. Target Domain** | Robotics, Environmental Science, Oceanography |
| **4. Statement of the Problem (SOP)** | 1. How can decentralized SLAM algorithms maintain swarm localization accuracy using only sparse, bandwidth-constrained acoustic underwater telemetry? <br> 2. What multi-agent exploration strategies optimize the mapping of dynamic, fluid-dispersed microplastic plumes compared to traditional lawnmower survey patterns? <br> 3. How do environmental factors like wave action and boat traffic impact the reliability of acoustic microplastic sensors and swarm communication? |
| **5. Technologies** | C++, ROS 2, PX4, Acoustic Modems, Gaussian Processes, Python |
| **6. Research Category** | Robotics, Distributed Systems, Environmental Informatics |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | ASV Swarm Simulation, Decentralized SLAM Algorithm, Plume Tracking Controller |
| **10. Possible Future Extensions** | Integration with autonomous underwater vehicles (AUVs) for 3D water column profiling, solar-powered continuous deployment. |
| **11. References / Inspiration** | Multi-robot SLAM literature, environmental plume tracking algorithms, acoustic underwater communication. |

## Idea 84
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Mitigating Visually Induced Motion Sickness (VIMS) in Virtual Reality Locomotion Using Galvanic Vestibular Stimulation (GVS) and Optic Flow Synchronization |
| **2. Description** | Visually Induced Motion Sickness (VIMS), or cybersickness, remains a primary barrier to widespread VR adoption, caused by the sensory conflict between visual optic flow and the vestibular system's perception of physical stillness. This thesis investigates the use of Galvanic Vestibular Stimulation (GVS)—applying mild electrical currents behind the ears to simulate vestibular signals—synchronized precisely with in-game locomotion. By developing a low-latency middleware that maps VR controller inputs and virtual acceleration to GVS waveforms, the system artificially induces the sensation of physical movement. The primary contribution is a hardware-software integrated framework that significantly reduces VIMS, enabling comfortable, extended use of VR for training and entertainment. |
| **3. Target Domain** | Human-Computer Interaction, Virtual Reality, Biomedical Engineering |
| **4. Statement of the Problem (SOP)** | 1. What mathematical mappings between virtual acceleration vectors and GVS current waveforms most accurately simulate the sensation of physical locomotion? <br> 2. How does the precise synchronization latency between visual optic flow and vestibular stimulation impact the reduction of cybersickness symptoms? <br> 3. What are the long-term habituation effects and safety thresholds of continuous GVS application during extended VR sessions? |
| **5. Technologies** | C#, Unity3D, C++, Custom GVS Hardware, OpenVR / SteamVR SDK, Biopotential Amplifiers |
| **6. Research Category** | Human-Computer Interaction, Virtual Reality, Hardware Engineering |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | GVS Middleware Plugin, Hardware Prototype, Clinical VIMS Evaluation Study |
| **10. Possible Future Extensions** | Application to flight and driving simulators, integration with full-body haptic suits for multimodal sensory substitution. |
| **11. References / Inspiration** | Galvanic Vestibular Stimulation literature, sensory conflict theory of motion sickness, VR locomotion research. |

## Idea 85
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Predicting CRISPR-Cas9 Off-Target Cleavage Sites Using Graph Attention Networks on 3D Chromatin Conformation (Hi-C) Data |
| **2. Description** | CRISPR-Cas9 gene editing holds immense therapeutic potential, but off-target DNA cleavage can cause severe, unintended mutations. Current predictive models rely primarily on 1D DNA sequence similarity, ignoring the complex 3D spatial folding of chromatin inside the nucleus, which dictates physical accessibility to the Cas9 complex. This research applies Graph Attention Networks (GATs) to Hi-C (chromatin conformation capture) data, modeling the genome as a 3D spatial graph. By integrating 1D sequence mismatch tolerance with 3D spatial proximity and epigenetic markers, the model accurately predicts physically viable off-target sites. The contribution is a highly precise, biologically grounded AI tool that improves the safety profile of therapeutic gene editing. |
| **3. Target Domain** | Bioinformatics, Artificial Intelligence, Genomics |
| **4. Statement of the Problem (SOP)** | 1. How can 3D chromatin conformation (Hi-C) data be effectively represented as a spatial graph to capture the physical accessibility of DNA sequences to the Cas9 complex? <br> 2. What graph attention mechanisms best weigh the relative importance of 1D sequence mismatch tolerance versus 3D spatial proximity in predicting off-target cleavage? <br> 3. How does the integration of epigenetic markers (e.g., DNA methylation, histone modifications) improve the predictive accuracy of the spatial GAT model? |
| **5. Technologies** | Python, PyTorch Geometric, BioPython, Hi-C Data Processing (e.g., Cooler), Scikit-learn |
| **6. Research Category** | Bioinformatics, Artificial Intelligence, Computational Biology |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | 3D Genomic GAT Model, Off-Target Prediction API, Biological Validation Report |
| **10. Possible Future Extensions** | Application to base editing and prime editing systems, integration with single-cell Hi-C data for tissue-specific off-target prediction. |
| **11. References / Inspiration** | CRISPR off-target prediction literature, Graph Neural Networks for genomics, Hi-C data analysis methodologies. |

## Idea 86
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Energy-Aware Beamforming and User Scheduling in Cell-Free Massive MIMO Networks Using Federated Multi-Agent Reinforcement Learning |
| **2. Description** | Cell-free massive MIMO is a foundational technology for 6G, offering immense spectral efficiency by surrounding users with distributed access points. However, the massive number of active antennas and complex digital signal processing result in prohibitive energy consumption. This thesis proposes a decentralized energy management framework using Federated Multi-Agent Reinforcement Learning (FMARL). Each access point acts as an agent, learning to optimize its beamforming vectors and user scheduling policies to maximize spectral efficiency while minimizing transmit power and hardware power consumption. By federating the learning process, the network adapts to dynamic user mobility without centralized data collection. The contribution is a scalable, green networking protocol that makes 6G cell-free architectures economically and environmentally viable. |
| **3. Target Domain** | Telecommunications, Networking, Green IT |
| **4. Statement of the Problem (SOP)** | 1. How can FMARL agents optimize continuous beamforming vectors and discrete user scheduling decisions under strict, distributed power constraints? <br> 2. What federated aggregation strategies best handle the non-stationary environment caused by high-speed user mobility in cell-free networks? <br> 3. How does the proposed energy-aware protocol compare to centralized convex optimization baselines in terms of energy efficiency (bits/Joule) and computational latency? |
| **5. Technologies** | Python, PyTorch, Ray RLlib, MATLAB 5G Toolbox / NS-3, Federated Learning Frameworks |
| **6. Research Category** | Networking, Artificial Intelligence, Telecommunications |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | FMARL Beamforming Algorithm, Network Simulation Environment, Energy Efficiency Benchmark |
| **10. Possible Future Extensions** | Integration with reconfigurable intelligent surfaces (RIS) for passive beamforming, hardware-aware RL for analog-to-digital converter (ADC) resolution scaling. |
| **11. References / Inspiration** | Cell-free massive MIMO literature, multi-agent reinforcement learning in wireless networks, 6G energy efficiency standards. |

## Idea 87
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Algorithmic Auditing of DeFi Lending Protocols for Economic Exploitability Using Symbolic Execution and Game Theory |
| **2. Description** | Decentralized Finance (DeFi) lending protocols manage billions of dollars, but smart contracts are frequently drained via complex economic exploits like oracle manipulation, flash loan attacks, and bad debt accrual. Traditional code-level auditing misses these logic-level financial vulnerabilities. This research develops an automated auditing engine that combines symbolic execution of Solidity bytecode with algorithmic game theory. The system models the protocol as a state machine and utilizes bounded model checking to search for sequences of transactions (e.g., flash loan -> manipulate oracle -> borrow -> liquidate) that result in a net-positive, risk-free profit for an attacker. The primary contribution is a formal verification tool specifically designed to mathematically prove the economic soundness of DeFi protocols before mainnet deployment. |
| **3. Target Domain** | Blockchain, FinTech, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. How can the continuous, real-world financial state of a DeFi protocol (e.g., token prices, liquidity pool depths) be abstracted into bounded symbolic variables for model checking? <br> 2. What game-theoretic algorithms efficiently search the exponentially large state space of flash loan transaction sequences to identify profitable economic exploits? <br> 3. How does the automated symbolic execution engine handle the complex external oracle dependencies and cross-contract composability inherent in modern DeFi ecosystems? |
| **5. Technologies** | Solidity, Python, Echidna / Manticore, Z3 Theorem Prover, Foundry, Game Theory Solvers |
| **6. Research Category** | Cybersecurity, Distributed Systems, Financial Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Economic Exploitability Auditor, Symbolic Execution Engine, DeFi Vulnerability Dataset |
| **10. Possible Future Extensions** | Real-time mempool monitoring to block active flash loan attacks, automated generation of economic circuit breakers (pausing mechanisms). |
| **11. References / Inspiration** | DeFi security research papers, symbolic execution for smart contracts, algorithmic game theory in finance. |

## Idea 88
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Privacy-Preserving Urban Noise Pollution Mapping and Source Classification Using Distributed Smartphone Microphones and Federated Audio Tagging |
| **2. Description** | Chronic urban noise pollution is linked to severe cardiovascular and cognitive health issues, yet city-wide acoustic monitoring is limited by the high cost of dedicated sensor networks. This thesis leverages the ubiquity of smartphones to create a crowdsourced, privacy-preserving acoustic mapping platform. Users opt-in to run a lightweight, edge-processed audio tagging model that classifies local noise sources (e.g., construction, traffic, sirens) and calculates decibel levels without ever recording or transmitting raw audio. A federated learning backend aggregates these acoustic embeddings to generate high-resolution, real-time urban noise heatmaps. The contribution is a scalable, GDPR-compliant environmental monitoring framework that empowers city planners to enforce noise ordinances and design healthier urban soundscapes. |
| **3. Target Domain** | Smart Cities, Environmental Science, Edge AI |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight audio tagging models maintain high classification accuracy on diverse, uncalibrated smartphone microphones in highly variable urban environments? <br> 2. What privacy-preserving federated learning techniques prevent the reconstruction of private conversations from transmitted acoustic embeddings? <br> 3. How can the system accurately estimate absolute Sound Pressure Levels (SPL) without requiring physical hardware calibration of the crowdsourced smartphones? |
| **5. Technologies** | Android / iOS (Swift/Kotlin), TensorFlow Lite, Python, PySyft, OpenStreetMap, FastAPI |
| **6. Research Category** | Internet of Things (IoT), Audio Processing, Edge Computing |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Mobile Crowdsourcing App, Federated Audio Model, GIS Noise Heatmap Dashboard |
| **10. Possible Future Extensions** | Integration with municipal 311 complaint systems, predictive noise modeling based on urban traffic and construction permit data. |
| **11. References / Inspiration** | Urban acoustic ecology literature, federated learning on mobile devices, smartphone audio calibration research. |

## Idea 89
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Generation of Formal Verification Proofs from Natural Language Specifications Using LLMs and Neuro-Symbolic Solvers |
| **2. Description** | Formal verification mathematically proves the correctness of critical software (e.g., aerospace, cryptographic protocols), but writing proofs in languages like Coq or Lean requires immense expertise and time. This thesis proposes a neuro-symbolic pipeline that translates natural language software specifications into formal logic, and then utilizes Large Language Models guided by automated theorem provers to iteratively generate the proof scripts. By using the theorem prover as a deterministic compiler and feedback loop, the LLM corrects its own logical hallucinations until the proof compiles and verifies successfully. The primary contribution is an AI-assisted formal methods tool that drastically lowers the barrier to entry for mathematically guaranteed software engineering. |
| **3. Target Domain** | Software Engineering, Artificial Intelligence, Mathematics |
| **4. Statement of the Problem (SOP)** | 1. How accurately can LLMs translate ambiguous natural language software requirements into strict, syntactically valid formal logic specifications (e.g., Lean 4)? <br> 2. What reinforcement learning or prompt-chaining strategies enable the LLM to effectively utilize the error feedback from the automated theorem prover to self-correct proof scripts? <br> 3. How does the neuro-symbolic pipeline perform on complex, stateful systems (e.g., concurrent algorithms) compared to purely heuristic LLM code generation? |
| **5. Technologies** | Python, Lean 4 / Coq, Llama-3 / GPT-4 API, LangChain, AST Parsers |
| **6. Research Category** | Software Engineering, Artificial Intelligence, Formal Methods |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Neuro-Symbolic Proof Generator, Lean 4 Integration Plugin, Verification Benchmark Suite |
| **10. Possible Future Extensions** | Automated generation of formal proofs for smart contract financial logic, integration with CI/CD pipelines for continuous mathematical verification. |
| **11. References / Inspiration** | Lean 4 documentation, neuro-symbolic AI literature, LLMs for theorem proving (e.g., AlphaGeometry, LeanDojo). |

## Idea 90
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Continuous, Non-Invasive Hydration Monitoring Using Multimodal Fusion of Bioimpedance Spectroscopy and Photoplethysmography (PPG) on Smartwatches |
| **2. Description** | Dehydration severely impacts athletic performance, cognitive function, and elderly health, but current monitoring relies on subjective thirst or invasive blood tests. This research develops a smartwatch-based hydration tracking system that fuses Bioimpedance Spectroscopy (BIS)—measuring the electrical resistance of tissue fluid—with Photoplethysmography (PPG) pulse wave velocity. A multimodal machine learning model analyzes the shifts in extracellular/intracellular fluid ratios and cardiovascular hemodynamics to estimate total body water continuously. The primary contribution is a highly accurate, non-invasive wearable algorithm that provides real-time hydration alerts, preventing heatstroke in athletes and managing fluid balance in clinical populations. |
| **3. Target Domain** | Healthcare, Wearable Technology, Signal Processing |
| **4. Statement of the Problem (SOP)** | 1. How can bioimpedance spectroscopy and PPG pulse wave features be temporally aligned and fused to accurately differentiate between dehydration and normal cardiovascular fluctuations? <br> 2. What machine learning architectures best compensate for the severe motion artifacts and skin-electrode contact noise inherent in wrist-worn bioimpedance sensors? <br> 3. How does the accuracy of the multimodal wearable model compare to clinical gold standards (e.g., bioimpedance analysis scales, urine specific gravity) across varying skin tones and ambient temperatures? |
| **5. Technologies** | Python, C++, Scipy, TensorFlow Lite, Apple Watch / WearOS APIs, Custom Bioimpedance Hardware |
| **6. Research Category** | Biomedical Engineering, Signal Processing, Artificial Intelligence |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Multimodal Hydration Algorithm, Smartwatch Application, Clinical Validation Study |
| **10. Possible Future Extensions** | Integration with continuous sweat electrolyte sensors, predictive hydration modeling for endurance athletes based on GPS and weather data. |
| **11. References / Inspiration** | Bioimpedance spectroscopy literature, PPG hemodynamics research, wearable health monitoring clinical trials. |

# Curated Undergraduate Computer Science Thesis Ideas (Batch 10 of 20)

## Idea 91
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Real-Time Adaptive Functional Electrical Stimulation (FES) for Drop-Foot Gait Restoration Using Wearable Ultrasound Muscle Imaging and Edge AI |
| **2. Description** | Drop-foot is a common gait abnormality caused by neurological conditions, typically treated with Functional Electrical Stimulation (FES) of the peroneal nerve. However, current FES systems operate in an open-loop manner, failing to adapt to muscle fatigue or varying terrain, which leads to inefficient walking and rapid muscle exhaustion. This research proposes a closed-loop FES system that utilizes a wearable, low-power ultrasound probe to measure real-time muscle fascicle length and contraction velocity. An edge-deployed AI model processes these biomechanical features to dynamically adjust the stimulation amplitude and timing. The primary contribution is a physiologically responsive neuroprosthetic control system that significantly improves gait symmetry and delays muscle fatigue compared to traditional timed FES devices. |
| **3. Target Domain** | Biomedical Engineering, Healthcare, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can high-frequency ultrasound echoes be processed on resource-constrained edge microcontrollers to extract real-time muscle fascicle kinematics? <br> 2. What closed-loop control algorithms best map continuous muscle contraction velocity to optimal FES stimulation parameters to compensate for localized muscle fatigue? <br> 3. How does the latency of the ultrasound-to-stimulation pipeline impact the natural kinematics of the swing phase during human walking? |
| **5. Technologies** | C++, Python, PyTorch, Wearable Ultrasound Probes, ARM Cortex-M, Digital Signal Processing (DSP) |
| **6. Research Category** | Embedded Systems, Signal Processing, Biomedical Engineering |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Closed-Loop FES Prototype, Muscle Kinematics Extraction Algorithm, Gait Analysis Benchmark |
| **10. Possible Future Extensions** | Integration with inertial measurement units (IMUs) for terrain-adaptive stimulation, extension to multi-joint exoskeleton control. |
| **11. References / Inspiration** | Literature on closed-loop FES, wearable ultrasound imaging research, biomechanics of drop-foot gait. |

## Idea 92
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Generative 3D Diffusion Models for the De Novo Design of Metal-Organic Frameworks (MOFs) Optimized for Direct Air Carbon Capture |
| **2. Description** | Metal-Organic Frameworks (MOFs) are highly porous materials with immense potential for Direct Air Capture (DAC) of CO2, but discovering optimal structures via trial-and-error synthesis is prohibitively slow. This thesis applies 3D graph-based diffusion models to generate novel MOF crystal structures from scratch. By conditioning the generative process on specific target properties—such as pore aperture size, surface area, and CO2/N2 selectivity—the model explores vast, uncharted chemical spaces. The expected contribution is an accelerated, AI-driven materials discovery pipeline that outputs highly probable, synthesizable MOF candidates, drastically reducing the R&D timeline for next-generation carbon capture technologies. |
| **3. Target Domain** | Materials Science, Artificial Intelligence, Green Tech |
| **4. Statement of the Problem (SOP)** | 1. How can 3D diffusion models be adapted to generate physically valid, periodic crystal lattices with strict geometric and chemical bonding constraints? <br> 2. What surrogate machine learning models can rapidly evaluate the CO2 adsorption capacity of generated MOFs without relying on computationally expensive Grand Canonical Monte Carlo (GCMC) simulations? <br> 3. How can synthesizability scores be integrated into the diffusion sampling process to ensure the generated materials can be physically created in a laboratory? |
| **5. Technologies** | Python, PyTorch3D, Pymatgen, CoRE MOF Database, Equivariant Graph Neural Networks |
| **6. Research Category** | Artificial Intelligence, Cheminformatics, Data Science |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | 3D Generative Diffusion Model, MOF Screening Pipeline, Candidate Material Dataset |
| **10. Possible Future Extensions** | Integration with automated robotic laboratories (self-driving labs) for physical synthesis, multi-objective optimization for moisture stability. |
| **11. References / Inspiration** | CoRE MOF database, 3D diffusion models for molecular generation (e.g., DiffLinker, EDOS), carbon capture literature. |

## Idea 93
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | In-Vehicle CAN Bus Intrusion Detection and Isolation Using Temporal Graph Neural Networks and ARM TrustZone Trusted Execution Environments |
| **2. Description** | Modern vehicles rely on the Controller Area Network (CAN) bus, which lacks inherent authentication, making it highly vulnerable to remote and physical cyber-physical attacks. Traditional intrusion detection systems (IDS) running on the main infotainment or gateway ECUs can be bypassed or disabled by compromised software. This research implements a hardware-backed IDS utilizing Temporal Graph Neural Networks (TGNs) to model the complex timing and payload relationships of CAN messages. Crucially, the inference engine is deployed entirely within the ARM TrustZone Trusted Execution Environment (TEE), ensuring the security monitor remains isolated and tamper-proof even if the main vehicle operating system is compromised. |
| **3. Target Domain** | Automotive Engineering, Cybersecurity, Embedded Systems |
| **4. Statement of the Problem (SOP)** | 1. How can Temporal Graph Neural Networks effectively model the strict, periodic timing constraints and payload dependencies of automotive CAN bus traffic? <br> 2. What is the computational and memory overhead of running continuous TGN inference within the highly constrained, secure memory enclave of ARM TrustZone? <br> 3. How does the TEE-isolated IDS handle zero-day anomalies and sophisticated replay attacks that mimic legitimate message timing patterns? |
| **5. Technologies** | C, Rust, ARM TrustZone (OP-TEE), PyTorch Geometric, SocketCAN, Raspberry Pi / NXP i.MX Boards |
| **6. Research Category** | Cybersecurity, Embedded Systems, Networking |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | TEE-Isolated IDS Agent, CAN Bus Attack Dataset, Latency and Security Audit Report |
| **10. Possible Future Extensions** | Automated generation of CAN firewall rules based on detected anomalies, integration with Vehicle-to-Everything (V2X) security modules. |
| **11. References / Inspiration** | ARM TrustZone documentation, automotive CAN bus security research, Temporal Graph Network literature. |

## Idea 94
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | On-Orbit Cloud Occlusion Inpainting and Super-Resolution of Multispectral Satellite Imagery Using Quantized Latent Diffusion Models |
| **2. Description** | Earth observation satellites capture vast amounts of multispectral imagery, but cloud cover frequently obscures critical surface data, and downlinking raw, high-resolution images requires massive bandwidth and ground-station time. This thesis proposes an on-orbit edge computing pipeline that utilizes heavily quantized Latent Diffusion Models (LDMs) to perform cloud masking, inpainting, and super-resolution directly on the satellite. By processing and compressing the data into high-fidelity, cloud-free insights before transmission, the system drastically reduces downlink requirements. The primary contribution is a radiation-tolerant, bandwidth-efficient AI architecture that maximizes the scientific yield of LEO satellite constellations. |
| **3. Target Domain** | Aerospace Engineering, Computer Vision, Edge Computing |
| **4. Statement of the Problem (SOP)** | 1. How can Latent Diffusion Models be aggressively quantized (e.g., INT8/INT4) to run on space-grade or COTS edge hardware without severe degradation in inpainting quality? <br> 2. What multispectral consistency constraints must be applied to the diffusion process to ensure the inpainted pixels maintain physical validity across different spectral bands? <br> 3. How does on-orbit processing and selective downlinking impact the overall data latency and bandwidth utilization compared to traditional raw-data transmission? |
| **5. Technologies** | C++, Python, PyTorch, ONNX Runtime, FPGA / Edge GPU Simulators, Sentinel-2 Datasets |
| **6. Research Category** | Computer Vision, Edge Computing, Remote Sensing |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Quantized Diffusion Pipeline, On-Orbit Processing Simulator, Bandwidth vs. Quality Analysis |
| **10. Possible Future Extensions** | Integration with onboard change-detection algorithms to only downlink anomalous events, federated learning across satellite swarms for model updates. |
| **11. References / Inspiration** | Latent Diffusion Models (Stable Diffusion) architecture, edge AI in space (e.g., Lockheed Martin SmartSat), remote sensing cloud masking. |

## Idea 95
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Autonomous Precision Pollination in Greenhouse Environments Using Micro-UAVs, Floral Receptivity Vision, and Electrostatic Pollen Dispensing |
| **2. Description** | The global decline of natural pollinators threatens crop yields, particularly in enclosed greenhouse environments where wind and insects are absent. This research develops an autonomous micro-UAV system designed for precision pollination. Using edge-based computer vision, the drone identifies target flowers and classifies their reproductive receptivity (e.g., anthesis stage). Upon confirming a receptive flower, the UAV utilizes an electrostatic dispensing mechanism to apply a micro-dose of dry pollen directly to the stigma, minimizing waste. The expected contribution is a highly targeted, robotic pollination framework that replaces inefficient, labor-intensive manual pollination or broad-spectrum drone spraying. |
| **3. Target Domain** | Agriculture, Robotics, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can lightweight computer vision models accurately classify the subtle morphological changes indicating floral receptivity under variable greenhouse lighting? <br> 2. What aerodynamic control strategies allow micro-UAVs to maintain stable hovering and precise positioning in the turbulent downwash generated by their own rotors near delicate flowers? <br> 3. How does the efficiency and fruit-set rate of electrostatic pollen dispensing compare to traditional manual pollination and liquid-based drone spraying? |
| **5. Technologies** | C++, Python, ROS 2, PX4, Crazyflie / Custom Micro-UAV, OpenCV, High-Voltage Electrostatic Circuits |
| **6. Research Category** | Robotics, Computer Vision, Agricultural Engineering |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | Micro-UAV Pollinator Prototype, Floral Receptivity Model, Pollination Efficiency Benchmark |
| **10. Possible Future Extensions** | Swarm coordination for large-scale greenhouse coverage, integration with multispectral imaging for plant stress detection during flight. |
| **11. References / Inspiration** | RoboBee and micro-UAV aerodynamics literature, precision pollination research, electrostatic agricultural spraying. |

## Idea 96
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Detection of Wash Trading and Artificial Price Inflation in NFT Markets Using Heterogeneous Temporal Graph Neural Networks |
| **2. Description** | The Non-Fungible Token (NFT) and digital art markets are heavily manipulated through "wash trading"—the practice of repeatedly selling an asset to oneself or colluding wallets to artificially inflate trading volume and floor prices. Traditional tabular analytics fail to capture the complex, multi-hop relationships and temporal patterns of these coordinated rings. This thesis applies Heterogeneous Temporal Graph Neural Networks (HTGNNs) to model the blockchain as a dynamic graph of wallets, tokens, and transactions over time. By learning the structural and temporal signatures of organic trading versus coordinated manipulation, the system accurately flags wash-traded collections. The contribution is a robust market-integrity tool that brings transparency to Web3 digital asset markets. |
| **3. Target Domain** | FinTech, Blockchain, Cybersecurity |
| **4. Statement of the Problem (SOP)** | 1. How can Heterogeneous Temporal Graph Neural Networks effectively capture the evolving, multi-hop relationships between colluding wallets and specific NFT contracts over time? <br> 2. What graph-based feature extraction techniques best differentiate between organic, high-demand trading volume and artificial, circular wash trading patterns? <br> 3. How does the system maintain detection accuracy across different blockchain architectures (e.g., Ethereum vs. Solana) with varying transaction speeds and fee structures? |
| **5. Technologies** | Python, PyTorch Geometric, The Graph (Subgraphs), Neo4j, Web3.py, Etherscan APIs |
| **6. Research Category** | Data Science, Distributed Systems, FinTech |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | HTGNN Fraud Detection Model, Blockchain Graph Extractor, Market Integrity Dashboard |
| **10. Possible Future Extensions** | Real-time mempool analysis to front-run or block wash trades, expansion to detect rug-pulls and liquidity manipulation in DeFi tokens. |
| **11. References / Inspiration** | Chainalysis crypto crime reports, temporal graph neural network literature, Web3 market manipulation research. |

## Idea 97
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Early Detection of Diabetic Foot Ulcers Using Multimodal Fusion of Smartphone Thermal Imaging and RGB Photogrammetry on Edge Devices |
| **2. Description** | Diabetic foot ulcers (DFUs) are a leading cause of lower-limb amputations. The earliest clinical indicator of a developing ulcer is localized inflammation, which manifests as a temperature anomaly before visible skin breakdown occurs. This research develops a mobile screening application that fuses data from smartphone-attached thermal cameras with standard RGB photogrammetry. An edge-deployed multimodal neural network aligns the thermal heatmaps with 3D foot contours to segment and quantify localized inflammation, compensating for ambient temperature and varying skin tones. The primary contribution is an accessible, low-cost, at-home screening tool that empowers diabetic patients to detect and treat ulcers before they become limb-threatening. |
| **3. Target Domain** | Healthcare, Mobile Computing, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can thermal and RGB images be accurately co-registered and aligned on mobile devices despite the differing focal lengths and parallax errors of dual-lens attachments? <br> 2. What multimodal fusion architectures best isolate pathological thermal anomalies from normal physiological temperature variations caused by ambient room temperature or recent physical activity? <br> 3. How does the system maintain segmentation accuracy across diverse skin tones and varying degrees of foot deformity (e.g., Charcot foot)? |
| **5. Technologies** | Python, TensorFlow Lite, FLIR Mobile SDK, OpenCV, Android / iOS, 3D Photogrammetry |
| **6. Research Category** | Computer Vision, Mobile Computing, Healthcare Informatics |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Mobile Screening App, Thermal-RGB Fusion Model, Clinical Feasibility Study |
| **10. Possible Future Extensions** | Integration with continuous glucose monitors (CGMs) to correlate systemic glycemic control with localized inflammation, automated telemedicine triage routing. |
| **11. References / Inspiration** | Diabetic foot thermography clinical trials, FLIR mobile integration documentation, multimodal medical image fusion. |

## Idea 98
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Dynamic Routing and Wavelength Assignment in Quantum Key Distribution (QKD) Networks Using Multi-Agent Deep Reinforcement Learning |
| **2. Description** | The future Quantum Internet relies on Quantum Key Distribution (QKD) to establish theoretically unbreakable encryption keys. However, routing entangled photons through optical fiber networks is highly complex due to severe signal attenuation, decoherence, and the no-cloning theorem, which prevents traditional signal amplification. This thesis utilizes Multi-Agent Deep Reinforcement Learning (MADRL) to optimize dynamic routing and wavelength assignment in hybrid classical-quantum optical networks. Each network node acts as an agent, learning to allocate scarce quantum resources and establish entanglement paths based on real-time fiber conditions and key-demand traffic. The contribution is a scalable, intelligent control plane that maximizes the secure key generation rate of emerging quantum networks. |
| **3. Target Domain** | Quantum Networking, Telecommunications, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How can MADRL agents optimize the conflicting objectives of maximizing quantum key generation rates while minimizing interference with classical data traffic on the same optical fiber? <br> 2. What reward functions best account for the non-linear physics of photon loss, decoherence, and quantum memory limits in long-distance entanglement routing? <br> 3. How does the decentralized MADRL control plane adapt to sudden fiber link failures or node outages compared to centralized heuristic routing algorithms? |
| **5. Technologies** | Python, Ray RLlib, NetSquid / SeQUeNCe (Quantum Simulators), PyTorch, Optical Networking Protocols |
| **6. Research Category** | Networking, Quantum Computing, Artificial Intelligence |
| **7. Novelty Level** | Cutting-edge |
| **8. Difficulty Level** | Expert |
| **9. Expected Deliverables** | MADRL Routing Algorithm, Quantum Network Simulation Environment, Key-Rate Optimization Report |
| **10. Possible Future Extensions** | Integration with quantum repeater placement optimization, extension to satellite-to-ground quantum routing networks. |
| **11. References / Inspiration** | SeQUeNCe quantum network simulator documentation, MADRL for optical networks, QKD routing literature. |

## Idea 99
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Markerless Augmented Reality Physics Laboratories Using Real-Time 3D Object Tracking and Synchronized Rigid-Body Dynamics Engines |
| **2. Description** | Remote and hybrid STEM education often relies on 2D virtual simulations that lack the tactile intuition and spatial reasoning developed in physical laboratories. This thesis develops a markerless Augmented Reality (AR) physics laboratory that overlays interactive, physically accurate simulations onto real-world, everyday objects. Using advanced 3D object tracking and depth estimation, the system recognizes physical boundaries (e.g., a real table or ramp) and synchronizes a rigid-body dynamics engine to simulate virtual projectiles, fluids, or electromagnetic fields interacting seamlessly with the physical environment. The primary contribution is an immersive, low-cost educational platform that bridges the gap between abstract virtual simulations and tangible physical experimentation. |
| **3. Target Domain** | Educational Technology, Augmented Reality, Computer Vision |
| **4. Statement of the Problem (SOP)** | 1. How can markerless 3D object tracking and spatial meshing be optimized to run at high framerates on mobile AR devices without causing thermal throttling? <br> 2. What collision-detection algorithms ensure seamless and physically accurate interactions between virtual rigid bodies and dynamically tracked, imperfect physical surfaces? <br> 3. How does the use of spatially anchored AR physics simulations impact student spatial reasoning and conceptual retention compared to traditional 2D screen-based simulations? |
| **5. Technologies** | C#, Unity3D, ARFoundation / ARCore / ARKit, MediaPipe, Bullet Physics Engine, C++ |
| **6. Research Category** | Human-Computer Interaction, Computer Vision, Educational Technology |
| **7. Novelty Level** | Medium |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | AR Physics Lab Application, Spatial Tracking Pipeline, Educational Efficacy User Study |
| **10. Possible Future Extensions** | Multi-user collaborative AR laboratories, integration with physical IoT sensors to feed real-world data into the virtual simulation. |
| **11. References / Inspiration** | Unity ARFoundation documentation, markerless tracking research, physics education research (PER) literature. |

## Idea 100
| Feature | Details |
| :--- | :--- |
| **1. Thesis Title** | Automated Detection of Temporal Inconsistencies and Logical Contradictions in Multi-Party Contracts Using Temporal Knowledge Graphs and LLMs |
| **2. Description** | Complex corporate and multi-party legal contracts contain dense networks of conditional obligations, deadlines, and dependencies. Human reviewers frequently miss subtle temporal inconsistencies (e.g., an obligation due before its prerequisite condition can be met). This research develops an NLP pipeline that utilizes Large Language Models to extract contractual events, conditions, and deadlines, structuring them into a Temporal Knowledge Graph (TKG). A deterministic temporal reasoning engine then traverses the graph to identify logical paradoxes, impossible timelines, and conflicting clauses. The expected contribution is a highly rigorous, automated contract auditing tool that prevents costly legal disputes arising from poorly drafted temporal logic. |
| **3. Target Domain** | Legal Technology, Natural Language Processing, Artificial Intelligence |
| **4. Statement of the Problem (SOP)** | 1. How accurately can LLMs extract complex, nested temporal dependencies and conditional logic from unstructured legal text to populate a formal Temporal Knowledge Graph? <br> 2. What graph-traversal and temporal reasoning algorithms are most effective at detecting cyclical dependencies and impossible chronological constraints within the TKG? <br> 3. How does the system handle ambiguous legal phrasing (e.g., "reasonable time," "promptly") when constructing strict temporal boundaries for the reasoning engine? |
| **5. Technologies** | Python, LangChain, Neo4j (Graph DB), Llama-3 / GPT-4 API, AllenAI (Temporal Logic), spaCy |
| **6. Research Category** | Natural Language Processing, Artificial Intelligence, Legal Tech |
| **7. Novelty Level** | High |
| **8. Difficulty Level** | Advanced |
| **9. Expected Deliverables** | Temporal Knowledge Graph Extractor, Logical Contradiction Engine, Contract Auditing Web Interface |
| **10. Possible Future Extensions** | Automated redlining and suggestion of corrected temporal clauses, integration with project management software to auto-generate compliance timelines. |
| **11. References / Inspiration** | Temporal knowledge graph reasoning literature, LegalBERT research, automated contract analysis frameworks. |
