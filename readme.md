# RAHUL KUMAR

## Summary

Software Engineer (Machine Learning) at Google, working with the Keras team on deep learning frameworks, LiteRT export, and cross-backend model portability. Previously built end-to-end on-device AI solutions at Samsung R&D and Qualcomm, spanning computer vision, sensor fusion, and generative AI. Passionate about reinforcement learning, algorithmic trading, edge AI deployment, and open-source ML infrastructure.

---

## Experience

- ### [Google](https://www.google.com/)
	**Software Engineer (Machine Learning)**

	Working with Keras Team on deep learning framework development, LiteRT model export, and cross-backend portability (TensorFlow, PyTorch, JAX). Contributing to production-grade ML infrastructure used by millions of developers.

	📅 Feb 2025-Present

	🗺 Hyderabad, India

	---
- ### [Qualcomm](https://www.qualcomm.com/)
	**Machine Learning Engineer**

	Worked with on-device AI implementation, DSP optimized solutions, and android demo for SOTA computer vision applications.

	📅 Sept 2024-Jan 2025

	🗺 Hyderabad, India

	---
- ### [Samsung R&D Institute India](https://research.samsung.com/sri-n)
	**Research & Development Engineer**

	Worked with different AI problems, mostly with computer vision and sensor data. Developed end-to-end solutions, include complete android app, web server and on-device AI.

	📅 July 2022-Sept 2024

	🗺 Noida, India

	---
- ### [Samsung R&D Institute India](https://research.samsung.com/sri-n)
	**Intern**

	Worked with Android Studio, learnt generative AI using Cycle GAN, training for SWC.

	📅 Jan 2022-June 2022

	🗺 Noida, India

	---


---

## Education

- ### [MITx](https://micromasters.mit.edu/)

	**[MicroMasters in Statistics and Data Science](https://micromasters.mit.edu/ds/)**

	📅 2021-23

	---
- ### [BIT Sindri](https://www.bitsindri.ac.in/)

	**[B.Tech Computer Science](https://www.bitsindri.ac.in/index.php/departments/computer-science-engineering)**

	📅 2018-22

	---
- ### [Guru Gobind Singh Public School](https://www.ggpsbokaro.org/)

	**[Higher Secondary Education]()**

	📅 2015-17

	---
- ### [ARS Public School](http://www.arspublicschool.com/)

	**[High School]()**

	📅 2008-15

	---
- ### [Sharswati Sishu Vidya Mandir]()

	**[Elementary School]()**

	📅 2005-08

	---


---

## Projects

1.	### [Keras & LiteRT Ecosystem](https://keras.io/guides/)

	Active contributor to the Keras ecosystem at Google. Driving LiteRT (TensorFlow Lite Runtime) export capabilities, cross-backend model portability, and production-grade deep learning infrastructure.
	- Implemented LiteRT export support for the PyTorch backend in Keras 3, enabling seamless on-device deployment of PyTorch-trained models.
	- Fixed critical bugs in the Attention layer (N-D input support) and custom model weight serialization with nested sublayers.
	- Authored the official Keras.io guide for exporting models to LiteRT, covering TensorFlow and PyTorch backends with end-to-end examples.
	- Contributed to keras-hub pretrained model hub and LiteRT-Torch converter integration for broader CPU/GPU/NPU on-device coverage.
	- Backported SavedModel export workarounds and resolved compatibility issues across Keras 3, TF 2.20, and Python 3.13.

	[code](https://github.com/pctablet505/keras)

	___
2.	### [Algorithmic Trading (RL Alpha Labs)](https://pctablet505.github.io/RLAlphaLabs/)

	Leading the development of an AI-driven trading platform tailored for the Indian stock market, integrating advanced reinforcement learning and heuristic strategies for optimized portfolio management.
	- Leveraged Kite-Connect API from Zerodha to build a robust historical data downloader, efficiently retrieving and storing comprehensive market data for stocks, ETFs, and other instruments in a high-performance database.
	- Designed a custom user interface for seamless portfolio management, real-time paper trading, and algorithm-based automated execution.
	- Engineered heuristic algorithms driven by technical signals for accurate trade simulation and backtesting.
	- Created a versatile trading environment supporting heuristic, strategy-based, and reinforcement learning agents, with full portfolio management simulation.
	- Implemented advanced risk management and loss tolerance systems to ensure agent stability and compliance.
	- Developing a sophisticated reinforcement learning agent with shared learnable parameters to trade across diverse entities, including multiple stocks, markets, brokers, cryptocurrencies, equities, and commodities.

	[code](https://github.com/pctablet505/AlgoTrading)

	___
3.	### Gemma TFLite Android Demo

	Minimal Android application demonstrating on-device inference of the Gemma 3 270M IT large language model via TensorFlow Lite / LiteRT, showcasing edge AI deployment for generative AI.
	- Built a production-ready Android app in Kotlin for running Gemma 3 270M IT on ARM64 devices with API 31+.
	- Integrated model export pipeline from Hugging Face to TFLite format using Keras backend.
	- Implemented hardware-accelerated inference with optimized memory footprint for mobile deployment.
	- Provided end-to-end documentation covering model export, Android SDK setup, build automation, and device deployment.

	[code](https://github.com/pctablet505/gemma-tflite-android-demo)

	___
4.	### ATS Optimizer

	A fully-automated job application pipeline that eliminates every manual step between discovering a job and submitting an application. Built for candidates applying to 50+ jobs per day.
	- Architected a modular system with five core engines: Candidate Profile, ATS Analysis, Job Discovery, Resume Generation, and Application Automation.
	- Implemented ATS scoring algorithm using NLP keyword extraction, semantic similarity, and formatting compliance checks.
	- Built multi-portal scrapers (LinkedIn, Indeed) with deduplication, smart filtering, and anti-detection measures.
	- Developed an LLM-powered resume generation engine that creates unique, tailored PDFs for each job description.
	- Designed a plugin-based portal driver system for automated form filling, screening question answering, and CAPTCHA handling.

	[code](https://github.com/pctablet505/ats-optimizer)

	___
5.	### Knox Capture

	Led the development of an innovative solution for scanning damaged barcodes on mobile devices, leveraging advanced synthetic dataset generation and cutting-edge computer vision techniques to overcome real-world challenges.
	- Pioneered a comprehensive barcode scanning system encompassing detection, segmentation, damage correction, and decoding of compromised barcodes.
	- Engineered a groundbreaking algorithm integrating mathematics, statistics, and geometric transformations to produce high-fidelity, photorealistic synthetic datasets, addressing the critical shortage of natural damaged barcode data.
	- Deployed YOLOv11 for precise barcode detection in complex environments.
	- Utilized Mask R-CNN for superior image segmentation, enabling accurate isolation of barcode regions.
	- Implemented a U-Net-based encoder-decoder architecture for intelligent damage correction and restoration.
	- Integrated a ResNet classifier for robust categorization of barcode types across diverse formats.
	- Orchestrated full end-to-end deployment: from algorithmic problem formulation and probabilistic dataset synthesis incorporating reflection physics, through rigorous deep learning model training for detection, segmentation, correction, and classification, culminating in optimized on-device Android implementation with hardware-accelerated camera integration and ultra-fast ML inference capabilities.
	- Addressed limitations of the Muenster Barcode Database, which lacks sufficient damaged barcode samples for robust training, by creating a synthetic dataset that enabled superior model performance.
	- Benchmarking revealed that existing solutions achieved approximately 84% detection accuracy and 67% correct decoding on damaged barcodes; our innovative approach elevated these metrics to 70-75% for both detection and decoding, representing a significant leap in reliability.
	- Introduced confidence score prediction for detections, allowing the system to intelligently assess barcode damage levels and abstain from restoration when damage exceeds recoverable thresholds, thereby drastically reducing incorrect decoding rates and enhancing overall system trustworthiness.

	___
6.	### SRIN-Satyapan

	Engineered a comprehensive anti-cheat proctored exam platform featuring advanced face recognition for secure candidate authentication and real-time face detection to flag potential plagiarism. Delivered a full-stack solution encompassing a web portal for examiners, a robust Android application for candidates, and a centralized server for seamless data management and AI-driven monitoring, ensuring integrity in remote assessments.
	- Real-time face recognition-based authentication for candidates.
	- Intelligent flagging of multiple persons or unauthorized individuals on screen, with safeguards to avoid false positives for random exam hall appearances.
	- Detection of unfair behaviors such as talking or suspicious activities during exams.
	- Comprehensive server-side exam portal including question uploading for examiners, result and registration portals for HRs, with question and option randomization to prevent copying.
	- Scalable system supporting over 10,000+ registered faces with successful recognition.
	- Auto-update features for Android apps to ensure seamless testing.
	- Kiosk mode implementation to prevent software tampering on managed devices.

	___
7.	### Face Recognition

	Developed an advanced real-time multiple face recognition system for live camera feeds and offline video processing.
	- Developed an advanced real-time multiple face recognition system for live camera feeds and offline video processing.
	- Optimized database search efficiency from linear to logarithmic time complexity, achieving a dramatic reduction in search time from 1200ms to 87ms on Android tablets for face embedding searches.
	- Generated a custom dataset of face embeddings and trained a proprietary classifier on this dataset to enhance recognition accuracy and surpass limitations of standard methods.
	- Built integrated surveillance and entry management systems leveraging this technology for enhanced security and access control.
	- Provided recognition solutions for static photos, videos, and real-time camera feeds, compatible across Android, Windows, and Linux platforms.

	[code](https://github.com/pctablet505/cv_face)

	___
8.	### Distraction Detection

	Implemented an intelligent system to monitor user attention during screen-based activities, utilizing facial expression analysis, eye movement tracking, yawn detection, head pose estimation, and robust face detection algorithms to accurately identify distracted states and promote focused engagement. This solution was deployed on Android devices and integrated into SRI-N Satyapan for enhanced proctoring capabilities.

	___
9.	### Car Crash Detection

	Created a smartphone-based emergency response system to detect car crash incidents in real-time using onboard sensors, automatically triggering SOS alerts to designated contacts for rapid assistance and improved road safety.
	- Created a smartphone-based emergency response system to detect car crash incidents in real-time using onboard sensors, automatically triggering SOS alerts to designated contacts for rapid assistance and improved road safety.
	- Overcame the major challenge of insufficient accident sensor data by collecting comprehensive datasets from non-accident scenarios including rash driving, phone throwing, loud music, and movies.
	- Developed a statistical model to accurately flag potential accidents.
	- Implemented the solution on Android phones for seamless integration.

	___
10.	### Drop Detection

	Achieved a groundbreaking reduction in model parameters from millions to fewer than 20, maintaining high accuracy with only a minimal drop from 98% to 96%, enabling efficient on-device deployment.
	- Achieved a groundbreaking reduction in model parameters from millions to fewer than 20, maintaining high accuracy with only a minimal drop from 98% to 96%, enabling efficient on-device deployment.
	- Developed a sophisticated mobile solution for detecting phone drops, estimating fall height, classifying collision surface hardness, and verifying drop versus catch events through advanced sensor fusion and predictive analytics.
	- Replaced the existing deep learning-based solution with efficient statistical models and simple ML algorithms.
	- Significantly improved power consumption and computational efficiency.

	___
11.	### Object Detection Tutorial

	Educational notebook and synthetic dataset demonstrating object detection as a machine learning problem, covering bounding box regression, binary classification, and multi-class classification.
	- Created a synthetic shape dataset to visualize core object detection concepts.
	- Demonstrated bounding box regression as a coordinate prediction problem.
	- Implemented binary classification to determine object presence in predicted regions.
	- Built multi-class classification to identify specific object types within detected regions.

	[code](https://github.com/pctablet505/object-detection-tutorial)

	___
12.	### Shadow Removal

	Computer vision project implementing iterative shading and reflectance estimation for automatic shadow removal in images.
	- Implemented adaptive thresholding using integral images for fast local region analysis.
	- Developed iterative shading and reflectance decomposition to isolate and remove shadows.
	- Utilized OpenCV and NumPy for efficient image processing pipelines.

	[code](https://github.com/pctablet505/Shadow-Removal)

	___
13.	### Data Structures & Algorithms

	Comprehensive Python implementations of advanced data structures and algorithms from CLRS and competitive programming.
	- Implemented van Emde Boas Tree with both O(u) and O(n log log u) space optimizations.
	- Built Red-Black Trees, AVL Trees, Splay Trees, and Treaps with full balancing logic.
	- Developed Segment Trees, Binary Indexed Trees, and Sparse Tables for range queries.
	- Implemented Skip Lists, Disjoint Sets, and implicit treaps.
	- All implementations are from scratch with detailed comments and complexity analysis.

	[code](https://github.com/pctablet505/Data-Structures)

	___
14.	### [PacMan AI](https://inst.eecs.berkeley.edu/~cs188/sp21/project1/)

	AI-based intelligent agent to control Pacman in different environments. The Pacman plays against the ghosts and tries to eat all food while staying safe from ghosts and finishing in minimum time. The Pacman uses different methods like A* Search, Heuristics, Reinforcement Learning with different parameters.

	[code](https://github.com/pctablet505/CS188-AI/tree/main/proj1-search-python3)

	___
15.	### Automatic Review Analyzer

	Sentiment analysis for customer reviews using a simple perceptron algorithm.

	[code](https://github.com/pctablet505/Machine-Learning/tree/main/Project1/sentiment_analysis)

	___
16.	### MNIST Digit Recognition

	Classification of digits using support vector machine and gradient descent.

	[code](https://github.com/pctablet505/Machine-Learning/tree/main/Project2/mnist/part1)

	___
17.	### Overlapping Digit Recognition

	Classification of overlapping digits which contain multiple digits in a single image, where a digit is written over another digit, using Convolutional Neural Networks.

	[code](https://github.com/pctablet505/Machine-Learning/tree/main/Project2/mnist/part2-twodigit)

	___
18.	### Collaborative Filtering via Gaussian Mixtures

	Recommender system for Netflix using Gaussian Mixtures models and EM algorithm. Ratings of few users for different movies are provided as input and ratings for movies which the user has not rated are calculated. It achieves very nice accuracy.

	[code](https://github.com/pctablet505/Machine-Learning/tree/main/project4/resources_netflix/netflix)

	___
19.	### Text game using Reinforcement Learning

	It is a game in which a robot is given tasks in a room and learns to play it. Implementations using Q learning, Q learning with approximations, using neural networks to reduce the exponential size Q Tables.

	[code](https://github.com/pctablet505/Machine-Learning/tree/main/project5/rl)

	___
20.	### Maze Solver

	Demonstration of complexity, speed, effectiveness of different search algorithms.

	[code](https://github.com/pctablet505/Artificial-Intelligence)

	___
21.	### [Degrees](https://cs50.harvard.edu/ai/2020/projects/0/degrees/)

	Calculation of minimum degree of separation between actors in Hollywood. Separation is in terms of working together.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/degrees)

	___
22.	### [Tic-Tac-Toe AI](https://www.youtube.com/watch?v=tp9DjqV_KoU)

	Minimax and Alpha-Beta pruning based undefeatable intelligent agent to play against human.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/tictactoe)

	___
23.	### [Minesweeper AI](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/)

	Knowledge-based intelligent agent to play Minesweeper which reasons using propositional logic.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/minesweeper)

	___
24.	### [CSP solver for Crossword Puzzle](https://cs50.harvard.edu/ai/2020/projects/3/crossword/)

	Solves crossword puzzles by modeling it into a Constraint Satisfaction Problem and then using backtracking search with different heuristics to improve performance.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/crossword)

	___
25.	### [Probabilistic models for reasoning under uncertainty](https://cs50.harvard.edu/ai/2020/projects/2/)

	To demonstrate page ranking and gene inheritance, by sampling and using bayes-net.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/probabilistic%20models)

	___
26.	### [Shopping](https://cs50.harvard.edu/ai/2020/projects/4/shopping/)

	K Nearest Neighbour model to predict whether a customer will make the purchase or not.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/shopping)

	___
27.	### [NIM](https://cs50.harvard.edu/ai/2020/projects/4/nim/)

	Playing NIM against human. Trained using reinforcement learning.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/nim)

	___
28.	### [Traffic Sign classification](https://cs50.harvard.edu/ai/2020/projects/5/traffic/)

	CNN model for 43 class classification of traffic sign boards.

	[code](https://github.com/pctablet505/Artificial-Intelligence/tree/main/traffic)

	___
29.	### CS50 Wiki

	Mini version of Wikipedia with almost all features of Wikipedia. Built using Django, HTML, Jinja, CSS, SASS.

	[code](https://github.com/pctablet505/Wiki)

	___
30.	### [HomePage](https://pctablet505.github.io/)

	Personal portfolio homepage containing details about hobbies, interests, and projects. Built using Flask, HTML, CSS, JavaScript.

	[code](https://github.com/pctablet505/pctablet505.github.io)

	___
31.	### CS50-Finance

	A lite app to get quotes of stocks and to perform buy, sell stocks. Technologies used: Flask, SQL, APIs, JSON, Heroku, GIT.

	[code](https://github.com/pctablet505/CS50-Finance)

	___


---

## Skills

- **Programming Languages**: Python, C, C++, Java, Kotlin, JavaScript
- **Deep Learning Frameworks**: Keras, TensorFlow, PyTorch, JAX, LiteRT, TFLite
- **Machine Learning**: Regression, Classification, Clustering, Recommendation, Collaborative Filtering, Reinforcement Learning, Generative AI
- **Computer Vision**: Object Detection, Image Segmentation, Face Recognition, Synthetic Dataset Generation, Geometric Transformations, Shadow Removal
- **Edge AI & On-Device ML**: Model Quantization, LiteRT Export, DSP Optimization, Android NNAPI, GPU Delegation, NPU Inference
- **Data Analysis and Statistics**: Advanced Data Structures, Algorithms, Probabilistic Modeling, Inference, Estimation, Hypothesis Testing, Prediction, Data Analysis
- **Tools and Libraries**: NumPy, OpenCV, Scikit-Learn, Pandas, Seaborn, Matplotlib, Playwright, Selenium
- **Android Development**: Java, Kotlin, ML model porting, Services, Fragments, Rest APIs, Sensor Access, Camera2 API
- **Web Development**: Flask, Django, HTML, SASS, CSS, Bootstrap, SQL, MVC, Git
- **IOT**: Arduino, Sensors, Wireless Control


---

## Achievements

- **MD Appreciation Award** [Honoured with MD Appreciation award by honourable MD at Samsung Research, Noida, for developing SRI-N Satyapan.]()
- **Implemented van Emde Boas Tree** [1st time correct implementation in python in the History](https://github.com/pctablet505/van-Emde-Boas-Tree)
- **World Programming Championship - IIT Mumbai** [Rank 69 | Certificate no 99695]()
- **Gold in HackFest 2020** [Rank 29 | 8051  Rating 2042.08 from 1500](https://www.hackerrank.com/results/hackerrank-hackfest-2020/stopslavery404)
- **GATE 2021** [Got AIR 5648](/static/gate2021.png)
- **CodeVita Season 9** [Cleared Round 1 with Rank 1042]()
- **CodeVita Season 9** [Got International 242 in Round 2]()
- **CodeVita Season 10** [Got International 426 in Round 1]()
- **Hack the Interview III** [Rank(73 | 919)](https://www.hackerrank.com/results/hack-the-interview-iv/stopslavery404)
- **Hack the Interview IV (Asia Pacific)** [Rank(100 | 4353)](https://www.hackerrank.com/results/hack-the-interview-iv-apac/stopslavery404)
- **Hack the Interview IV (U.S.) ** [Rank( 65 | 1217) ](https://www.hackerrank.com/results/hack-the-interview-iv/stopslavery404?h_r=profile)
- **Hackerrank Algorithms** [Rank 1026/ 2219538](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=algorithms&type=practice)
- **Hackerrank Data Structures ** [Rank 540| 931788](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=data-structures&type=practice)
- **Hackerrank Python Practice** [Rank 1](https://www.hackerrank.com/leaderboard?filter=stopslavery404&filter_on=hacker&page=1&track=python&type=practice)


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
|[SQL Basic](https://www.hackerrank.com/certificates/2508bf1f2b12) <img src="homepage/certificates/SQL Basic.png" width=200 height=160 >|[SQL Intermediate](https://www.hackerrank.com/certificates/74470a9fe364) <img src="homepage/certificates/SQL Intermediate.png" width=200 height=160 >|[Udemy Data Structures and Algorithms](https://www.udemy.com/certificate/UC-37c2faaf-17c4-4089-ab2d-18190a8aa61f/) <img src="homepage/certificates/DSA.jpg" width=200 height=160 >|[Udemy Python](https://www.kaggle.com/learn/certification/pctablet505/intermediate-machine-learning) <img src="homepage/certificates/Python.jpg" width=200 height=160 >|
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

