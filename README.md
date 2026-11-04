<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:090014,35:240046,70:5A189A,100:4361EE&text=ABHILASH%20REDDY%20SOMIGARI&fontColor=FFFFFF&fontSize=40&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20AI%2FML%20Engineer&descAlignY=58&descSize=17&animation=fadeIn"/>

<a href="https://abhilashsomigari.github.io"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/abhilashreddysomigari"><img src="https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:abhilashreddysomigari@gmail.com"><img src="https://img.shields.io/badge/Email-5B21B6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

## About

M.S. Computer Science student at West Virginia University (GPA 3.87, graduating Dec 2026). I build LLM agents with evaluation gates, explainable computer-vision pipelines, and ROS 2 control nodes for F1TENTH cars.

**Open to:** Software Engineering · AI/ML Engineering · Applied AI roles.

## Projects

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**OpsPilot**](https://github.com/AbhilashSomigari/opspilot) | AI incident-response agent that root-causes incidents with 5 evidence tools (metrics, logs, traces, deploys, RAG). **93% accuracy vs. a 30% LLM-only baseline** on a 30-incident benchmark; human-approval gate with **0 unsafe actions in 90 investigations** | LangGraph · FastAPI · PostgreSQL · OpenTelemetry |
| [**EvalForge**](https://github.com/AbhilashSomigari/evalforge) | CI/CD evaluation harness for tool-using agents, published to PyPI as [`evalforge-agents`](https://pypi.org/project/evalforge-agents/): YAML scenario suites, **11 graders**, **104 tests**, CI baseline gates | Python · FastAPI · PostgreSQL |
| [**ProspectPilot**](https://github.com/AbhilashSomigari/prospectpilot) | Multi-agent SDR pipeline (prospect → enrich → verify → write/critique) with an EvalForge-gated self-improvement loop; **960 seeded eval trials** with paired bootstrap CIs and significance-gated prompt promotion | LangGraph · FastAPI · pgvector · Terraform |
| [**Cloud Forecasting**](https://github.com/AbhilashSomigari/spatiotemporal-cloud-forecasting) | Next-frame cloud forecasting on 864 GOES-16 frames; a residual CNN cuts 5-minute MAE **35% below a persistence baseline** | PyTorch · CNN · ConvLSTM |
| [**YOLOv5 Satellite XAI**](https://github.com/AbhilashSomigari/yolov5-satellite-image-detector) | YOLOv5 fine-tuned on hand-labeled satellite imagery, with a Grad-CAM / EigenCAM / Integrated Gradients pipeline that scores explanation faithfulness | PyTorch · YOLOv5 · Captum |
| [**Multi-Agent Debate RAG**](https://github.com/AbhilashSomigari/multi_agent-debate-rag) | Local RAG where two retriever agents answer with citations, cross-examine each other, and a judge synthesizes; a checker rewrites any uncited claims | LangGraph · Ollama · Chroma |
| **F1TENTH (ROS 2)** | Nodes run on the physical car: [automatic emergency braking](https://github.com/AbhilashSomigari/automatic-emergency-braking), [follow the gap](https://github.com/AbhilashSomigari/follow-the-gap), [pure pursuit](https://github.com/AbhilashSomigari/pure-pursuit), and uncertainty-aware speed control ([fast-when-certain](https://github.com/AbhilashSomigari/fast-when-certain), in progress) | ROS 2 · Python |
| [**FRAS**](https://github.com/AbhilashSomigari/FRAS) | Face-recognition classroom attendance with webcam enrollment, live recognition, and PDF reports | OpenCV · Python |

## Experience

**Graduate Research Assistant** · West Virginia University · `Aug 2025 – Aug 2026`
- Cut manual heatmap inspection by **70%** with a custom XAI faithfulness metric (localization-curve AUC) for the YOLOv5 satellite detector, and cut experiment iteration time by **50%** with a Flask + React app.
- Built a SAM3 segmentation pipeline over **20** laparoscopic surgery videos. Scaling-based normalization made cross-frame comparisons **30%** more reliable, and automated cut-ratio analysis cut manual review by **40%**.

**Teaching Assistant (Data-Driven WV)** · West Virginia University · `Jan 2026 – May 2026`
- Built GOES-16 data pipelines and starter code, cutting student setup time by **30%** and raising submission success by **35%**.

**Software Developer Intern** · SAK Informatics, Hyderabad · `Jan 2024 – Mar 2024`
- Built Python automation, data pipelines, and Flask REST APIs, reducing manual data handling by **30%**.

**Mentor** · Smart Interviews, Hyderabad · `Oct 2023 – Dec 2023`
- Mentored **80+ students** in data structures and algorithms.

## Education

- **M.S. Computer Science**, West Virginia University · Jan 2025 – Dec 2026 (expected) · GPA 3.87/4.00
- **B.Tech Computer Science**, JNTU Hyderabad · Nov 2020 – Jun 2024

## Certifications

- [Oracle Agentic AI Certified Foundations Associate](https://catalog-education.oracle.com/ords/certview/sharebadge?id=1661EBC4F263E80EBE1FD8C1FD7E4E5256B262640FCCF7CCF8538FAAD9B6838C) (2026)
- [IBM RAG and Agentic AI Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/FNK3SB94JT4C) (2025)
- [Smart Interviews Certified Smart Coder](https://smartinterviews.in/certificate/07f6d372)

## Skills

<img src="https://skillicons.dev/icons?i=python,java,cpp,ts,js,react,nextjs,fastapi,flask,django,postgres,docker,kubernetes,aws,terraform,githubactions,linux&theme=dark" alt="Skills"/>

![PyTorch](https://img.shields.io/badge/PyTorch-312E81?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-4338CA?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5B21B6?style=flat-square&logo=opencv&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-6D28D9?style=flat-square&logo=langchain&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-7C3AED?style=flat-square&logo=postgresql&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS%202-4C1D95?style=flat-square&logo=ros&logoColor=white)

**Coding profiles:**
[LeetCode](https://leetcode.com/u/ab_reddy27/) ·
[Codeforces](https://codeforces.com/profile/ab_reddy27) ·
[CodeChef](https://www.codechef.com/users/ab_reddy27) ·
[HackerRank](https://www.hackerrank.com/profile/abhilashreddy027)

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AbhilashSomigari/AbhilashSomigari/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AbhilashSomigari/AbhilashSomigari/output/github-contribution-grid-snake.svg"/>
  <img width="100%" src="https://raw.githubusercontent.com/AbhilashSomigari/AbhilashSomigari/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake"/>
</picture>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:090014,35:240046,70:5A189A,100:4361EE"/>

</div>
