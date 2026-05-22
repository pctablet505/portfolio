# RAHUL KUMAR

**Software Engineer (Machine Learning)** | Google — Keras Team  
Hyderabad, India · [work.rahul126@gmail.com](mailto:work.rahul126@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rahul126) · [GitHub](https://www.github.com/pctablet505) · [Hackerrank](https://www.hackerrank.com/stopslavery404)

---

## Summary

Software Engineer (Machine Learning) at Google, driving cross-backend model portability and on-device deployment for the Keras ecosystem. Authored official Keras.io guides, shipped LiteRT export for PyTorch backend, and contributed 75+ PRs across Keras, KerasHub, and TensorFlow — infrastructure used by millions of developers. Previously built production on-device AI at Samsung R&D (computer vision, face recognition, sensor fusion) and Qualcomm (DSP-optimized edge AI). Passionate about open-source ML infrastructure, reinforcement learning, and algorithmic trading.

---

## Experience

- ### [Google](https://www.google.com/)
	**Software Engineer (Machine Learning)** — Keras Team

	📅 Feb 2025 – Present · Hyderabad, India

	- Shipped LiteRT export support for the PyTorch backend in Keras 3, enabling seamless on-device deployment of PyTorch-trained models via TensorFlow Lite / LiteRT.
	- Authored the official Keras.io guide for exporting models to LiteRT, adopted as canonical documentation for the ecosystem.
	- Contributed 75+ PRs across keras-team/keras, keras-team/keras-hub, and tensorflow/tensorflow: bug fixes, performance optimizations, security patches, and new export capabilities.
	- Fixed critical production issues: Attention layer N-D input support, custom model weight serialization with nested sublayers, TPU FlashAttention compatibility, OpenVINO backend bugs.
	- Identified and patched a namespace-hijacking vulnerability in `deserialize_keras_object` affecting model deserialization security.
	- Built end-to-end Android demos (Gemma 3 270M on-device LLM inference) showcasing Keras → LiteRT → mobile deployment pipeline.

	---
- ### [Qualcomm](https://www.qualcomm.com/)
	**Machine Learning Engineer**

	📅 Sept 2024 – Jan 2025 · Hyderabad, India

	- Developed DSP-optimized inference pipelines for computer vision models on Qualcomm Snapdragon platforms.
	- Built production Android demos demonstrating hardware-accelerated AI (GPU, DSP, NPU delegation) for client presentations and benchmarking.

	---
- ### [Samsung R&D Institute India](https://research.samsung.com/sri-n)
	**Research & Development Engineer**

	📅 July 2022 – Sept 2024 · Noida, India

	- Led Knox Capture: end-to-end barcode scanning system for damaged barcodes using YOLOv11 detection, Mask R-CNN segmentation, U-Net restoration, and synthetic dataset generation.
	- Architected SRIN-Satyapan: anti-cheat proctored exam platform with real-time face recognition, supporting 10,000+ registered faces across Android and web portals.
	- Built real-time multi-face recognition system with optimized embedding search: reduced lookup time from 1,200 ms to 87 ms on Android tablets.
	- Developed sensor-fusion solutions for drop detection (compressed model from millions of params to <20) and car crash detection using statistical models on Android.
	- Honored with MD Appreciation Award for developing SRIN-Satyapan.

	---
- ### [Samsung R&D Institute India](https://research.samsung.com/sri-n)
	**Intern**

	📅 Jan 2022 – June 2022 · Noida, India

	- Trained CycleGAN for generative AI use cases in Samsung's software competency program.
	- Gained hands-on experience with Android Studio, on-device model deployment, and ML pipeline integration.

	---

## Featured Open Source

Selected contributions to the Keras and TensorFlow ecosystems:

| PR | Repository | Impact |
|---|---|---|
| [LiteRT export for PyTorch backend](https://github.com/keras-team/keras/pulls?q=is%3Apr+author%3Apctablet505+pytorch+backend) | keras-team/keras | Enabled on-device deployment of PyTorch-trained Keras 3 models |
| [Attention N-D input fix](https://github.com/keras-team/keras/pull/20429) | keras-team/keras | Restored N-D input support for transformer variants |
| [Security fix: deserialize_keras_object](https://github.com/keras-team/keras/pulls?q=is%3Apr+author%3Apctablet505+namespace) | keras-team/keras | Closed arbitrary code execution vulnerability in model deserialization |
| [Auto-enable large_model ONNX export](https://github.com/keras-team/keras/pull/22825) | keras-team/keras | Fixed ONNX export for models >1.5GB (Gemma, LLaMA) |
| [Keras 3 + TF 2.20 + Python 3.13 compatibility](https://github.com/keras-team/keras/pulls?q=is%3Apr+author%3Apctablet505+python+3.13) | keras-team/keras | Restored LiteRT export across latest releases |
| [LiteRT-LM export for KerasHub](https://github.com/keras-team/keras-hub/pulls?q=is%3Apr+author%3Apctablet505+litert) | keras-team/keras-hub | On-device LLM inference with prefill/decode signatures |
| [Official LiteRT export guide](https://github.com/keras-team/keras-io/pulls?q=is%3Apr+author%3Apctablet505) | keras-team/keras-io | Canonical documentation for Keras → LiteRT export |

**Full contribution history:** [92 PRs across keras-team, google-ai-edge, tensorflow, and more](https://github.com/pulls?q=is%3Apr+author%3Apctablet505)

---

## Projects

### Professional & Open Source

1.	### [Keras & LiteRT Ecosystem (Google)](https://keras.io/guides/)

	Professional open-source work as part of the Keras Team at Google. Driving LiteRT export capabilities, cross-backend model portability, and production-grade deep learning infrastructure.

	- Implemented LiteRT export support for the PyTorch backend in Keras 3, enabling seamless on-device deployment of PyTorch-trained models via TFLite / LiteRT.
	- Built LiteRT-LM export for KerasHub with prefill/decode signatures, optimized for on-device large language model inference.
	- Authored the official Keras.io guide for exporting models to LiteRT, covering TensorFlow and PyTorch backends with end-to-end examples.
	- Fixed critical bugs in the Attention layer (N-D input support), custom model weight serialization with nested sublayers, and TPU FlashAttention compatibility.
	- Identified and patched a namespace-hijacking vulnerability in `deserialize_keras_object` affecting model deserialization security.
	- Built end-to-end Android demos (Gemma 3 270M IT on-device LLM) demonstrating the full Keras → LiteRT → mobile deployment pipeline.
	- Contributed to LiteRT-Torch converter integration for broader CPU/GPU/NPU on-device coverage.

	[code](https://github.com/pctablet505/keras) · [keras-hub](https://github.com/pctablet505/keras-hub) · [keras-io](https://github.com/pctablet505/keras-io)

	___
2.	### [Algorithmic Trading (RL Alpha Labs)](https://pctablet505.github.io/RLAlphaLabs/)

	AI-driven trading platform tailored for the Indian stock market, integrating advanced reinforcement learning and heuristic strategies for optimized portfolio management.

	- Leveraged Kite-Connect API from Zerodha to build a robust historical data downloader, efficiently retrieving and storing comprehensive market data for stocks, ETFs, and other instruments in a high-performance database.
	- Designed a custom user interface for seamless portfolio management, real-time paper trading, and algorithm-based automated execution.
	- Engineered heuristic algorithms driven by technical signals for accurate trade simulation and backtesting.
	- Created a versatile trading environment supporting heuristic, strategy-based, and reinforcement learning agents, with full portfolio management simulation.
	- Implemented advanced risk management and loss tolerance systems to ensure agent stability and compliance.
	- Developing a sophisticated reinforcement learning agent with shared learnable parameters to trade across diverse entities, including multiple stocks, markets, brokers, cryptocurrencies, equities, and commodities.

	[code](https://github.com/pctablet505/AlgoTrading)

	___
3.	### ATS Optimizer

	A fully-automated job application pipeline that eliminates every manual step between discovering a job and submitting an application. Built for candidates applying to 50+ jobs per day.

	- Architected a modular system with five core engines: Candidate Profile, ATS Analysis, Job Discovery, Resume Generation, and Application Automation.
	- Implemented ATS scoring algorithm using NLP keyword extraction, semantic similarity, and formatting compliance checks.
	- Built multi-portal scrapers (LinkedIn, Indeed) with deduplication, smart filtering, and anti-detection measures.
	- Developed an LLM-powered resume generation engine that creates unique, tailored PDFs for each job description.
	- Designed a plugin-based portal driver system for automated form filling, screening question answering, and CAPTCHA handling.

	[code](https://github.com/pctablet505/ats-optimizer)

	___

### Samsung R&D

4.	### Knox Capture

	Led the development of an innovative solution for scanning damaged barcodes on mobile devices, leveraging advanced synthetic dataset generation and cutting-edge computer vision techniques to overcome real-world challenges.

	- Pioneered a comprehensive barcode scanning system encompassing detection, segmentation, damage correction, and decoding of compromised barcodes.
	- Engineered a groundbreaking algorithm integrating mathematics, statistics, and geometric transformations to produce high-fidelity, photorealistic synthetic datasets, addressing the critical shortage of natural damaged barcode data.
	- Deployed YOLOv11 for precise barcode detection in complex environments.
	- Utilized Mask R-CNN for superior image segmentation, enabling accurate isolation of barcode regions.
	- Implemented a U-Net-based encoder-decoder architecture for intelligent damage correction and restoration.
	- Integrated a ResNet classifier for robust categorization of barcode types across diverse formats.
	- Orchestrated full end-to-end deployment: from algorithmic problem formulation and probabilistic dataset synthesis incorporating reflection physics, through rigorous deep learning model training for detection, segmentation, correction, and classification, culminating in optimized on-device Android implementation with hardware-accelerated camera integration and ultra-fast ML inference capabilities.
	- Introduced confidence score prediction for detections, allowing the system to intelligently assess barcode damage levels and abstain from restoration when damage exceeds recoverable thresholds, thereby drastically reducing incorrect decoding rates and enhancing overall system trustworthiness.

	*Private repository — code available on request.*

	___
5.	### SRIN-Satyapan

	Engineered a comprehensive anti-cheat proctored exam platform featuring advanced face recognition for secure candidate authentication and real-time face detection to flag potential plagiarism. Delivered a full-stack solution encompassing a web portal for examiners, a robust Android application for candidates, and a centralized server for seamless data management and AI-driven monitoring, ensuring integrity in remote assessments.

	- Real-time face recognition-based authentication for candidates.
	- Intelligent flagging of multiple persons or unauthorized individuals on screen, with safeguards to avoid false positives for random exam hall appearances.
	- Detection of unfair behaviors such as talking or suspicious activities during exams.
	- Comprehensive server-side exam portal including question uploading for examiners, result and registration portals for HRs, with question and option randomization to prevent copying.
	- Scalable system supporting over 10,000+ registered faces with successful recognition.
	- Auto-update features for Android apps to ensure seamless testing.
	- Kiosk mode implementation to prevent software tampering on managed devices.

	*Private repository — code available on request.*

	___
6.	### Face Recognition

	Developed an advanced real-time multiple face recognition system for live camera feeds and offline video processing. Originally built at Samsung R&D and later open-sourced.

	- Optimized database search efficiency from linear to logarithmic time complexity, achieving a dramatic reduction in search time from 1200ms to 87ms on Android tablets for face embedding searches.
	- Generated a custom dataset of face embeddings and trained a proprietary classifier on this dataset to enhance recognition accuracy and surpass limitations of standard methods.
	- Built integrated surveillance and entry management systems leveraging this technology for enhanced security and access control.
	- Provided recognition solutions for static photos, videos, and real-time camera feeds, compatible across Android, Windows, and Linux platforms.

	[code](https://github.com/pctablet505/cv_face)

	___
7.	### Distraction Detection

	Implemented an intelligent system to monitor user attention during screen-based activities, utilizing facial expression analysis, eye movement tracking, yawn detection, head pose estimation, and robust face detection algorithms to accurately identify distracted states and promote focused engagement. This solution was deployed on Android devices and integrated into SRI-N Satyapan for enhanced proctoring capabilities.

	*Private repository — code available on request.*

	___
8.	### Car Crash Detection

	Created a smartphone-based emergency response system to detect car crash incidents in real-time using onboard sensors, automatically triggering SOS alerts to designated contacts for rapid assistance and improved road safety.

	- Overcame the major challenge of insufficient accident sensor data by collecting comprehensive datasets from non-accident scenarios including rash driving, phone throwing, loud music, and movies.
	- Developed a statistical model to accurately flag potential accidents.
	- Implemented the solution on Android phones for seamless integration.

	*Private repository — code available on request.*

	___
9.	### Drop Detection

	Achieved a groundbreaking reduction in model parameters from millions to fewer than 20, maintaining high accuracy with only a minimal drop from 98% to 96%, enabling efficient on-device deployment.

	- Developed a sophisticated mobile solution for detecting phone drops, estimating fall height, classifying collision surface hardness, and verifying drop versus catch events through advanced sensor fusion and predictive analytics.
	- Replaced the existing deep learning-based solution with efficient statistical models and simple ML algorithms.
	- Significantly improved power consumption and computational efficiency.

	*Private repository — code available on request.*

	___

### Technical Depth

10.	### [Object Detection Tutorial](https://github.com/pctablet505/object-detection-tutorial)

	Educational notebook and synthetic dataset demonstrating object detection as a machine learning problem, covering bounding box regression, binary classification, and multi-class classification.

	- Created a synthetic shape dataset to visualize core object detection concepts.
	- Demonstrated bounding box regression as a coordinate prediction problem.
	- Implemented binary classification to determine object presence in predicted regions.
	- Built multi-class classification to identify specific object types within detected regions.

	[code](https://github.com/pctablet505/object-detection-tutorial)

	___
11.	### [Shadow Removal](https://github.com/pctablet505/Shadow-Removal)

	Computer vision project implementing iterative shading and reflectance estimation for automatic shadow removal in images.

	- Implemented adaptive thresholding using integral images for fast local region analysis.
	- Developed iterative shading and reflectance decomposition to isolate and remove shadows.
	- Utilized OpenCV and NumPy for efficient image processing pipelines.

	[code](https://github.com/pctablet505/Shadow-Removal)

	___
12.	### [Data Structures & Algorithms](https://github.com/pctablet505/Data-Structures)

	Comprehensive Python implementations of advanced data structures and algorithms from CLRS and competitive programming.

	- Implemented van Emde Boas Tree with both O(u) and O(n log log u) space optimizations.
	- Built Red-Black Trees, AVL Trees, Splay Trees, and Treaps with full balancing logic.
	- Developed Segment Trees, Binary Indexed Trees, and Sparse Tables for range queries.
	- Implemented Skip Lists, Disjoint Sets, and implicit treaps.
	- All implementations are from scratch with detailed comments and complexity analysis.

	[code](https://github.com/pctablet505/Data-Structures)

	___
13.	### [Academic Foundations](https://github.com/pctablet505/Artificial-Intelligence)

	A collection of foundational machine learning, artificial intelligence, and web development projects from coursework at MIT, Harvard (CS50), and UC Berkeley (CS188).

	- **MIT Machine Learning**: Sentiment analysis perceptron, SVM MNIST digit recognition, overlapping digit CNN, Netflix collaborative filtering with Gaussian Mixtures, Q-learning text game agent. ([code](https://github.com/pctablet505/Machine-Learning))
	- **Harvard CS50 AI**: Maze solver (search algorithms), [Degrees](https://cs50.harvard.edu/ai/2020/projects/0/degrees/) (BFS), [Tic-Tac-Toe AI](https://www.youtube.com/watch?v=tp9DjqV_KoU) (Minimax), [Minesweeper AI](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/) (propositional logic), [Crossword CSP solver](https://cs50.harvard.edu/ai/2020/projects/3/crossword/), probabilistic reasoning (PageRank, Bayes nets), Shopping (KNN), NIM (RL), [Traffic Sign CNN](https://cs50.harvard.edu/ai/2020/projects/5/traffic/). ([code](https://github.com/pctablet505/Artificial-Intelligence))
	- **UC Berkeley CS188 AI**: [PacMan AI](https://inst.eecs.berkeley.edu/~cs188/sp21/project1/) with A* search, heuristics, and reinforcement learning. ([code](https://github.com/pctablet505/CS188-AI))
	- **CS50 Web**: [Wiki](https://github.com/pctablet505/Wiki) (Django Wikipedia clone), [Finance](https://github.com/pctablet505/CS50-Finance) (Flask stock trading app).

	___
14.	### [HomePage](https://pctablet505.github.io/)

	Personal portfolio homepage containing details about hobbies, interests, and projects. Built using Flask, HTML, CSS, JavaScript.

	[code](https://github.com/pctablet505/pctablet505.github.io)

	___

---

## Education

- ### [MITx](https://micromasters.mit.edu/)
	**[MicroMasters in Statistics and Data Science](https://micromasters.mit.edu/ds/)**

	📅 2021 – 2023

	---
- ### [BIT Sindri](https://www.bitsindri.ac.in/)
	**[B.Tech Computer Science](https://www.bitsindri.ac.in/index.php/departments/computer-science-engineering)**

	📅 2018 – 2022

	---

## Skills

- **Programming Languages**: Python, C, C++, Java, Kotlin, JavaScript, Starlark
- **Deep Learning Frameworks**: Keras, TensorFlow, PyTorch, JAX, LiteRT, TFLite, ONNX, OpenVINO
- **Machine Learning**: Regression, Classification, Clustering, Recommendation, Collaborative Filtering, Reinforcement Learning, Generative AI, Model Quantization, Model Pruning
- **Computer Vision**: Object Detection, Image Segmentation, Face Recognition, Synthetic Dataset Generation, Geometric Transformations, Shadow Removal, YOLO, Mask R-CNN, U-Net
- **Edge AI & On-Device ML**: LiteRT Export, TFLite Conversion, DSP Optimization, Android NNAPI, GPU Delegation, NPU Inference, Model Compression, Post-Training Quantization
- **Data Analysis and Statistics**: Advanced Data Structures, Algorithms, Probabilistic Modeling, Inference, Estimation, Hypothesis Testing, Prediction, Data Analysis
- **Tools and Libraries**: NumPy, OpenCV, Scikit-Learn, Pandas, Seaborn, Matplotlib, Playwright, Selenium, Docker, CI/CD
- **Android Development**: Java, Kotlin, Jetpack Compose, ML model porting, Services, Fragments, Rest APIs, Sensor Access, Camera2 API
- **Web Development**: Flask, Django, HTML, SASS, CSS, Bootstrap, SQL, MVC, Git
- **IoT**: Arduino, Sensors, Wireless Control

---

## Achievements

- **MD Appreciation Award** — Honoured with MD Appreciation award by honourable MD at Samsung Research, Noida, for developing SRI-N Satyapan.
- **Implemented van Emde Boas Tree** — [1st time correct implementation in python in the History](https://github.com/pctablet505/van-Emde-Boas-Tree)
- **World Programming Championship - IIT Mumbai** — Rank 69 | Certificate no 99695
- **Gold in HackFest 2020** — [Rank 29 | 8051 Rating 2042.08 from 1500](https://www.hackerrank.com/results/hackerrank-hackfest-2020/stopslavery404)
- **GATE 2021** — [Got AIR 5648](/static/gate2021.png)
- **CodeVita Season 9** — Cleared Round 1 with Rank 1042 | Got International 242 in Round 2
- **CodeVita Season 10** — Got International 426 in Round 1
- **Hack the Interview III** — [Rank(73 | 919)](https://www.hackerrank.com/results/hack-the-interview-iv/stopslavery404)
- **Hack the Interview IV (Asia Pacific)** — [Rank(100 | 4353)](https://www.hackerrank.com/results/hack-the-interview-iv-apac/stopslavery404)
- **Hack the Interview IV (U.S.)** — [Rank( 65 | 1217)](https://www.hackerrank.com/results/hack-the-interview-iv/stopslavery404?h_r=profile)
- **Hackerrank Algorithms** — [Rank 1026 / 2219538](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=algorithms&type=practice)
- **Hackerrank Data Structures** — [Rank 540 | 931788](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=data-structures&type=practice)
- **Hackerrank Python Practice** — [Rank 1](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=python&type=practice)

---

## Certifications

|||||
|:----:|:----:|:----:|:----:|
|[MIT MicroMasters in Statistics and Data Science](https://credentials.edx.org/credentials/df346be2b21745ca9ad5195d4f264360/) <img src="homepage/certificates/MITx MicroMasters in Statistics and Data Science.png" width=200 height=160 >|[MIT Data Analysis: Statistical Modelling and Computation in Application](https://courses.edx.org/certificates/bf4ea7cb34a742cea00c770801d1947d) <img src="homepage/certificates/MITx 6.419x.png" width=200 height=160 >|[MIT Fundamentals of Statistics](https://courses.edx.org/certificates/3c59035943454549990f2d2de7f49e9f) <img src="homepage/certificates/MITx 18.6501x Fundamentals of statistics.png" width=200 height=160 >|[MIT Probability - The Science of Uncertainity](https://courses.edx.org/certificates/45213294fe2649c5a5954e4c42a70f13) <img src="homepage/certificates/MIT 6.431x.png" width=200 height=160 >|
|[MIT Machine Learning with Python-From Linear Models to Deep Learning](https://courses.edx.org/certificates/8cbde197f6874661ab8794d753f9fd7b) <img src="homepage/certificates/MIT 6.86x.jpg" width=200 height=160 >|[CS50 Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/certificates/2b1773c1-473d-4a7b-89ae-460d23154126) <img src="homepage/certificates/CS50 AI.png" width=200 height=160 >|[IBM Introductioin to AI](https://www.coursera.org/account/accomplishments/certificate/UA73U5EJC6XJ) <img src="homepage/certificates/IBM Introductioin to AI.png" width=200 height=160 >|[IBM Python for Data Science, AI & Development](https://www.coursera.org/account/accomplishments/verify/YSE63GF4U76Q) <img src="homepage/certificates/IBM Python.PNG" width=200 height=160 >|
|[Udemy Complete 2020 Data Science & Machine Learning Bootcamp](http://ude.my/UC-d7c52c49-464f-4b63-a9b4-2da5d4c53ff4/) <img src="homepage/certificates/Machine Learning.jpg" width=200 height=160 >|[C Advanced](https://www.hackerrank.com/certificates/58d066424a1e) <img src="homepage/certificates/C Advanced.png" width=200 height=160 >|[C Basic](https://www.hackerrank.com/certificates/0c61249bbe1d) <img src="homepage/certificates/C Basic.png" width=200 height=160 >|[C Intermediate](https://www.hackerrank.com/certificates/337182b9dc84) <img src="homepage/certificates/C Intermediate.png" width=200 height=160 >|
|[CSS](https://www.hackerrank.com/certificates/92d056e955d2) <img src="homepage/certificates/CSS.png" width=200 height=160 >|[Java](https://www.hackerrank.com/certificates/253bacd0f0c0) <img src="homepage/certificates/Java.png" width=200 height=160 >|[Kaggle Intermediate Machine Learning](https://www.kaggle.com/learn/certification/pctablet505/intermediate-machine-learning) <img src="homepage/certificates/Kaggle - Intermediate Machine Learning.png" width=200 height=160 >|[Kaggle Intro to Deep Learning](https://www.kaggle.com/learn/certification/pctablet505/intro-to-deep-learning) <img src="homepage/certificates/Kaggle - Intro to Deep Learning.png" width=200 height=160 >|
|[Kaggle Intro to Machine Learning](https://www.kaggle.com/learn/certification/pctablet505/intro-to-machine-learning) <img src="homepage/certificates/Kaggle - Intro to Machine Learning.png" width=200 height=160 >|[Kaggle Python](https://www.kaggle.com/learn/certification/pctablet505/python) <img src="homepage/certificates/Kaggle - Python.png" width=200 height=160 >|[Problem Solving Advanced](https://www.hackerrank.com/certificates/fc7b9af8aac8) <img src="homepage/certificates/problem Solving Advanced.png" width=200 height=160 >|[Problem Solving Basic](https://www.hackerrank.com/certificates/e3c6568f71c6) <img src="homepage/certificates/Problem Solving Basic.png" width=200 height=160 >|
|[Problem Solving Intermediate](https://www.hackerrank.com/certificates/f5bcd6aa9355) <img src="homepage/certificates/Problem Solving Intermediate.png" width=200 height=160 >|[Python Advanced](https://www.hackerrank.com/certificates/6e9c190da189) <img src="homepage/certificates/Python Advanced.png" width=200 height=160 >|[Python Basic](https://www.hackerrank.com/certificates/93d10484c124) <img src="homepage/certificates/Python Basic.png" width=200 height=160 >|[Python Intermediate](https://www.hackerrank.com/certificates/9ecfb2a355a2) <img src="homepage/certificates/Python Intermediate.png" width=200 height=160 >|
|[SQL Basic](https://www.hackerrank.com/certificates/2508bf1f2b12) <img src="homepage/certificates/SQL Basic.png" width=200 height=160 >|[SQL Intermediate](https://www.hackerrank.com/certificates/74490a9fe364) <img src="homepage/certificates/SQL Intermediate.png" width=200 height=160 >|[Udemy Data Structures and Algorithms](https://www.udemy.com/certificate/UC-37c2faaf-17c4-4089-ab2d-18190a8aa61f/) <img src="homepage/certificates/DSA.jpg" width=200 height=160 >|[Udemy Python](https://www.kaggle.com/learn/certification/pctablet505/intermediate-machine-learning) <img src="homepage/certificates/Python.jpg" width=200 height=160 >|
|[SSCP Cert Prep: 5 Cryptography](https://www.linkedin.com/learning/certificates/ce217421b25f5ed3a79b285747e63908813fae27bd68729b6dd7dac38d27a0ad) <img src="homepage/certificates/SSCP Cert Prep- 5 Cryptography.png" width=200 height=160 >|

---

## Contact

- **Phone** [+91-8709253658](tel:+91-8709253658)
- **Mail** [work.rahul126@gmail.com](mailto:work.rahul126@gmail.com)
- **LinkedIn** [@rahul126](https://www.linkedin.com/in/rahul126)
- **Website** [https://github.com/pctablet505/portfolio](https://github.com/pctablet505/portfolio)
- **Hackerrank** [@stopslavery404](https://www.hackerrank.com/stopslavery404)
- **GitHub** [@pctablet505](https://www.github.com/pctablet505)
- **Instagram** [@hellorahul.me](https://www.instagram.com/hellorahul.me)
- **Youtube** [YouTube](https://www.youtube.com/channel/UCnRPtPB_CXs1ngGlwKqP-yw)

---
