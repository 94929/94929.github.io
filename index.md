---
layout: default
title: Jinsung Ha (하진성)
---

## About Me

---

> Machine Learning Engineer with 4+ years of work experience.

<details>
    <summary>If you'd like to know more about me, click then type `import jinsung`</summary>
    <iframe frameborder="0" width="98%" height="335px" src="brython/index.html"></iframe>
</details>

## Interest

---

> Machine Learning Engineering (ML Serving and MLOps)

## Techical Skills

---

> Languages: Python, Typescript  
> Backend Frameworks: FastAPI, NestJS  
> Deep Learning Framework: PyTorch  

## Work Experience

---

**[Dable](https://dable.io/en)** (Subsidiary of [Yanolja](https://yanolja.in/en)) | South Korea (Jul 2022 - Present)  
_Machine Learning Engineer (전문연구요원 전직)_  
_AI Team (online ads system)_

Server Side: (focused on optimizing the p99 latency and throughput)
- Maintained onnx-based ML model inference server processing 100k+ requests per minute.
- Implemented redis-cluster-based online feature store for mobile app DSP.
- Improved p99 latency and throughput of inference server, based on cpu profiled data.
- Reduced memory usage by 5X using shared memory, resulting in cost savings.
- Decreased model preparation time by 5X through implementing a model caching storage.
- Enhanced ML server observability with custom Prometheus metrics and Grafana dashboards.
- Implemented centralized logging system using CloudWatch Logs and Athena.
- Automated server code deployment, loadtesting, linting, code review.
- Refactored inference server structure for improved efficiency and manageability.
- Restructured inference architecture to support model ensemble methods.

Infra Side: (focused on optimizing the pipelining cost)
- Led migration of server applications to EKS cluster.
- Maintained Airflow DAGs for model pipeline (sensors, training, calibration etc).
- Improved pipeline job observability and fixed failing Airflow tasks.

Model Side: (focused on optimizing [RoAS](https://www.appsflyer.com/glossary/roas))
- Analyzed data of underperforming models to optimize budget allocation.
- Discovered and implemented new features, improving offline AUC of ML models.
- Developed new calibration model logic, increasing RoAS by 3X.
- Conducted A/B testing on calibrated pCTR model.

_Vision Team (offline ads system)_

- Involved in both SW 1.0 and 2.0 part of the vision team.
- Light-weighted edge device containing ads player and inference module by optimization.
- Proposed a custom DAG Scheduler pipeline for asynchronous ADs update.
- Implemented a data processor for raw edge logs to provide realtime aggregation.
- Implemented people counter module based on people tracking module, used in COEX convention hall.

**[LUXROBO](https://global.luxrobo.com/eng)** | South Korea (Jan 2020 - Jul 2022)  
_Machine Learning Engineer (전문연구요원 편입)_

- Implemented MODI Python API, [PyMODI](https://github.com/luxrobo/pymodi) for MODI AI KIT.
- Enhaned usability of MODI by implementing SWs including MODI Firmware Updater, VirtualMODI.
- Led AI Team to win 2nd place in AI Championship 2020.
- Conducted a side-research on depth completion, published our research to CVPR 2022.
- Structured an automated data pipeline recommendation system APIs of LMS.
- Received the best peer (of AI) prize in 2021, nominated by colleagues.

**[Schlumberger UK](https://www.slb.com/about/rd/technology/abtc.aspx)** | United Kingdom (Mar 2018 - Sep 2018)  
_Machine Learning Engineering Intern_

- Implemented a machine learning program which predicts an optimal node group for small-sized reservoir simulation in HPC environment.

**[NEOWIZ](https://www.neowiz.com/neowiz?t=1)** | South Korea (Aug 2017 - Sep 2017)  
_Machine Learning Engineering Intern_

- Implemented a deep musical note generator for a rhythm game called Tapsonic.

## Research Experience

---

**GuideFormer: Transformers for Image Guided Depth Completion**  
Kyeongha Rho\*, [Jinsung Ha](https://94929.github.io)\*, Youngjung Kim  
_IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2022_  
[[pdf](https://openaccess.thecvf.com/content/CVPR2022/papers/Rho_GuideFormer_Transformers_for_Image_Guided_Depth_Completion_CVPR_2022_paper.pdf)]

- We propose a fully transformer-based architecture for depth completion.

**User-Guided Colorization Using Optimization and Learned Similarity**  
[Jinsung Ha](https://94929.github.io)\*, [Shuyu Lin](https://shuyulin.co.uk)\*, [Ronald Clark](https://www.ron-clark.com)

- We propose an optimization based deep learning approach for user-guided colorization.

## Thesis

---

**Self-Supervised Learning for Depth Image Completion and Enhancement**  
Co-Supervised by [Dr Ronald Clark](https://www.ron-clark.com) and [Dr Sajad Saeedi](https://www.sajad-saeedi.ca) at [Dyson Robotics Lab](https://www.imperial.ac.uk/dyson-robotics-lab)  
_Achieved First Class Honours (Distinction)_

- The objective is to use deep learning to enhance the depth data thus it can be used to its full benefit in robotic perception tasks.

## Education

---

**[Imperial College London](https://www.imperial.ac.uk/computing)** | London, United Kingdom (Oct 2014 - Oct 2019)  
_[MEng Computing](https://www.imperial.ac.uk/study/courses/undergraduate/computing-meng/) (Artificial Intelligence)_, Achieved 2:1  
_학석사통합과정 전산학 (인공지능)_, GPA 3.3/4.0

- Year 1. Programming, Databases, Architecture, Hardware, Discrete Maths, Maths Methods, Logic, Reasoning about Programs
- Year 2. Artificial Intelligence, Algorithms, Operating Systems, Networks, Software Designs, Statistics, Concurrency, Compilers, Models of Computation, Computational Techniques
- Year 3. Machine Learning, Computer Vision, Robotics, Web Security, Distributed Algorithms, Graphics, Advanced Databases
- Year 4. Deep Learning, Reinforcement Learning, Natural Language Processing, ML for imaging, Maths for ML, Machine Arguing, Distributed Ledgers, Software Engineering for Industry

## Projects

---

[![Hanc marginis exiguitas non caperet.](./projects.png)](https://jinsungha.notion.site/12716fbd7f154ac4a776ba206b950061)

## Awards & Activities

---

**창업진흥원장상 (2nd Place in [LG Science Park Section](https://youtu.be/kNiEJx1Sl7M))** | [AI Championship 2020](http://kstartup-aic.com)  
_[LUXROBO AI Team](https://youtu.be/WvvKBmTsPTY?t=5822)_

- Developed a deep ensemble network to detect anomaly in noise inspection of electronics.

**[Opensource Contributon 2021](https://www.oss.kr/contribution_academy)** | [Open Source Software KR](https://www.oss.kr)  
_Participant_

- Contributed to [pytorch-tutorials-kr](https://tutorials.pytorch.kr) by translating official docs in Korean.

## Certifications

---

| Name                             | Issued by   | Expires on |
| -------------------------------- | ------------| ---------- |
| Tensorflow Developer Certificate | Tensorflow  | Jan 2024   |
| Terraform Associate (003)        | HashiCorp   | Sep 2025   |

## Opensource Contributions

---

| Project                                                                              | Role        | PR #       |
| ------------------------------------------------------------------------------------ | ----------- | ---------- |
| [pymodi](https://github.com/LUXROBO/pymodi)                                          | Maintainer  | \>= 97     |
| [modi-firmware-updater](https://github.com/LUXROBO/modi-firmware-updater)            | Author      | \>= 1      |
| [iamport-rest-client-python](https://github.com/iamport/iamport-rest-client-python)  | Maintainer  | \>= 43     |
| [ray](https://github.com/ray-project/ray)                                            | Contributor | 38496      |
| [pyupbit](https://github.com/sharebook-kr/pyupbit)                                   | Contributor | 5, 7, 8, 9 |
| [pytorch-tutorials-kr](https://github.com/9bow/PyTorch-tutorials-kr)                 | Contributor | 276        |
| [backend-interview-question](https://github.com/ksundong/backend-interview-question) | Contributor | 24         |
| [virtual-modi](https://github.com/LUXROBO/virtual-modi)                              | Author      | \>= 1      |

## Languages

---

Korean(native) and English(fluent)
