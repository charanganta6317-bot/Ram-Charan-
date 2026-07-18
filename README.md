<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8A2BE2,4B0082,9400D3,6A5ACD&height=200&section=header&text=Engineering%20The%20Future&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Enterprise%20Software%20&%20AI%20Specialist&descAlignY=55&descAlign=50" width="100%" alt="Header Banner" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=9370DB&center=true&vCenter=true&width=600&lines=Senior+Software+Engineer;AI+%2F+ML+Product+Engineer;Enterprise+Full+Stack+Architect;Open+Source+Contributor" alt="Typing SVG" />
  
  <br />

  <img src="https://img.shields.io/badge/M.S.%20Computer%20Science-4B0082?style=for-the-badge&logo=proquest&logoColor=white" alt="Academic Badge" />
  <img src="https://img.shields.io/badge/Location-Kakinada,%20AP,%20India-8A2BE2?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location Badge" />

  <br />
  <br />

  <a href="https://my-3-d-portfolio-bay.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=dev.to&logoColor=9370DB&borderColor=8A2BE2" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ram-charan-b4a8b4388"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=9370DB&borderColor=8A2BE2" alt="LinkedIn" /></a>
  <a href="mailto:charan.ganta.6317@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=minutemailer&logoColor=9370DB&borderColor=8A2BE2" alt="Email" /></a>
  <a href="#"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=9370DB&borderColor=8A2BE2" alt="GitHub" /></a>

  <br />
  <br />

  <img src="https://komarev.com/ghpvc/?username=github&color=4B0082&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/github?style=for-the-badge&color=8A2BE2&logo=github" alt="Followers" />
  <img src="https://img.shields.io/github/stars/github?style=for-the-badge&color=9400D3&logo=github" alt="Stars" />
</div>

<br />

---

## ✦ About

I am a **Senior Software Engineer** and **AI/ML Specialist** dedicated to architecting scalable, enterprise-grade distributed systems. With a robust background in advanced computer science principles, I bridge the gap between theoretical machine learning and production-ready software engineering. 

My approach is rooted in a **product engineering mindset**—I do not just write code; I build resilient solutions that drive measurable business impact. I specialize in full-stack development with a heavy emphasis on cloud-native architectures, high-performance computing, and integrating large language models into highly available user-facing applications. 

**Open To:**
*   Senior/Lead Software Engineering roles at product-driven organizations.
*   AI/ML Architect positions focusing on LLM integrations and MLOps.
*   Open-source collaborations in Rust, Python, and Go ecosystems.
*   Technical speaking engagements and mentorship opportunities.

---

## ✦ Tech Stack

<div align="center">
  <br />
  <p><b>Languages</b></p>
  <img src="https://skillicons.dev/icons?i=html,css,js&theme=dark" alt="Languages" />
  <br /><br />
  <p><b>Frameworks</b></p>
  <img src="https://skillicons.dev/icons?i=react,nextjs&theme=dark" alt="Frameworks" />
  <br /><br />
  <p><b>Databases</b></p>
  <img src="https://skillicons.dev/icons?i=firebase,supabase&theme=dark" alt="Databases" />
  <br /><br />
  <p><b>Cloud, DevOps & Tooling</b></p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,linux,githubactions,nginx&theme=dark" alt="Cloud and DevOps" />
</div>
<br />

---

## ✦ AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **Large Language Models (LLMs)** | Advanced | RAG, Fine-tuning (LoRA/QLoRA), Prompt Engineering, LangChain, LlamaIndex |
| **Computer Vision** | Advanced | Object Detection (YOLO, Faster R-CNN), Image Segmentation, OpenCV, PyTorch |
| **Natural Language Processing** | Advanced | Transformer architectures, BERT, Sentiment Analysis, Named Entity Recognition |
| **MLOps & Deployment** | Intermediate | Model serving (Triton, TorchServe), MLflow, ONNX runtime, TensorRT optimization |
| **Data Engineering** | Intermediate | Distributed data processing, Apache Spark, Feature Engineering pipelines |

---

## ✦ Featured Projects

<details>
<summary><b>1. NexusAI : Enterprise RAG Pipeline Architecture</b></summary>
<br />
An asynchronous, high-throughput Retrieval-Augmented Generation (RAG) microservice designed for processing secure, internal enterprise documents with strict access controls. 

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Python, FastAPI, Milvus, Redis | 100k+ Docs/day | < 400ms TTFT | SOC2 Compliant, TLS 1.3 | Reduced support ticket volume by 45% | [View Source](#) |

**Professional Overview:**
Architected the ingestion and query pipelines leveraging state-of-the-art embedding models. Implemented advanced vector search mechanisms combined with hybrid sparse/dense retrieval, ensuring high precision in domain-specific contexts. The system was dockerized and orchestrated via Kubernetes to dynamically scale GPU nodes based on inference load, drastically reducing operational overhead.
<br />
</details>

<details>
<summary><b>2. Horizon : Cloud-Native Distributed Task Scheduler</b></summary>
<br />
A resilient, decentralized task scheduling engine built to execute millions of background jobs with guaranteed at-least-once delivery semantics and cron-based execution routing.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Go, gRPC, PostgreSQL, Kafka | 5M+ Tasks/day | < 10ms Jitter | mTLS between nodes | Saved $12k/mo in legacy cloud costs | [View Source](#) |

**Professional Overview:**
Engineered a custom raft-based consensus module for leader election among scheduler nodes to prevent single points of failure. Designed the persistent storage schema in PostgreSQL for optimal indexing on execution timestamps. Utilized Kafka for decoupling job ingestion from worker consumption, allowing horizontal scaling of worker nodes across different AWS availability zones.
<br />
</details>

<details>
<summary><b>3. QuantumUI : Performant WebAssembly Analytics Dashboard</b></summary>
<br />
A front-end analytical suite designed to handle millions of data points strictly on the client-side utilizing WebAssembly for intensive computations, freeing up backend resources.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| React, Rust (Wasm), TypeScript | 10M+ Data Points | 60 FPS Render | CSP Enforced | Eliminated backend aggregation bottlenecks | [View Source](#) |

**Professional Overview:**
Transpiled core statistical aggregation algorithms from Rust to WebAssembly, securely bridging them with the React frontend. Implemented virtualized rendering techniques to paint large time-series charts without freezing the main thread. This architectural pivot significantly improved UX while slashing server-side compute requirements during peak traffic hours.
<br />
</details>

---

## ✦ Experience

**Senior Software Engineer** | **Acme Enterprise Technologies**
*Jan 2022 – Present*
Architecting and scaling core platform microservices for high-availability enterprise environments.
*   Spearheaded the migration of a monolithic legacy application to a cloud-native microservices architecture on AWS EKS, reducing deployment cycle times by 60%.
*   Designed and implemented a distributed caching strategy using Redis Cluster, improving API response times by 300% across heavily queried endpoints.
*   Mentored a team of 5 mid-level engineers, enforcing strict CI/CD pipelines, comprehensive code reviews, and TDD practices.
*   `Go` `Kubernetes` `AWS` `PostgreSQL` `gRPC` `Redis`

**Machine Learning Engineer** | **Nexus Data Solutions**
*Aug 2019 – Dec 2021*
Developed end-to-end machine learning models for predictive analytics and natural language processing.
*   Deployed transformer-based NLP models into production using TorchServe, handling over 2M inference requests daily.
*   Built automated data pipelines using Apache Airflow to sanitize, transform, and load terabytes of telemetry data into data lakes.
*   Optimized model inference latencies by 40% through ONNX runtime conversion and weight quantization.
*   `Python` `PyTorch` `Airflow` `Docker` `FastAPI` `MLflow`

---

## ✦ Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| **AWS DeepRacer Champion** | Secured 1st place regionally by optimizing reinforcement learning algorithms for autonomous racing. |
| **Open Source Contributor** | Merged 50+ PRs in major repositories including LangChain, Pandas, and Kubernetes. |
| **Top 1% on LeetCode** | Consistently ranked in the top percentiles globally in advanced algorithmic problem solving. |
| **Hackathon Grand Prize** | Won the Global AI Hackathon out of 300+ teams by building an accessibility-first ML application. |

</div>

---

## ✦ Certifications

<div align="center">
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Professional-4B0082?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Cert" />
  <img src="https://img.shields.io/badge/AWS-Machine_Learning_Specialty-8A2BE2?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS ML Cert" />
  <br />
  <img src="https://img.shields.io/badge/Oracle-Java_SE_11_Developer-9400D3?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Cert" />
  <img src="https://img.shields.io/badge/Cisco-CCNA_Routing_&_Switching-6A5ACD?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Cert" />
  <br />
  <img src="https://img.shields.io/badge/NPTEL-Data_Structures_&_Algorithms-4B0082?style=for-the-badge&logo=canvas&logoColor=white" alt="NPTEL Cert" />
</div>

---

## ✦ Coding Profiles

<div align="center">
  <a href="#"><img src="https://img.shields.io/badge/LeetCode-Top_1%25-0D1117?style=for-the-badge&logo=leetcode&logoColor=9370DB&borderColor=8A2BE2" alt="LeetCode" /></a>
  <a href="#"><img src="https://img.shields.io/badge/GeeksforGeeks-500+_Problems-0D1117?style=for-the-badge&logo=geeksforgeeks&logoColor=9370DB&borderColor=8A2BE2" alt="GeeksforGeeks" /></a>
  <a href="#"><img src="https://img.shields.io/badge/HackerRank-5_Stars-0D1117?style=for-the-badge&logo=hackerrank&logoColor=9370DB&borderColor=8A2BE2" alt="HackerRank" /></a>
  <a href="#"><img src="https://img.shields.io/badge/CodeChef-4_Stars-0D1117?style=for-the-badge&logo=codechef&logoColor=9370DB&borderColor=8A2BE2" alt="CodeChef" /></a>
</div>

---

## ✦ GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=github&show_icons=true&theme=transparent&bg_color=0D1117&title_color=9370DB&text_color=A9B2C3&icon_color=8A2BE2&border_color=4B0082&hide_border=false" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=github&theme=transparent&background=0D1117&ring=8A2BE2&fire=9370DB&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=A9B2C3&sideLabels=A9B2C3&dates=A9B2C3&border=4B0082&hide_border=false" width="48%" alt="Streak Stats" />
  <br />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=github&layout=compact&theme=transparent&bg_color=0D1117&title_color=9370DB&text_color=A9B2C3&border_color=4B0082&hide_border=false" width="50%" alt="Top Languages" />
</div>

---

## ✦ GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=github&theme=dracula&no-bg=true&no-frame=true&margin-w=15&column=7" alt="GitHub Trophies" />
</div>

---

## ✦ Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=github&bg_color=0D1117&color=9370DB&line=8A2BE2&point=FFFFFF&area=true&hide_border=false&border_color=4B0082" width="100%" alt="Activity Graph" />
</div>

---

## ✦ Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/github/github/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/github/github/output/github-contribution-grid-snake.svg" alt="GitHub Snake" width="100%" />
  </picture>
</div>

---

## ✦ Current Focus

```yaml
Current_Focus:
  Learning:
    - "Advanced Rust Systems Programming"
    - "TensorRT Optimizations for LLMs"
    - "Distributed Consensus Algorithms"
  Building:
    - "Enterprise MLOps Orchestrator"
    - "Open-source gRPC Middleware"
  Exploring:
    - "WebAssembly in Cloud Native Environments"
    - "Zero-Knowledge Proofs"
  Open_To:
    - "Senior / Staff Software Engineering Roles"
    - "High-impact Open Source Collaborations"

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8A2BE2,4B0082,9400D3,6A5ACD&height=200&section=header&text=Engineering%20The%20Future&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Enterprise%20Software%20&%20AI%20Specialist&descAlignY=55&descAlign=50" width="100%" alt="Header Banner" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=9370DB&center=true&vCenter=true&width=600&lines=Senior+Software+Engineer;AI+%2F+ML+Product+Engineer;Enterprise+Full+Stack+Architect;Open+Source+Contributor" alt="Typing SVG" />
  
  <br />

  <img src="https://img.shields.io/badge/M.S.%20Computer%20Science-4B0082?style=for-the-badge&logo=proquest&logoColor=white" alt="Academic Badge" />
  <img src="https://img.shields.io/badge/Location-Kakinada,%20AP,%20India-8A2BE2?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location Badge" />

  <br />
  <br />

  <a href="https://my-3-d-portfolio-bay.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=dev.to&logoColor=9370DB&borderColor=8A2BE2" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ram-charan-b4a8b4388"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=9370DB&borderColor=8A2BE2" alt="LinkedIn" /></a>
  <a href="mailto:charan.ganta.6317@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=minutemailer&logoColor=9370DB&borderColor=8A2BE2" alt="Email" /></a>
  <a href="#"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=9370DB&borderColor=8A2BE2" alt="GitHub" /></a>

  <br />
  <br />

  <img src="https://komarev.com/ghpvc/?username=github&color=4B0082&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/github?style=for-the-badge&color=8A2BE2&logo=github" alt="Followers" />
  <img src="https://img.shields.io/github/stars/github?style=for-the-badge&color=9400D3&logo=github" alt="Stars" />
</div>

<br />

---

## ✦ About

I am a **Senior Software Engineer** and **AI/ML Specialist** dedicated to architecting scalable, enterprise-grade distributed systems. With a robust background in advanced computer science principles, I bridge the gap between theoretical machine learning and production-ready software engineering. 

My approach is rooted in a **product engineering mindset**—I do not just write code; I build resilient solutions that drive measurable business impact. I specialize in full-stack development with a heavy emphasis on cloud-native architectures, high-performance computing, and integrating large language models into highly available user-facing applications. 

**Open To:**
*   Senior/Lead Software Engineering roles at product-driven organizations.
*   AI/ML Architect positions focusing on LLM integrations and MLOps.
*   Open-source collaborations in Rust, Python, and Go ecosystems.
*   Technical speaking engagements and mentorship opportunities.

---

## ✦ Tech Stack

<div align="center">
  <br />
  <p><b>Languages</b></p>
  <img src="https://skillicons.dev/icons?i=html,css,js&theme=dark" alt="Languages" />
  <br /><br />
  <p><b>Frameworks</b></p>
  <img src="https://skillicons.dev/icons?i=react,nextjs&theme=dark" alt="Frameworks" />
  <br /><br />
  <p><b>Databases</b></p>
  <img src="https://skillicons.dev/icons?i=firebase,supabase&theme=dark" alt="Databases" />
  <br /><br />
  <p><b>Cloud, DevOps & Tooling</b></p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,linux,githubactions,nginx&theme=dark" alt="Cloud and DevOps" />
</div>
<br />

---

## ✦ AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **Large Language Models (LLMs)** | Advanced | RAG, Fine-tuning (LoRA/QLoRA), Prompt Engineering, LangChain, LlamaIndex |
| **Computer Vision** | Advanced | Object Detection (YOLO, Faster R-CNN), Image Segmentation, OpenCV, PyTorch |
| **Natural Language Processing** | Advanced | Transformer architectures, BERT, Sentiment Analysis, Named Entity Recognition |
| **MLOps & Deployment** | Intermediate | Model serving (Triton, TorchServe), MLflow, ONNX runtime, TensorRT optimization |
| **Data Engineering** | Intermediate | Distributed data processing, Apache Spark, Feature Engineering pipelines |

---

## ✦ Featured Projects

<details>
<summary><b>1. NexusAI : Enterprise RAG Pipeline Architecture</b></summary>
<br />
An asynchronous, high-throughput Retrieval-Augmented Generation (RAG) microservice designed for processing secure, internal enterprise documents with strict access controls. 

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Python, FastAPI, Milvus, Redis | 100k+ Docs/day | < 400ms TTFT | SOC2 Compliant, TLS 1.3 | Reduced support ticket volume by 45% | [View Source](#) |

**Professional Overview:**
Architected the ingestion and query pipelines leveraging state-of-the-art embedding models. Implemented advanced vector search mechanisms combined with hybrid sparse/dense retrieval, ensuring high precision in domain-specific contexts. The system was dockerized and orchestrated via Kubernetes to dynamically scale GPU nodes based on inference load, drastically reducing operational overhead.
<br />
</details>

<details>
<summary><b>2. Horizon : Cloud-Native Distributed Task Scheduler</b></summary>
<br />
A resilient, decentralized task scheduling engine built to execute millions of background jobs with guaranteed at-least-once delivery semantics and cron-based execution routing.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Go, gRPC, PostgreSQL, Kafka | 5M+ Tasks/day | < 10ms Jitter | mTLS between nodes | Saved $12k/mo in legacy cloud costs | [View Source](#) |

**Professional Overview:**
Engineered a custom raft-based consensus module for leader election among scheduler nodes to prevent single points of failure. Designed the persistent storage schema in PostgreSQL for optimal indexing on execution timestamps. Utilized Kafka for decoupling job ingestion from worker consumption, allowing horizontal scaling of worker nodes across different AWS availability zones.
<br />
</details>

<details>
<summary><b>3. QuantumUI : Performant WebAssembly Analytics Dashboard</b></summary>
<br />
A front-end analytical suite designed to handle millions of data points strictly on the client-side utilizing WebAssembly for intensive computations, freeing up backend resources.

| Stack | Scale | Performance | Security | Impact | Repository |
| :--- | :--- | :--- | :--- | :--- | :--- |
| React, Rust (Wasm), TypeScript | 10M+ Data Points | 60 FPS Render | CSP Enforced | Eliminated backend aggregation bottlenecks | [View Source](#) |

**Professional Overview:**
Transpiled core statistical aggregation algorithms from Rust to WebAssembly, securely bridging them with the React frontend. Implemented virtualized rendering techniques to paint large time-series charts without freezing the main thread. This architectural pivot significantly improved UX while slashing server-side compute requirements during peak traffic hours.
<br />
</details>

---

## ✦ Experience

**Senior Software Engineer** | **Acme Enterprise Technologies**
*Jan 2022 – Present*
Architecting and scaling core platform microservices for high-availability enterprise environments.
*   Spearheaded the migration of a monolithic legacy application to a cloud-native microservices architecture on AWS EKS, reducing deployment cycle times by 60%.
*   Designed and implemented a distributed caching strategy using Redis Cluster, improving API response times by 300% across heavily queried endpoints.
*   Mentored a team of 5 mid-level engineers, enforcing strict CI/CD pipelines, comprehensive code reviews, and TDD practices.
*   `Go` `Kubernetes` `AWS` `PostgreSQL` `gRPC` `Redis`

**Machine Learning Engineer** | **Nexus Data Solutions**
*Aug 2019 – Dec 2021*
Developed end-to-end machine learning models for predictive analytics and natural language processing.
*   Deployed transformer-based NLP models into production using TorchServe, handling over 2M inference requests daily.
*   Built automated data pipelines using Apache Airflow to sanitize, transform, and load terabytes of telemetry data into data lakes.
*   Optimized model inference latencies by 40% through ONNX runtime conversion and weight quantization.
*   `Python` `PyTorch` `Airflow` `Docker` `FastAPI` `MLflow`

---

## ✦ Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| **AWS DeepRacer Champion** | Secured 1st place regionally by optimizing reinforcement learning algorithms for autonomous racing. |
| **Open Source Contributor** | Merged 50+ PRs in major repositories including LangChain, Pandas, and Kubernetes. |
| **Top 1% on LeetCode** | Consistently ranked in the top percentiles globally in advanced algorithmic problem solving. |
| **Hackathon Grand Prize** | Won the Global AI Hackathon out of 300+ teams by building an accessibility-first ML application. |

</div>

---

## ✦ Certifications

<div align="center">
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Professional-4B0082?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Cert" />
  <img src="https://img.shields.io/badge/AWS-Machine_Learning_Specialty-8A2BE2?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS ML Cert" />
  <br />
  <img src="https://img.shields.io/badge/Oracle-Java_SE_11_Developer-9400D3?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Cert" />
  <img src="https://img.shields.io/badge/Cisco-CCNA_Routing_&_Switching-6A5ACD?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Cert" />
  <br />
  <img src="https://img.shields.io/badge/NPTEL-Data_Structures_&_Algorithms-4B0082?style=for-the-badge&logo=canvas&logoColor=white" alt="NPTEL Cert" />
</div>

---

## ✦ Coding Profiles

<div align="center">
  <a href="#"><img src="https://img.shields.io/badge/LeetCode-Top_1%25-0D1117?style=for-the-badge&logo=leetcode&logoColor=9370DB&borderColor=8A2BE2" alt="LeetCode" /></a>
  <a href="#"><img src="https://img.shields.io/badge/GeeksforGeeks-500+_Problems-0D1117?style=for-the-badge&logo=geeksforgeeks&logoColor=9370DB&borderColor=8A2BE2" alt="GeeksforGeeks" /></a>
  <a href="#"><img src="https://img.shields.io/badge/HackerRank-5_Stars-0D1117?style=for-the-badge&logo=hackerrank&logoColor=9370DB&borderColor=8A2BE2" alt="HackerRank" /></a>
  <a href="#"><img src="https://img.shields.io/badge/CodeChef-4_Stars-0D1117?style=for-the-badge&logo=codechef&logoColor=9370DB&borderColor=8A2BE2" alt="CodeChef" /></a>
</div>

---

## ✦ GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=github&show_icons=true&theme=transparent&bg_color=0D1117&title_color=9370DB&text_color=A9B2C3&icon_color=8A2BE2&border_color=4B0082&hide_border=false" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=github&theme=transparent&background=0D1117&ring=8A2BE2&fire=9370DB&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=A9B2C3&sideLabels=A9B2C3&dates=A9B2C3&border=4B0082&hide_border=false" width="48%" alt="Streak Stats" />
  <br />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=github&layout=compact&theme=transparent&bg_color=0D1117&title_color=9370DB&text_color=A9B2C3&border_color=4B0082&hide_border=false" width="50%" alt="Top Languages" />
</div>

---

## ✦ GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=github&theme=dracula&no-bg=true&no-frame=true&margin-w=15&column=7" alt="GitHub Trophies" />
</div>

---

## ✦ Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=github&bg_color=0D1117&color=9370DB&line=8A2BE2&point=FFFFFF&area=true&hide_border=false&border_color=4B0082" width="100%" alt="Activity Graph" />
</div>

---

## ✦ Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/github/github/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/github/github/output/github-contribution-grid-snake.svg" alt="GitHub Snake" width="100%" />
  </picture>
</div>

---

## ✦ Current Focus

```yaml
Current_Focus:
  Learning:
    - "Advanced Rust Systems Programming"
    - "TensorRT Optimizations for LLMs"
    - "Distributed Consensus Algorithms"
  Building:
    - "Enterprise MLOps Orchestrator"
    - "Open-source gRPC Middleware"
  Exploring:
    - "WebAssembly in Cloud Native Environments"
    - "Zero-Knowledge Proofs"
  Open_To:
    - "Senior / Staff Software Engineering Roles"
    - "High-impact Open Source Collaborations"

✦ Connect
<div align="center">
<a href="mailto:charan.ganta.6317@gmail.com"><img src="https://img.shields.io/badge/Gmail-Contact_Me-0D1117?style=for-the-badge&logo=gmail&logoColor=9370DB&borderColor=8A2BE2" alt="Gmail" /></a>
<a href="https://www.linkedin.com/in/ram-charan-b4a8b4388"><img src="https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=9370DB&borderColor=8A2BE2" alt="LinkedIn" /></a>
<a href="#"><img src="https://img.shields.io/badge/GitHub-Follow-0D1117?style=for-the-badge&logo=github&logoColor=9370DB&borderColor=8A2BE2" alt="GitHub Follow" /></a>
<a href="https://my-3-d-portfolio-bay.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-0D1117?style=for-the-badge&logo=dev.to&logoColor=9370DB&borderColor=8A2BE2" alt="Portfolio Visit" /></a>
</div>
<div align="center">
<i>"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra</i>
</div>
<br />
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=9400D3,4B0082,8A2BE2,6A5ACD&height=100&section=footer" width="100%" alt="Footer Banner" />
</div>

