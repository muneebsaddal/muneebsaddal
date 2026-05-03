<h1 align="center">Muhammad Muneeb Arshad</h1>

<p align="center">
  <b>Data Scientist | AI Systems Engineer | Computer Vision & LLM Automation</b>
</p>

<p align="center">
  <a href="https://github.com/muneebsaddal">
    <img src="https://img.shields.io/badge/GitHub-muneebsaddal-181717?style=for-the-badge&logo=github" alt="GitHub profile" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Production%20AI%20Systems-0A66C2?style=for-the-badge" alt="Production AI systems" />
  <img src="https://img.shields.io/badge/Specialty-Computer%20Vision-2E7D32?style=for-the-badge" alt="Computer vision" />
  <img src="https://img.shields.io/badge/Specialty-LLM%20Agents-6A1B9A?style=for-the-badge" alt="LLM agents" />
</p>

I build end-to-end AI systems that move from dataset strategy and model training into production deployment, monitoring, and automation. My work sits at the intersection of industrial computer vision, medical imaging, sports analytics, deterministic LLM orchestration, and enterprise workflow automation.

I care about AI systems that are measurable, inspectable, and reliable: schema-first validation, bounded retries, reproducible traces, human escalation paths, and observability dashboards are part of how I design production workflows.

---

## What I Build

| Area | Work I Do |
| --- | --- |
| Computer Vision | Defect detection, instance segmentation, OCR, medical imaging, sports analytics, pose estimation, keypoint detection |
| LLM Systems | LangGraph agents, planner/executor/validator workflows, schema-governed outputs, RAG, local LLMs, multimodal pipelines |
| Production ML | Dataset engineering, annotation pipelines, model training, evaluation, deployment, monitoring, client-side integration |
| Automation | FastAPI services, n8n/Zapier-compatible webhooks, Redis-backed state, human-in-the-loop routing, real-time dashboards |
| Business Intelligence | Power BI dashboards, financial analytics, operational KPIs, sales and profitability analysis |

---

## Core Stack

**Languages:** Python, SQL, JavaScript, TypeScript  
**ML/DL:** PyTorch, TensorFlow, Keras, scikit-learn, Hugging Face Transformers  
**Computer Vision:** YOLOv8/v11, DETR, Mask R-CNN, CNNs, OpenCV, CVAT, OCR pipelines  
**LLM & Agents:** LangGraph, LangChain, OpenAI GPT-4o, Claude, Ollama, LLaVA-OneVision, mBART, LoRA  
**Retrieval & NLP:** RAG, FAISS, Sentence Transformers, TF-IDF, semantic search  
**Backend & Apps:** FastAPI, Flask, React/Vite, Streamlit, WebSocket, REST APIs  
**Infrastructure:** Docker, Linux, Redis, Celery, GitHub Actions, remote GPU environments  
**Production Patterns:** Pydantic v2, schema registries, circuit breakers, bounded retries, audit trails, replayable traces

---

## Featured Systems

### AI Automation Platform

Production-grade agent orchestration platform with FastAPI, LangGraph, Redis, React/Vite, and WebSocket observability.

- Built a planner/executor/validator multi-agent pipeline with structured state and bounded retry routing.
- Designed six-panel real-time monitoring for raw input, graph state transitions, structured output, validation errors, logs, and tool results.
- Added complete trace export and replay endpoints so every run can be inspected, diffed, audited, or reproduced.

**Stack:** LangGraph, FastAPI, Redis, React, WebSocket, Pydantic, OpenAI/Ollama

### Signal Builder Agent

Schema-governed AI system for trading signal generation using an Intermediate Representation layer.

- Solved the "schema explosion" problem by having the LLM produce compact IR objects while deterministic resolvers map them to full schemas.
- Built a four-stage LangGraph pipeline: intent classification, IR generation, IR validation, and schema resolution.
- Managed 25+ versioned signal definitions with strict Pydantic validation and low-temperature generation for consistency.

**Stack:** LangGraph, Pydantic, schema registry, OpenAI/Ollama, structured validation

### AI Ops Agent System

Multi-agent DevOps automation system designed for autonomous workflow execution from natural language requests.

- Implemented planner, executor, and validator agents with Redis-backed shared state.
- Added context-aware retries where validation failures feed structured error reasons back into the next execution attempt.
- Built robust JSON parsing with self-correction, markdown-fence handling, and first-valid-block extraction.

**Stack:** LangGraph, Redis, Python, FastAPI, LLM tooling, structured logs

### Industrial Computer Vision Systems

Production ML pipelines for quality control and manufacturing automation.

- Designed annotation guidelines, class definitions, boundary-case rules, and labeling workflows for defect detection projects.
- Developed detection, segmentation, classification, and OCR systems using YOLO, DETR, Mask R-CNN, and lightweight edge-ready models.
- Built preprocessing and post-processing pipelines for reliable inference under real-world lighting, angle, and image-quality variation.

**Stack:** YOLOv8/v11, DETR, Mask R-CNN, OpenCV, OCR, CVAT, PyTorch

### Padel Sports Analytics

Training-first sports analytics system for player detection, pose estimation, ball tracking, and court keypoint detection.

- Normalized datasets from multiple sources into training-ready formats.
- Built temporal smoothing inference logic for more stable analytics outputs.
- Created CVAT handoff workflows for continuous annotation and retraining.

**Stack:** YOLO, pose estimation, keypoint detection, CVAT, Python, OpenCV

### Multimodal Arabic Sign Language Translation

Three-stage vision-language pipeline adapting MMSLT for Arabic Sign Language on the Isharah-500 dataset.

- Processed 7,500 videos across signer-independent and unseen-sentence splits.
- Used LLaVA-OneVision for offline gesture descriptions, CLIP visual features, and mBART with LoRA adapters for Arabic translation.
- Designed ablation studies to quantify the value of visual features, textual descriptions, mapper alignment, and pipeline components.

**Stack:** LLaVA-OneVision, CLIP ViT-L/14, mBART-large-50, LoRA, PyTorch, 4-bit quantization

---

## Selected Project Portfolio

| Project | Domain | Highlights |
| --- | --- | --- |
| Deterministic AI Processor | LLM Automation | Compiler-like LLM pipeline, strict schema validation, max-1 retry strategy, local Ollama deployment |
| AI Workflow Automation Agent | Enterprise Automation | Intent routing, create/update/escalate paths, n8n webhook support, human-in-the-loop handling |
| RAG Document Q&A System | NLP | TF-IDF retrieval, semantic chunking, context-grounded answers, Flask API |
| Medical X-ray Vertebral Segmentation | Medical Imaging | Adapted TotalSpineSeg from 3D MRI to 2D X-ray, synthetic DRR data, clinical overlay outputs |
| Skin Disease Detection App | Medical AI | CNN and transfer-learning classifiers deployed through Flask for image upload and prediction |
| Diabetic Retinopathy Classification | Medical AI | APTOS 2019 grading, CLAHE preprocessing, 5-class severity classification |
| Pneumonia Classification | Medical AI | Custom CNN for chest X-rays with precision, recall, F1, and confusion-matrix validation |
| Financial News Sentiment Pipeline | NLP / FinTech | VADER, FinBERT, scraping/API ingestion, time-series sentiment visualization |
| Global Retail Power BI Dashboard | BI | Power Query, DAX, KPI scorecards, geospatial views, profitability analysis |
| OpenSky Flight Data Pipeline | Data Engineering | Real-time aviation API ingestion, geospatial EDA, Folium maps, flight-density analysis |

---

## Professional Experience

### Data Scientist, Elunic GmbH

**December 2025 - Present**

Building industrial computer vision and production ML systems for quality control and manufacturing automation.

- Own end-to-end CV solution development from problem definition, data strategy, and annotation planning to training, deployment, and monitoring.
- Develop real-time defect detection, instance segmentation, classification, and OCR pipelines for production environments.
- Coordinate annotation workflows and translate quality requirements into precise dataset guidelines.

### Freelance AI Engineer, Upwork

**2025 - Present**

Delivering production AI systems across computer vision, automation, medical imaging, sports analytics, and multimodal AI.

- Built LangGraph-based automation systems with FastAPI, Redis, Pydantic validation, webhook integration, and human escalation.
- Developed sports analytics, manufacturing vision, medical segmentation, sign-language translation, RAG, and deterministic LLM workflows.
- Focused on practical deployment constraints: GPU cost, model size, inference reliability, retraining workflows, and client review cycles.

### Software Engineer, Emumba

**March 2022 - November 2022**

Worked on full-stack production applications and DevOps workflows.

- Built React and TypeScript frontend features with MUI and Ant Design.
- Implemented CI/CD pipelines with GitHub Actions.
- Developed maintainable, state-driven user journeys with modern React patterns.

### Managing Partner, Floreat Enterprises

**2020 - 2025**

Led operations, sales, inventory, logistics, and client management for a surgical instruments export business.

- Introduced sales tracking, inventory analytics, cost analysis, and KPI-driven planning.
- Built practical business understanding that now informs AI, analytics, and automation work.

---

## Education & Certifications

**BS Computer Science**  
National University of Sciences and Technology (NUST), 2016 - 2020

**Certifications**

- Machine Learning Specialization
- MERN Stack Full Ecommerce Site
- Front-End Web UI Frameworks and Tools: Bootstrap 4
- Microsoft Office Specialist Master Certification

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=muneebsaddal&show_icons=true&hide_border=true&theme=default" alt="Muhammad Muneeb Arshad GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=muneebsaddal&layout=compact&hide_border=true&theme=default" alt="Top languages" />
</p>

---

## How I Think About AI Systems

I do not treat LLMs or vision models as magic boxes. I prefer production architectures where each component has a contract:

- Inputs and outputs are validated.
- Failures are bounded and observable.
- Traces can be replayed.
- Human review is routed intentionally.
- Models sit inside deterministic software, not outside it.

That philosophy shows up whether I am building a YOLO defect detector for a manufacturing line, a LangGraph automation agent, a medical imaging pipeline, or a multimodal translation system.

---

## Open To

- Production computer vision systems
- Industrial defect detection and OCR
- LLM agent orchestration and automation platforms
- RAG and schema-governed AI workflows
- Medical imaging and sports analytics pipelines
- AI system audits, prototyping, and deployment consulting

<p align="center">
  <a href="https://github.com/muneebsaddal">
    <img src="https://img.shields.io/badge/View%20My%20Work-GitHub-181717?style=for-the-badge&logo=github" alt="View my work on GitHub" />
  </a>
</p>
