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
